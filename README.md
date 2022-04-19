# chormeUi-media
一个简单多屏适配
<head>
		<title>鱼哥哥</title>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width,initial-scale=1,user-scalable=no" />
		<link rel="stylesheet" type="text/css" href="font/iconfont.css"/>
		<link rel="stylesheet" href="css/reset.css" type="text/css"/>
		<link rel="stylesheet" href="css/common.css" type="text/css"/>
		<link rel="stylesheet" href="css/ipad.css" type="text/css" media="(min-width:768px)"/>
		<link rel="stylesheet" href="css/pc.css" type="text/css" media="(min-width:1000px)"/>
		<link rel="stylesheet" href="css/pc-w.css"  media="(min-width:1200px)"/>
	</head>
	<!--
	总结：1、浮动块套一个div，大分辨率下，直接浮动div
		  2、解决间隙的办法：百分比布局，文字左，右对齐	
			3、box-sizing：border-box不计较边框和边距
			4、子级display-inline-block，父级text-align：center
	调试：1、各个浏览器兼容情况，排除法：逐个内容块删除排查
