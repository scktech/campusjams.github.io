# Table of Contents

* [About UH Stego](#about-uh-stego)
* [Development history](#development-history)
 * [Milestone 1: Mockup and deployment](https://github.com/scktech/Stego/projects/1)
 * [Milestone 2: Site function implementation](https://github.com/scktech/Stego/projects/2)
* [Features](#features)

# About UH Stego 

UH students commonly send text messages to communicate, but sometimes SMS or instant chat is not secure enough. Truly sensitive data should be transported or hidden to ensure that it is not left exposed to nosey third parties.

Our application allows students hide sensitive text messages or images steganographically. These doctored images can be used a transport media to deliver messages without raising any suspicion or attracting unwanted attention. Once in the hands of the proper recipient, the hidden message can be extracted.

# Features
* Create a profile to send and receive messages.
* Find other users to send private messages.
* Encrypt a message using steganography.
* Decrypt an encrypted message that used steganography.

# Login Page

Users are greeted at the landing page with only a login button.  Since UH Stego deals with sensitive information, outsiders should not be able to understand the purpose of the application.  Anyone with a UH account can login to UH Stego.  Upon clicking the login button, the UH CAS authentication screen will appear and request for your UH username and password.

![](images/login.png)

# Landing Page

Once logged in, users are greeted with information about UH Stego and a top menu filled with options.

![](images/landing.png)

# Profile Page
Users can create profiles to send and receive messages, and include a little bit of information about themselves.

![](images/profile.png)

# Encrypt Page
To encrypt a message, users fill out the text box above and can select from four different images.   A steganographic image is then generated.

![](images/encrypt.png)

# Decrypt Page
To decrypt a message, users can place the URL of their encrypted image and have it decrypted.  The decrypted message will appear in the box below.

![](images/decrypt.png)

# Find User Page
Users can find other users to communicate with.

![](images/finduser1.png)

They can specify the user they would like to contact by entering their UH username.

![](images/finduser2.png)
