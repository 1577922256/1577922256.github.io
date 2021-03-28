<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title></title>
		<style type="text/css">
				fieldset{
					width: 260px;
					border: 3px solid yellow;
					}
					fieldset legend{
						font: 15px "微软雅黑" ;
						color: #00FFFF;
						margin-left: 20px;
					}
					#log{
						margin: 10px auto;
						width: 50px;
					}
					form input.txt{
						border: 1px solid #808080;
						width: 120px;
						height: 20px;
						line-height: 20px;
					}
					form fieldset input.btn{
						border: 1px solid #00FFFF;
						height: 25px;
						line-height: 50px;
						width: 40px;
						text-align: center;
		                font: 12px "微软雅黑";
						margin-left: 40px;
					}
					.label{
						text-align: right;
					}
					.submit{
						text-align: center;
					}
		</style>
	</head>
	<body>
		<div id="log">
							<form action="" method="post">
								<fieldset>
									<legend>登录购乐乐网</legend>
									<table>
										<tr>
											<td class="label"><label for="userName" >用户名：</label></td>
											<td><input type="text" id="userName" class="txt" /></td>
										</tr>
										<tr>
											<td class="label"><label for="userPwd" >密码：</label></td>
											<td><input type="password" id="userPwd" class="txt" /></td>
										</tr>
										<tr>
											<td class="label"><label for="userPwd" >确定密码：</label></td>
											<td><input type="password" id="userPwd" class="txt" /></td>
										</tr>
										<tr>
											<td class="label"><label for="userName" >邮箱：</label></td>
											<td><input type="text" id="userName" class="txt" /></td>
										</tr>
										<tr>
											<td colspan="2" class="submit"><input type="submit" class="btn" value="登录" /></td>
										</tr>
										
									</table>
								</fieldset>
							</form>
						</div>
	</body>
</html>
