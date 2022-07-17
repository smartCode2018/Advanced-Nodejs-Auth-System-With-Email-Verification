# Advanced-Nodejs-Auth-System-With-Email-Verification

This is an advance Node.js Auth Application with Complete Register, Login and Passowrd Rest functionalities.

Covers Email sainding with nodemailer.

---- To istall ----

Rename config.env.example to config.env and fill in your credentials and mongodb Url

Run "yarn" to install packages, then run "yarn server" to start your backend.

API ENPOINTS & SAMPLE
\*Register
http://localhost:5000/api/auth/register
{
"username": "your user name",
"email":"Your Email",
"password":"your password"
}

\*Login
http://localhost:5000/api/auth/login
{
"email":"Your Email",
"password":"your password"
}

\*Forgot Password
http://localhost:5000/api/auth/forgotpassword
{
"email":"Your Email",
}

http://localhost:5000/api/auth/resetpassword/enter_reset_password_token_sent_to_your_email
{
"password":"Your new password",
}

For futher refrences you can import the REACT_AUTH.postman_collection file to your postman to see my examples.

HAPPY CODING - smartcode.kc
Contact: smartcode.kc@gmail.com
