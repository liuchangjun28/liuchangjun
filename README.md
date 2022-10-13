<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
	</head>
	<body>
		<table border="1">
			
		<tr>
		<th>
			信息统计表
		</th>
		    </tr>
		<tr>
			<td>姓名：<input typu="trxt" name="userName"></td>
        </tr>
		<tr>
			<td>年龄：<input type="text" name="userName"></td>
		</tr>
		<tr>
			<td>性别：<input type="radio" name="sex" value="1">
			          <input type="radio" name="sex" value="0">
			</td>
		</tr>
	         <td>爱好：<input type="checkbox" name="hobby" value="1">钓鱼<br>
			          <input type="checkbox" name="hobby" value="2">钢琴<br>
			          <input type="checkbox" name="hobby" value="3">篮球<br>
					  <input type="checkbox" name="hobby" value="4">游泳<br>
					  <input type="checkbox" name="hobby" value="5">健身
			 </td>
		</tr>
		<tr>
			<td>学历:
			<select name="degree">    
			    <option value="">--请选择--</option>
				<option value="1">专科</option>    
				<option value="2">本科</option>    
				<option value="3">硕士</option>    
				<option value="4">博士及以上</option></select>
			</select>
		</td>
	</tr>
		<td>自我介绍
		<textarea name="troduct"rows="10"cols="30"></textarea>
		</td>
	</tr>
	    <td>
			<input type="submit" value="提交">
			<input type="reset" value="重置">
			<input type="button" value="返回">
		</td>
	</tr>	
	</table>
</body>
