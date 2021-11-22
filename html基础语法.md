## 我的第一个html

<!--这是注释-->
<html>
<!--头-->
	<head>
		<title>
		<!--标题-->
		my first html
		</title>
	</head>
	<!--网页体显示在网页上-->
	<body>
	这是我的html
	</body>
</html>

## 基本标签

<html>
<body>

<p>这是一个段落，多大事大赛大赛DSADSPadsAASDASD</p>
<p>第二个段落</p>
<h1>标题字</h1>
<h2>二级标题字</h2>
<h3>三级标题字</h3>

<!--换行标记-->
hello <br>world  <!--独目标记-->

页面显示：
hello
world
<!--水平线,color是属性，指定颜色值可以使用单引号双引号不用引号且不区分大小写-->

<hr color="red">
<!--预留格式,否则在网页上面是一排输出-->
<pre>
for(int i=0;i<100;i++){
System.out.println("i = "+i);
}


<b>粗体字</b>
<i>斜体字</i>
<ins>插入字</ins>
<del>删除字</del>
10<sup>2</sup>
m<sub>2</sub>

<font color="red" size="12">hello world</font>
<!--空格-->
a bc
a&nbsp;bc
<!--小于号-->
b<a>c
b&lt;a&gt;c
<!--表格分成3部分，thead，tbody，tfoot-->
<!--border设置边框宽度，1px表示1像素,50%表示浏览器显示百分比-->

<table border="1px" wdth="300px" height="200px" align="center">
<thead>
	<tr>
		<td>1</td>
		<td>2</td>
		<td>3</td>
	</tr>
</thead>
<tbody>
	<tr>
		<td>1</td>
		<td>2</td>
		<td>3</td>
	</tr>
</tbody>
<tfoot>
	<tr>
		<td>1</td>
		<td>2</td>
		<td>3</td>
	</tr>
</tfoot>
</table>

<!--表格单元格合并-->

<table border="1px" wdth="300px" height="200px" align="center">
	<tr>
		<td>1</td>
		<!--colspan表示列合并-->
		<td colspan="2">xy</td>
		<!--<td>y</td>-->
	</tr>
	<tr>
		<td>1</td>
		<td>2</td>
		<!--rowspan表示行合并-->
		<td rowspan="2">king</td>
	</tr>
	<tr>
		<td>1</td>
		<td>2</td>
		<!--<td>fute</td>-->
	</tr>


	<!--th可以代替td，表示自动加粗并居中-->

</table>


</body>
</html>
