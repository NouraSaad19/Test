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

*4.2)Confirm a mobile verification:*
|Method|verifyOTP()|
|---|---|
**Request parmeters:**
|Parmeter name|Type|
|otp|String|

**5)Resend OTP:**
|Method|resendOTP()|
|---|---|
**Request parmeters:**
|Parmeter name|Type|
|phone|String|

**6)Sign in by google:**
|Method|loginUsingGoogle()|
|---|---|
**Request parmeters:**
|Parmeter name|Type|
|_|_|



**7)Sign out:**
|Method|signOut()|
|---|---|
**Request parmeters:**
|Parmeter name|Type|
|_|_|

**8)Change password:**
|Method|changePassword()|
|---|---|
**Request parmeters:**
|Parmeter name|Type|
|oldPassword|String|
|newPassword|String|


**9)Get the current user name:**
|Method|getNameField()|
|---|---|
**Request parmeters:**
|Parmeter name|Type|
|_|_|


**10)Get the current user image:**
|Method|getImageField()|
|---|---|
**Request parmeters:**
|Parmeter name|Type|
|_|_|


**11)Update user name in profile:**
|Method|updateName()|
|---|---|
**Request parmeters:**
|Parmeter name|Type|
|updateName|String|



**12)Update user image in profile:**

*12.1)Take photo from gallery:*
|Method|TakePhoto()|
|---|---|
**Request parmeters:**
|Parmeter name|Type|
|Course|ImageSource|

*12.2Update image in profile:*
|Method|updateImageProfile()|
|---|---|
**Request parmeters:**
|Parmeter name|Type|
|_|_|
