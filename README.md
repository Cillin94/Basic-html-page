Basic-html-page
===============

A small program to use the likes of tables and pictures on a html page.

<!DOCTYPE html>
<html>
	<body>
		<table width="1050" border="0">
		<form method="post" action="showform.php">
		<fieldset>
			<tr>
			<thead><img src="top_nav.jpg"/></thead>
			</tr>
			<tr>
			<td rowspan="2"><img src="my_sky.jpg"></td>
			<td colspan="2"><img src="arrow.gif">Login/Register		<img src="arrow.gif">Print this page?</td>
			</tr>
			<tr>
			<td width="500" height="200" style="vertical-align:top;">
			<label for="username">Username</label>
			<input type="text" id="username" name="username" class="large" placeholder="Enter your username here"/><br>
			<label for="password">Password</label>
			<input type="text" id="password" name="password" class="large"/><br>
			<br>
			<u>Username Help</u>	<u>Password Help</u><br>
			<u>Register Today</u><br>
			<input type="checkbox" name="rememberme" value="rememberme"/>Remember me?
			</td>
			</tr>
			<tr>
			<td rowspan="2">
			<img src="sky_record.jpg">
			<img src="mobile_news.jpg"><br>
			<img src="sky_box.jpg">
			<img src="win_win.jpg">
			</td>
			<td colspan="2" style="vertical-align:top;">
			<img src="arrow.gif">What is Remote Record?<br>
			<img src="arrow.gif">Sky by broadband<br>
			<img src="arrow.gif">Sky by mobile<br>
			<img src="arrow.gif">What's on TV<br>
			<img src="arrow.gif">Contact Us
			</td>
			</tr>
		<fieldset>
		<form>	
		</table>
	</body>
</html>
