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

## Executing request in postman

---

paste pic here

---

## 📧 Default MailDev Dashboard

---

![Screenshot (20)](https://user-images.githubusercontent.com/81378094/137305372-2abf8355-2df2-449c-8d79-a8a3167ed642.png)

---

## ❎ User Should Verify Account

---

![Screenshot (21)](https://user-images.githubusercontent.com/81378094/137305997-717f60ea-7aa1-4b1e-a055-d0ff2a3a4dd7.png)

---

## ✔️ Account Confirmed

---

![Screenshot (22)](https://user-images.githubusercontent.com/81378094/137306421-f3d0f6b7-7595-4344-a4c3-bf1302da41a0.png)

---

