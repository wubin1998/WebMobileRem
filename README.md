# WebMobileRem
网页移动端rem适配方案


```html
<meta name="viewport" content="initial-scale=1,maximum-scale=1, minimum-scale=1,user-scalable=0">
<script>
var deviceWidth = document.documentElement.clientWidth;
document.documentElement.style.fontSize = deviceWidth / 7.5 + "px";
<!-- 
  这里设置字体大小除于7.5的意思是:
  设计稿宽度750 / 100 = 7.5;

  尺寸等于 100px = 1rem;

  例如设计稿，按钮宽度是80px;
  那么设置width为0.8rem; 任何值只需除于100得到rem值;
 -->
</script>
```