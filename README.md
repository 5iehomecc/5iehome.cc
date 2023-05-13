# 网站静态资源调用

## 目录结构
- img：存放文章封面，配图，结合 PigGo token，用于直接 PigGo 上传图片
  - 其他用户可访问地址：`https://raw.githubusercontent.com/5iehomecc/wpblog/master/img/xxx.webp`
- fonts：存放自定义字体
- css：存放 css 文件
- js：存放 js 文件
- wp-plugins：存放插件

## JsDelivr CDN 加速地址
调用仓库里的 css/js/图片/字体 等静态资源
- `https://cdn.jsdelivr.net/gh/5iehomecc/wpblog@latest/img/`
- `https://cdn.jsdelivr.net/gh/5iehomecc/wpblog@latest/fonts/`

考虑到之前 `cdn.jsdelivr.net` 曾经访问不了，可以用以下域名替代

```
fastly.jsdelivr.net
gcore.jsdelivr.net
originfastly.jsdelivr.net
quantil.jsdelivr.net
```
