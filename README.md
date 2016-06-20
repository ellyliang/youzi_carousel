柚子移动端图片切换

做这个纯粹是为了认识下npm module怎么搞~

这是一个移动端图片切换的功能，因为只是练习，不排除有很多问题。


用法：
```js
var carousel = require('youzi_carousel');

//所有的数据
var list = [{
	img: "http://7xkinp.com1.z0.glb.clouddn.com/1.png"
},
{
	img: "http://7xkinp.com1.z0.glb.clouddn.com/2.png"
},
{
	img: "http://7xkinp.com1.z0.glb.clouddn.com/3.png"
},
{
	img: "http://7xkinp.com1.z0.glb.clouddn.com/4.png"
},
{
	img: "http://7xkinp.com1.z0.glb.clouddn.com/5.png",
},
{
	img: "http://7xkinp.com1.z0.glb.clouddn.com/6.png",
},
{	
	img: "http://7xkinp.com1.z0.glb.clouddn.com/7.png",
},
{	
	img: "http://7xkinp.com1.z0.glb.clouddn.com/8.png",
}
];

new carousel({
	dom: document.getElementById('jCarousel'),  // 传入节点
	data: list                                  // 图片数据列表
});
```


