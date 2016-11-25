<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
</head>
<body>
<h1>学生信息登记表</h1>>
   <form action="1.php"  method="post" >
    用户名：<input type="text" maxlength="6" name="usernale"  value="123123"><br><hr>
    密码：<input type="password" name="pwd"><br><hr>
<!-- 单选按钮 -->
性别：<input type="radio" name="gender" checked="checked">男 ><input type="radio" name ="gender">女
    <br>
    生日：<input type="date" name="dd">
   <!-- <input type="submit"> -->
     <br>
爱好：<input type="checkbox">打酱油 <input type="checkbox">熬夜 <input type="checkbox"> 写代码
     <br>
     专业：
     <select>
  <option value ="软件">软件</option>
  <option value ="硬件">硬件</option>
  <option value="android">android</option>
  <option value="ios">Audi</option>
</select>
     <br>
<input type="submit">

       </form>
  </body>

</html>
