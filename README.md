# taobaoindex
#简介：
这是淘宝首屏静态页面，通过html+css实现淘宝页面首屏布局与样式，不涉及js代码。html部分采用h5,css部分使用css3。
#布局实现：
首先将页面首屏分为四个大部分，顶部导航条，搜索部分，中间导航条以及内容展示区域。从上至下，从左至右，由外及内逐步细化实现各个部分布局与样式。
#知识点：
1.布局不受窗口大小变化影响-->选中html+body，对顶层盒子进行overflow-x:hidden处理。
2.div居中处理--> margin：0 auto
3.单行文本水平居中--> text-align：center line-height为当前文本所在容器的高度
4.浮动--> float
5.a标签不会继承父级设置的color等文字属性
6.背景图片截取部分：background：url('url') scroll x y;
