# Login and Registration using Postgres Authorization in a spring boot and spring security.

This repository will demostrate the login and user registration with spring security.

***
**Requirements:**
 * Java 8
 * Dynamic and static salt.
 * Strong Hashing algorithm.
 * Spring security.
 * JWT.
 * Basic version of Angular JS.

***
User interfaces:
-----------------
There are two forms in the web interface.
    1. Login form.
    2. Registration form.

Implementations:
----------------
•	Leveraging spring security for login page.
•	Authentication - postgresql connectivity using user details service.
•   Authorization - Granted roles for method level security.

***
Enhancements:
---------------------------
 1. Implementing additional feature to send OTP to user email/mobile. 
 2. Implementing additional feature captcha to avoid from abusing web applications from automated scripts, programs and bots.
 3. Implementing additional feature to add secret questions and answers to reset the password.
 4. Adding password policy in future.
 
 ***
 Links for reference:
 ----------------------
 1. [Mitigating rainbow table with salt](https://auth0.com/blog/adding-salt-to-hashing-a-better-way-to-store-passwords/).
 2. [Best way to store the user password in the database](https://stackoverflow.com/questions/1054022/best-way-to-store-password-in-database).
 3. [How to store the password](https://www.geeksforgeeks.org/store-password-database/).
