**Authentication Function Documentation**  
 

This document describes how you can use the functions in the authentication template…  

**1)Sign up by email & password**



|**User sign up by email & password:**|
| - |
|Method|<p>() </p><p>signUpUsingFirebase</p>|
|**Request parmeters:**|
|Parmeter name|Type|
|userModel|UserModel|



**2)Sign in by email & password**
|**User sign in by email & password:**|
| - |
|Method|loginUsingFirebase()|
|**Request parmeters:**|
|Parmeter name |Type|
|email|String|
|password|String|


**3)Reset password by email** 
|**User reset password by email:**|
| - |
|Method|resetPassword()|
|**Request parmeters:**|
|Parmeter name |Type|
|email|String|



**4)sign in by phone number** 
1) **Request a mobile verification :**
|**Request a mobile verification :**|
| - |
|Method|verifyPhone()|
|**Request parmeters:**|
|Parmeter name |Type|
|phone|String|



2) **Confirm a mobile verification :**
|**Confirm a mobile verification :**|
| - |
|Method|verifyOTP()|
|**Request parmeters:**|
|Parmeter name |Type|
|otp|String|



**5)Resend OTP**
|**Resend OTP :**|
| - |
|Method|resendOTP()|
|**Request parmeters:**|
|Parmeter name |Type|
|phone|String|


**6)Sign in by google** 
|**User sign in by google :**|
| - |
|Method|loginUsingGoogle()|
|**Request parmeters:**|
|Parmeter name |Type|
|||


**7)Sign out** 
**User sign out:![](Aspose.Words.e89b8954-97ed-4540-be2c-41a01fec5393.001.png)**
|Method|signOut()|
| - | - |
|**Request parmeters:**|
|Parmeter name |Type|
|||



**8)Change password** 
|**User change password:**|
| - |
|Method|changePassword()|
|**Request parmeters:**|
|Parmeter name |Type|
|oldPassword|String|
|newPassword|String|



**9)Get the current user name** 
|**Get user name:**|
| - |
|Method|getNameField()|
|**Request parmeters:**|
|Parmeter name |Type|
|||



**10)Get the current user image** 
|**Get user image:**|
| - |
|Method|getImageField()|
|**Request parmeters:**|
|Parmeter name |Type|
|||



**11) Update user name in profile** 
|**Update user name in profile :**|
| - |
|Method|updateName()|
|**Request parmeters:**|
|Parmeter name |Type|
|updateName|String|
**12)Update user image in profile**  

1) **Take Photo from gallery** 
|**Update user image in profile :**|
| - |
|Method|TakePhoto()|
|**Request parmeters:**|
|Parmeter name |Type|
|Course |ImageSource |


2) **Update image in profile** 
|**Update user image in profile :**|
| - |
|Method|updateImageProfile()|
|**Request parmeters:**|
|Parmeter name |Type|
|||

