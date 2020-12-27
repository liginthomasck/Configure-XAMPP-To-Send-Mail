# Configure-XAMPP-To-Send-Mail
Configure XAMPP to send Mail from Localhost in PHP.

### NOTE: Currently rewritting the code.
Hereby The Login Page Designed In A Manner Particulary For The Dependencies Of The Modern Android, IOS, Windows, MacOs, KaiOs, Electron and Web Applications.

First, go to the XAMPP installation directory and open the XAMPP folder and follow the below steps same:

1. Go to the (C:\xampp\php) and open the php.ini file then find the mail function by scrolling down or simply press ctrl+f to search directly then find the following lines of the source code given in https://github.com/CiyaKhan/Configure-XAMPP-To-Send-Mail/blob/main/php.ini and pass those values.
That's all for this file, save the file by pressing ctrl+s and close.

2. Now, go the (C:\xampp\sendmail) and open the sendmail.ini  then find sendmail by scrolling down or press ctrl+f to search directly then find the following lines of the source code given in https://github.com/CiyaKhan/Configure-XAMPP-To-Send-Mail/blob/main/sendmail.ini and pass those values.
That's all for this file, save the file by pressing ctrl+s and close.

3. Now, you're done with the required changes in these files. To send mail using Gmail paste the following codes given in https://github.com/CiyaKhan/Configure-XAMPP-To-Send-Mail/blob/main/configure.php into your PHP file.

##### Important note: If your mail isn't sent and you got a warning or error. Please configure your google account security as "Less secure apps". To configure it:
- Go to your Google account then click on the Security tab and scroll down, there you can see the Less secure app access panel, Simply turn on that. This panel only shows if you haven't enabled 2-Step Verification.
- If you're getting an error as a password is wrong then simply go to the sendmail.ini file and put the correct password of your that Gmail account which you've provided in sendmail_from.

## Key Feature
The Modern Applications User Interface Is Fully Deployed To Developed The Login Page.

###### Developers Support : Zanck Pvt.Ltd.
_developers support@ ciyakhan515@gmail.com_
