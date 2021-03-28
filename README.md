
<html>
	<head>
		<meta charset="utf-8">
		<title></title>
		<script src="js/jquery-3.3.1.min.js" type="text/javascript" charset="utf-8"></script>
		<script type="text/javascript">
			$(function(){
				$(":input").click(function(){
					$(":header").css("color","red");
					$(":header+ul").css("list-style","url(img/list.gif)");
					$(":header+ul>li>ul").css("list-style","url(img/list_icon.gif)");
				});
			});
		</script>
	</head>
	<body>
		<h2>Web前端技术</h2>
		<ul>
			<li>使用DIv+Css设计前端页面
			<ul>
				<li>页面布局</li>
				<li>美化页面</li>
				<li>页面特效</li>
			  </ul>
			</li>
			
			<li>使用JavaScript+jQuery设计页面特效
			<ul>
				<li>JavaScript基础</li>
				<li>jQuery选择器</li>
				<li>jQuery操作Dom</li>
			  </ul>
			</li>
		</ul>
		<p><input type="button"  value="改变样式" /></p>
	</body>
</html>
