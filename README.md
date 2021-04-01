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
			<li>①添加确定按钮：
private void 取消按钮的click属性
{
            string name = this.控件名.Text;
            string tel = this.控件名.Text;
            string no = this.控件名.Text;
            string sex = this.控件名.Checked ? "男 " : "女";
            string address = this.控件名.Text;
            string sql = string.Format("insert into CustomersTb1(custName,custTel,custNO,custSex,Address) values('{0}',{1},{2},'{3}','{4}');",name,tel,no,sex,address,id);
            bool result = DBHelper.ExecuteNonQuery(sql);
            if (result)
            {
                MessageBox.Show("添加成功！");
            }
            else
            {
                MessageBox.Show("添加失败！");
            }
} 

②取消按钮（清空控件内容）：
privat void clear（）
{
string （控件名）=“（空）”；
string （控件名）=“（空）”；
string （控件名）=“（空）”；
string （控件名）=“（空）”；
}
private void 取消按钮的click属性
{
clear（）；
}

③dgv显示数据：
string sql = string.format（select * from 表名）；
this.dataGridView1.DataSource = DBhelper.Enq(sql);

④查询按钮：
string 命名 = this.控件名.Text
stri</li>
		</ul>
	</body>
</html>
