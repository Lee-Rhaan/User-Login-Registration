## 🚥 User-Login-Registration

|Java|Spring Boot|MySQL|PostMan|Maven|
|---|---|---|---|---|

|Spring Security|Java Mail|Email Verification with Expiry|Encryption|
|---|---|---|---|

### ⚖️ Overview:

> This is a hobby project to get exposure on working with Spring Security.
- A user signs up with his/her details (they could either be a normal user or an admin).
- They then get emailed a token which should be verified before it expires (expires in 15 minutes).
- Their account stays disabled untill the token is verified.
- Everything is being tracked in the database:
> When the token was issued, the status of the token & user, when the token expires etc.

- I've used BCrypt to encrypt the user's passwords.
- I have exceptions in place for stopping users from registering with emails/tokens that already exists in the database.
