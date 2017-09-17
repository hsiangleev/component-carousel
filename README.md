# component-carousel
### 轮播图
[链接](https://hsiangleev.github.io/component-carousel/carousel.html)

* 说明：
* 需要在模板外添加父盒子，轮播图宽高与父盒子相等
* 引入文件后调用函数: Carousel();
* ie8报错；ie9兼容性不高
* 
* html模板:
``` javascript
<div id="c-carousel">
	<ul id="c-imgContent">
		<li><a href="javascript:;"><img src="" alt=""></a></li>
		<li><a href="javascript:;"><img src="" alt=""></a></li>
		<li><a href="javascript:;"><img src="" alt=""></a></li>
		<li><a href="javascript:;"><img src="" alt=""></a></li>
		<li><a href="javascript:;"><img src="" alt=""></a></li>
	</ul>
	<ul id="c-iconContent">
		<li class="active"></li>
		<li></li>
		<li></li>
		<li></li>
		<li></li>
	</ul>
	<div id="c-left">&lt;</div>
	<div id="c-right">&gt;</div>
</div>
```
