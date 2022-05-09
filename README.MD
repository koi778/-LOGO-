自定义代码
可以去版权、改LOGO、加统计代码等等。

默认主题更改进度条颜色示例

<style>
.ui.fine.progress> .bar {
    background-color: pink !important;
}
</style>
默认主题修改LOGO、移除版权示例（来自 @iLay1678，欢迎PR）

<style>
.right.menu>a{
visibility: hidden;
}
.footer .is-size-7{
visibility: hidden;
}
.item img{
visibility: hidden;
}
</style>
<script>
window.onload = function(){
var avatar=document.querySelector(".item img")
var footer=document.querySelector("div.is-size-7")
footer.innerHTML="Powered by 你的名字"
footer.style.visibility="visible"
avatar.src="你的方形logo地址"
avatar.style.visibility="visible"
}
</script>
hotaru 主题更改背景图片示例

<style>
.hotaru-cover {
    background: url(https://s3.ax1x.com/2020/12/08/DzHv6A.jpg) center;
}
</style>
