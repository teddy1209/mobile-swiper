# 移动端轮播图

## 根据 https://aotu.io/notes/2017/07/17/design-a-swiper/ 提供代码和思路做了一些修改

## 卡片轮播组件使用方法
```html
<!-- 设置为false则不自动轮播，设置数字为自动轮播时间(毫秒) -->
<ul id="selector" autoplay="3000"> 
    <li>
        <img src="1.jpg">
    </li>
    <li>
        <img src="2.jpg">
    </li>
    <li>
        <img src="3.jpg">
    </li>
    <li>
        <img src="4.jpg">
    </li>
    <li>
        <img src="5.jpg">
    </li>
</ul>
<script>
    new mobileSwiper("#selector"); //传入ul的id
</script>
```
