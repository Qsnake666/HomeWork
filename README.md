<html>
<head>
<meta charset="UTF-8">
<title>清泽心雨招新</title>
<style type="text/css">
h1{
font-size:50px;
color:blue;
text-align:center;
}
h2{
font-size:20px;
color:black;
text-align:center;
}
h3{
font-size:20px;
color:brown;
text-align:center;
}
</style>
</head>
<body>
<h1>欢迎来到清泽心雨</h1>
<br>
<h2><strong>报名填写资料</strong></h2>
<br>
<h3>基本信息</h3><br><br>
<style>

.abc{
width:30% ; margin : 0 auto;/*加个宽720px 边界1px的框width:720px;border:1px 线粗solid固体框;margin:0 auto ;width:720px;border:1px solid;text-align:left;*/ 
}
</style>
<div class="abc">
<form method = "post" action = "save.php">
<p>
<label>姓名：</label>
<input type = "text" name = "name" value = "real name">
</p>
<p>
<label>性别：</label>
<label>男</label>
<input type ="radio" value="1" name ="ppp"/>
<label>女</label>
<input type ="radio" value="2" name ="ppp"/>
</p>
<p>请问您有什么爱好：
<input type = "checkbox" name=sv value = 跑步>跑步
<input type = "checkbox" name=sv1 value = 游泳>游泳
<input type = "checkbox" name=sv value = 打游戏>打游戏
<input type = "checkbox" name=sv value = 电脑技术>电脑技术
</p>
<p>
<label>请问您有意于什么部门：</label>
<select >
<option value = "请选择"  selected = "selected">请选择</option>
<option value = "网络安全">网络安全</option>
<option value = "清泽微视">清泽微视</option>
</select>
</p>
</div>
<h2>
<input type = "submit" name = "submit" value = "submit">
<input type = "reset" name = "reset" value = "reset">
</h2>
</form>
</body>
</html>
</html>
