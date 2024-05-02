# cloudprojectsAWS
This will house all my beginner cloud computing and cloud security projects on AWS

Best Practices of the 2nd Project on IAM

1. Do not use your AWS root account, instead, create an IAM user and attach policies to it to facilitate your daily activities on the AWS Console.

2. Always download the .csv file of an IAM user before closing the user creation interface. This file contains his/her username, password (not shown), access key and unique
link for that specific user to log in.

3. Create groups and attach policies to it if you have numerous IAM users who have same access levels. This always all users under the group inherit set permissions instead
of attaching permissions to users individually.

4. Take a screenshot of the QR code for the MFA and store it in a safe place; this is incase you forget your password or delete the authenticator application as you will not
be able to access the IAM account without it.

Project 3 ( Hosting a static website on Amazon S3)
In this project, I unchecked the 'block all public access' option so as to allow public access. However in a real world scenario, NEVER uncheck it unless you have access controls in check.

Before adding the bucket access policy, you will notice a 403 error when you try to access the website. This is because I had unchecked the block all public access option that led us to use bycket policy to enable public access.

Project 4 ( S3 bucket versioning)

1. This is a small sample project showing how S3 bucket versioning works. 

If you want to access the uploaded document on the AWS Console, click on it and head to Object URL. Edit permissions to unblock all public access and click
on actions to make it public. Access to the URL will be enabled.
