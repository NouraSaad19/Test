**Authentication Function Documentation**  
 

This document describes how you can use the functions in the authentication template…  


**1)User sign up by email & password:**
|Method|signUpUsingFirebase()|
|---|---|
**Request parmeters:**
|Parmeter name|Type|
|userModel|UserModel|

**2)User sign in by email & password:**
|Method|loginUsingFirebase()|
|---|---|
**Request parmeters:**
|Parmeter name|Type|
|email|String|
|password|String|



**3)Reset password by email:**
|Method|resetPassword()|
|---|---|
**Request parmeters:**
|Parmeter name|Type|
|email|String|



**4)Sign in by phone number:**
*4.1)Request a mobile  verification:*
|Method|verifyPhone()|
|---|---|
**Request parmeters:**
|Parmeter name|Type|
|phone|String|
