## 🚥 User-Login-Registration API

|Java|Spring Boot|MySQL|Postman|Maven|
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

![Screenshot (23)](https://user-images.githubusercontent.com/81378094/137320164-89337736-7b52-4ea2-ba45-6a66270b00d7.png)

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

## If the account is confirmed, the User can Sign-in without triggering any exceptions

---

![Screenshot (24)](https://user-images.githubusercontent.com/81378094/137320602-58dd3818-cda9-4daf-8ced-065178435b39.png)

---

## The landing page after user signed in
> Have not created any endpoints to receive signed-in user

---

![Screenshot (25)](https://user-images.githubusercontent.com/81378094/137320948-782aace0-08f4-4985-b79f-0b6b141a149f.png)

---

## If a user tries confirming verification if account is already verified
> They receive an exception

---

![Screenshot (27)](https://user-images.githubusercontent.com/81378094/137321356-0276ed25-381f-4e8b-8ba9-9718474ee45e.png)

---

## Here's what I track in the database tables

---

![Screenshot (26)](https://user-images.githubusercontent.com/81378094/137321668-1dc36165-64a5-480a-bf36-fd80cc2a705c.png)

---
