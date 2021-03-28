<html>
	<head>
		<meta charset="utf-8" />
		<title></title>
		<script src="js/jquery-3.3.1.min.js" type="text/javascript" charset="utf-8"></script>
		<script type="text/javascript">
			$(function(){
				$("a[href='#']").click(function(){
					var flag=$("ul li:gt(0)").is(":visible");
					if (flag) {
						$("ul li:gt(0)").css("display","none");
						$(this).text("(展开)");
					} else{
						$("ul li:gt(0)").css("display","list-item");
						$(this).text("(收起)");
					}
				});
			});
		</script>
	</head>
	<body>
		<h3>笔记<a href="#">(收起)</a></h3>
		<ul>
			<li>C#</li>
			<li>袁宇欣</li>
			<li>刘宇</li>
			<li>熊辉</li>
			<li>时空终点</li>
			<li>前任3：再见前任</li>
			<li>冰雪奇缘</li>
			<li>极品飞车</li>
		</ul>
	</body>
</html>
