# Email-controller
This is our final project in Networking course at HCMUS. This app using email to control the computer from remote. 
## Function
- Screenshot
- Screen recording
- List the process on the computer
- Stop a process
- Shutdown / Restart
- Copy a file
- Capture a keyboard event

## How we done
1. Get email: First we use `imaplib` library in Python to connect our app to mail server. In this app, the mail server address is imap.zoho.com and port is 993. Our app only read the mail which has the keyword from user.
2. Create email: We create a MIMEMultipart object with the argument: receiver, subject, content, and attached file.
3. Send email: Use SMTP protocol to send email to user email address. Again, connect to the mail server of Zoho and then send the mail to the address which send request.
## Our team

|Member|Github|
|------|------|
|Tran Kieu Minh Lam|[@minhlam2102002](https://github.com/minhlam2102002)|
|Nguyen Hoang Lam|[@hoanglam1134](https://github.com/Hoanglam1134)|
|Nguyen Pham Ba Duy||
## Reference
- https://www.geeksforgeeks.org/e-mail-format/?ref=lbp
- https://www.geeksforgeeks.org/multipurpose-internet-mail-extension-mime-protocol/
- https://docs.python.org/3/library/smtplib.html
- https://docs.python.org/3/library/imaplib.html
