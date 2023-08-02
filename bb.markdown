---
layout: page
title: Biometric Bureau
permalink: /biometric-bureau/
---

### Description:

Component of the system to creating/store and manage biometric credentials.

### Documentation:

![alt_text](images/b1.png)

#### Registration

To register in the system click on “Register Now” button to go to register page.

![alt_text](images/b2.png)

Here you have to provide your personal data (first name, last name, email, password). After that click "Create Account"
to submit registration info. All fields are required.

![alt_text](images/b3.png)

Now you are registered in the system and can login from home page.

#### Restore credentials

If you forgot you password click “Forgot password link” to go to restore password page.

![alt_text](images/b4.png)

On the page provide your email you have used to register in the system and click “Submit” to send the data.

![alt_text](images/b5.png)

If you are in the database you will receive a link to your email after opening which you will be prompted to provide a
new password. After submitting new credentials you will be able to login to the system.

#### Login

Go to home page, provide your credentials (email and password) and click "Login". If the data is correct you will be
redirected to dashboard.

![alt_text](images/b6.png)

#### Use web service

#### Users

On the users page you will se a list of users who registered in the mobile application and requrested biometric
credentials from it.

![alt_text](images/b7.png)

You can naviage throgh the table page by page and if necessary click "Show Biometrics" under the "Actions" column to see
provided biometric data (face).

![alt_text](images/b8.png)

#### Admins

This page contains a list of registed admin users.

![alt_text](images/b9.png)

Table contains personal data (first name, last name, email) and data of registration.

#### Dumps

This page can be used to create/dowload database of the whole biometric bureau service. This possibility is udeful for
integrations with existing IT systems that lending organizations may already have in place.

Click "Run Dump" button to schedule a new dump. Wait unti it will appear in the table and click downloadn to get json
dump of the db.

![alt_text](images/b10.png)
