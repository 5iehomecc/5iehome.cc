## 回到顶部
1. 引用 jquery 库和 jquery.goup.js 到 index.html
```java
  <script src="https://fastly.jsdelivr.net/gh/5iehomecc/wpblog@latest/js/uptotop/jquery.js"></script>
  <script src="https://fastly.jsdelivr.net/gh/5iehomecc/wpblog@latest/js/uptotop/jquery.goup.js"></script>
```
2. 再调用下插件
```java
<script type="text/javascript">
    $(document).ready(function () {
      $.goup({
        trigger: 100,
        bottomOffset: 32,
        locationOffset: 32,
        title: 'TOP',
        titleAsText: true
      });
    });
  </script>
```
