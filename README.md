<!DOCTYPE html>
	<html>
		<head>
			<title>review</title>
		</head>
		<body>
					<fieldset>
					<legend>Your details</legend>
						<form  action="http://www.example.org/login.php">		  
							<p>username:
					 		<input type="text" name="name"size="15" maxlength="30" required="required"/></p>
						<p> Password:
						 <input type="password" name="userspassword" size="15" maxlength"30" required="required"/>
						</form>
					</fieldset>
					<fieldset>
					<legend>Your Review</legend>
						<table> 
							<tr>
								<td>
									<form action="http//www.example.com/review/how.php">
										<p>How did you  hear about us?</p>
									<select name="ways of hearing about us" size="3" multiple="multiple">
									<option value="friend">friend</option>
									<option value="Google"selected="selected">Google</option>
									<option value="facebook">Facebook</option>
									<option value="youtube">Youtube</option>
									<option value="bing">Bing</option>
										</form>
								</td>
								<td>
									<form acton="http//www.example.com/review/r8.php">
									 <p> Rate us 1/5: 
									 </br>
									<input type="radio" name="rating" value="1" /><img src="https://lh4.ggpht.com/m87ygjwDXCfESDi8gVJw0Jyu3Xn-rCzLPycfehfvVm3iM9dnFUL1Enit59zeddUMPg=w300" height="10"width="10"/>
											<input type="radio" name="rating" value="2"/><img src="https://lh4.ggpht.com/m87ygjwDXCfESDi8gVJw0Jyu3Xn-rCzLPycfehfvVm3iM9dnFUL1Enit59zeddUMPg=w300" height="10"width="10"/><img src="https://lh4.ggpht.com/m87ygjwDXCfESDi8gVJw0Jyu3Xn-rCzLPycfehfvVm3iM9dnFUL1Enit59zeddUMPg=w300" height="10"width="10"/>
											<input type="radio" name="rating" value="3"/><img src="https://lh4.ggpht.com/m87ygjwDXCfESDi8gVJw0Jyu3Xn-rCzLPycfehfvVm3iM9dnFUL1Enit59zeddUMPg=w300" height="10"width="10"/><img src="https://lh4.ggpht.com/m87ygjwDXCfESDi8gVJw0Jyu3Xn-rCzLPycfehfvVm3iM9dnFUL1Enit59zeddUMPg=w300" height="10"width="10"/><img src="https://lh4.ggpht.com/m87ygjwDXCfESDi8gVJw0Jyu3Xn-rCzLPycfehfvVm3iM9dnFUL1Enit59zeddUMPg=w300" height="10"width="10"/>
											<input type="radio"name="rating"value="4"/><img src="https://lh4.ggpht.com/m87ygjwDXCfESDi8gVJw0Jyu3Xn-rCzLPycfehfvVm3iM9dnFUL1Enit59zeddUMPg=w300" height="10"width="10"/><img src="https://lh4.ggpht.com/m87ygjwDXCfESDi8gVJw0Jyu3Xn-rCzLPycfehfvVm3iM9dnFUL1Enit59zeddUMPg=w300" height="10"width="10"/><img src="https://lh4.ggpht.com/m87ygjwDXCfESDi8gVJw0Jyu3Xn-rCzLPycfehfvVm3iM9dnFUL1Enit59zeddUMPg=w300" height="10"width="10"/><img src="https://lh4.ggpht.com/m87ygjwDXCfESDi8gVJw0Jyu3Xn-rCzLPycfehfvVm3iM9dnFUL1Enit59zeddUMPg=w300" height="10"width="10"/>
											<input type="radio" name="rating"value="5"/><img src="https://lh4.ggpht.com/m87ygjwDXCfESDi8gVJw0Jyu3Xn-rCzLPycfehfvVm3iM9dnFUL1Enit59zeddUMPg=w300" height="10"width="10"/><img src="https://lh4.ggpht.com/m87ygjwDXCfESDi8gVJw0Jyu3Xn-rCzLPycfehfvVm3iM9dnFUL1Enit59zeddUMPg=w300" height="10"width="10"/><img src="https://lh4.ggpht.com/m87ygjwDXCfESDi8gVJw0Jyu3Xn-rCzLPycfehfvVm3iM9dnFUL1Enit59zeddUMPg=w300" height="10"width="10"/><img src="https://lh4.ggpht.com/m87ygjwDXCfESDi8gVJw0Jyu3Xn-rCzLPycfehfvVm3iM9dnFUL1Enit59zeddUMPg=w300" height="10"width="10"/><img src="https://lh4.ggpht.com/m87ygjwDXCfESDi8gVJw0Jyu3Xn-rCzLPycfehfvVm3iM9dnFUL1Enit59zeddUMPg=w300" height="10"width="10"/>
									</p>
									</td>
							</tr>
			      			</form>
						</table>
			<form action="http://www.example.com/review/comment.php">
				<p>Comments:</p>
				<textarea name="users comment">Enter your comments</textarea>
				</form>
					</fieldset>
			<form action="http://www.example.com/review/submit.php">
			<input type="submit" name="review"Value="submit review"/>
			</form>

		</body>
	</html>
