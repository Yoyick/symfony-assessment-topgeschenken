 Symfony & PHP Logic Assessment - Topgeschenken

This repository contains a technical assessment completed for **Topgeschenken Nederland**. The project demonstrates proficiency in PHP logic, Symfony framework implementation, and maintainability.

### 📜 Context
This was a coding challenge consisting of four assignments:
1. **Logic:** A custom "FizzBuzz" implementation.
2. **String Manipulation:** A multibyte-safe string reverser.
3. **Security:** A secure 'forgot password' flow.
4. **Algorithms:** A matrix rotation function (90 degrees).

*Note: This project was originally built following specific requirements (PHP 7.2+ compatibility and Symfony preference).*

### 🛠 Tech Stack
- **Framework:** Symfony 5
- **PHP:** 7.4.11
- **Database:** MySQL

### 🚀 Development Instructions

1. **Clone & Install:** Download the repository and run `composer install`.
2. **Environment:** 
   - Configure your database credentials in `.env`.
   - To test the password reset (Assignment 3), configure a valid `MAILER_DSN` (SMTP).
3. **Server Setup:**
   - Run `symfony server:start` from the project root.
   - Set up a local proxy using `http://127.0.0.1` (following the [Symfony documentation](https://symfony.com)).
   - Run `symfony proxy:start`.
4. **Access:** Open the application via your local Symfony proxy URL.

---
*Archived project for portfolio purposes.*
