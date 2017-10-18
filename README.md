# Gemsy Talk: 

##Core:
- Login / logout
- optional return user to requested url on login
- configurable redirect for non-logged-in users
- Password encryption, algorithms: bcrypt (default), MD5, SHA-1, SHA-256, SHA-512, AES or custom.
- Configurable stretches and salt.
- Configurable attribute names for username, password and email.
- Allow multiple fields to serve as username.

## Other Features by Module:
User Activation 
  - activate by email, configurable attribute names, configurable mailer
Reset Password 
  - with email verification, configurable mailer, configurable time between emails
Remember Me 
  - with configurabe expiration, configurable attribute names
Session Timeout
  - configurable session timeout, optionally session timeout will be calculated from last user action
Brute Force Protection
  - brute force login protection, configurable logins before lock & lock duration
Basic HTTP Authenication
  - before action, automatic login, automatic login is disabled if session key changed
Activity Logging
  - automatic logging of last login, last logout, last activity time and IP address for last login
External
  -OAuth1 & OAuth2 support (currently Twitter, Facebook, Github, Google, Heroku, LinkedIn)
  (helps you log in users fromm external auth providers)
 
