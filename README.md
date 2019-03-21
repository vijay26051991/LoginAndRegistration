# Login and Registration using Postgres Authorization in a spring boot and spring security.

This repository will demostrate the login and user registration with spring security.

***
**Requirements:**
 * Java 8
 * Dynamic and static salt.
 * Strong Hashing algorithm.
 * Spring security.
 * JWT.

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
