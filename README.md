# OTP-Verification-System
Python Project
Medium Link : 
## STEPS to generate APP PasswordCancel changes
1. Go to your Google Account.
2. Select Security.
3. Under "Signing in to Google," select App Passwords.
4. If you don't have App Password option, it might be because:
    ● 2-Step Verification is not set up for your account.
    ● 2-Step Verification is only set up for security keys.
    ● Your account is through work, school, or other organization.
    ● You turned on Advanced Protection.
5. At the bottom, choose >Select app and choose the app you using and then >Select device and choose the device you're using and then Generate.
6. Follow the instructions to enter the App Password. The App Password is the 16-character code in the yellow bar on your device.
7. Tap Done.


### Python already has a library that lets you connect to an SMTP server, like the one Gmail uses. This library is called, predictably, smtplib and comes included with Python.

### starttls() is an email protocol command that tells an email server that an email client, including an email client running in a web browser, wants to turn an existing insecure connection into a secure one.

### Using smtplib library, there are a few different ways you can create a connection to your mail server. Here we'll focus on creating a plain, insecure connection (which should rarely, if ever, be used). This connection is unencrypted and defaults to port 25. However, the protocol for mail submission actually uses 587, which is what we'll use.

SMTP (Simple Mail Transfer Protocol) is an application-level protocol (on top of TCP) used to communicate with mail servers from external services, like an email client on your phone. SMTP is a delivery protocol only, so you can't actually retrieve email with it, you can only send an email, which is what we'll be focusing on in this article. If you want to retrieve email instead, then you'll want to check out the IMAP (Internet Message Access Protocol) protocol. We should note that many email services, like Gmail, don't usually use SMTP on their internal mail servers. SMTP is usually just provided as an outward-facing interface to their service via the smtp.gmail.com server. This is mostly meant to be used by email clients on your phone or computer (like Outlook, Thunderbird, etc).

#### For more info visit : https://docs.python.org/3/library/smtplib.html
