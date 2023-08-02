---
layout: page
title: Credit Bureau
permalink: /credit-bureau/
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

On this page you can see a list of all users who took at least one loan. The system doesn’t store any personal data.

![alt_text](images/b7.png)

#### Admins

This page contains a list of registed admin users.

![alt_text](images/b8.png)

Table contains personal data (first name, last name, email) and data of registration.

#### Dumps

This page can be used to create/dowload database of the whole biometric bureau service.

Click "Run Dump" button to schedulee a new dump. Wait unti it will appear in the table and click downloadn to get json
dump of the db.

![alt_text](images/b9.png)

#### Offers

This page contains a list of all offers with the ability to add, modify or delete them.

![alt_text](images/b10.png)

To create a new offer click on the “New offer” button and fill necessary information in the dialog below (name, amount
in $, days to return). All fields are required.

![alt_text](images/b11.png)

After click “Submit” a new record will be created in database and a new row will appear in the table.

Update offer dialog has same components as the “Create offer” dialog so you can modify all existing fields.

![alt_text](images/b12.png)

When you click “Delete” button you will be prompted to confirm this action and after click “Yes” the record will be
deleted from database.

![alt_text](images/b13.png)

#### Applications

This page is for reviewing incoming loan request applications to either confirm or deny them.

![alt_text](images/b14.png)

When click on “Confirm” button you will be prompted to review user personal data and take his biometrics from camera on
your pc to verify user.

![alt_text](images/b15.png)

When the camera is initialized on your computer click “Take biometrics” button to take a snapshot and then “Submit”
button to approve application.

![alt_text](images/b16.png)

If something is incorrect in the provided data click on the “Deny” button to open dialog and submit a reason for denying
to the user.

#### Loans

This page contains a table with all loans and buttons for managing them.

![alt_text](images/b17.png)

If a user wants to extend his existing loan click on the “Update” button and fill new amount and date to return.

![alt_text](images/b18.png)

After click “Submit” loan will be updated in the database.

To close loan simply click on the “Close” button and confirm operation.

![alt_text](images/b19.png)


