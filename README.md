# ST10512089_PROG5121_Part-1
Part 1 Repository
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
====JAVA LOGIN====:
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
-Public class is login. 
-Used string method for the username,password and phoneNumber.
-Login user username with the required conditions. 
-Login user password with limited characters of 8.
-Login user phoneNumber with limited length of 12 numbers.
-Used public boolean to check username length and if it has an underscore.
-Used public boolean to check password complexity.
-Boolean method to check for password if it has capital letters,special characters and numbers.
-For loop was implemented for the conditions of the password length,index numbers.
-Used public boolean to check phone number length and start with +27.
-Used public boolean to  check register user in string method of username,phone number,password.
-Used if statement to make all three variables false.
-Used user details to make all three variables return true.
-Used public boolean for login user's with string method for user's username and password.
-If statement with conditions of null username and null password and make it return false.
-Used return this method to both the username and password and make it both  equals to username and password by using brackets in  the end.
-Used public string return login status with the condition of boolean method of success.
-Used if statement with the condition of success and return method with the message of Welcome and it is great to see you with inverted commas and wrote +username+.
-Else if the user's 3 variables is incorrect, the return method will be implemented with  the message of the three variables to be incorrect and ask the user to try again.
------------------------------------------------------------------------------------------------------------------------------------------------------------------
===THE END OF MY LOGIN JAVA CODE===
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
====JAVA MAIN FOR REGISTRATION====
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
-Public class is Main and using public static void main for our starting point for our code.
-Imported the Scanner java class so my code could scan the the user's details.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
---REGISTRATION SECTION---
-Made output for user registration by writing system.out.println for the user username,password and phone number.
-Used boolean method to  call the register user  and  store the message it returns.
-Showing the registration messege by outputing using system.out.println(response);.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
---LOGIN SECTION---
-Making two outputs for the user's username and password by using System.out.println();. 
-Using boolean method for the login user username and password.
-Using string method to make the code print out the logged in message.
-Using output method for the correct login message by using System.out.println(loginMessage);.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
===THE END OF MY JAVA MAIN REGISTRATION===
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
====JAVA LOGINTEST====
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
-Public class is LoginTest.
-Using Logintest to test login java code.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
---TEST---
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
-Using public void  to test valid and invalid  username of the user.
-Using assertTrue for valid username and check for username. 
-Using assertFalse for invalid username if it contains no underscore and if it is too long.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
---TEST---
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
-Using public void  to test valid and invalid password of the user.
-Using assertTrue for valid password and check for password complexity.
-Using assertFalse for invalid password if it contains no capital letters and no numbers.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
---TEST---
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
-Using public void  to test valid and invalid phone number of the user.
-Using assertTrue for valid phone number and check for the phone number with the correct international code of South Africa.
-Using assertFalse for invalid phone number with no international code of South Afica.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
---TEST---
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
-Using public void to test login success and login failed.
-Using login register user valid details on both login success and login failed.
-Using assertTrue for attempt login with the same correct details of the login user
-Using assertFalse for attempt login with the password only of the user.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
====THE END OF JAVA LOGINTEST====
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
