# -TEST
实现一个三列布局，其中左侧和右侧的部分宽度固定，中间部分宽度随浏览器宽度的变化而自适应变化
<!DOCTYPE html>
<html>
<head>
<title>rool -jiao</title>
<meta http-equiv="Content-Type" content="text/html" charset="utf-8">
<style>

.box1{
	width:150px;
	height:100px;
	float:left;
	background-color: red;
}
.box2{
	float:right;
	width:200px;
	height:100px;
	background-color: blue;

}
.box3{
	background-color: #000;
	height:100px;
}
</style>
</head>
<body>

<div class="box1"></div>
<div class="box2"></div>
<div class="box3"></div>


</body>
</html>
