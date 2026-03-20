 Symfony & PHP Logic Assessment - Topgeschenken

This repository contains a technical assessment completed for **Topgeschenken Nederland**. The project demonstrates proficiency in PHP logic, Symfony framework implementation, and maintainability.

### 📜 Context
This was a coding challenge consisting of four assignments:
1. **Logic:** A custom "FizzBuzz" implementation.
Create a function that lists all numbers from 1 to 100, each on a new line.
However:
For every multiple of 3 (3, 6, ...), print "Top"
For every multiple of 5 (5, 10, ...), print "Gifts"
For numbers that are multiples of both 3 and 5 (e.g., 15), print "TopGifts"

2. **String Manipulation:** A multibyte-safe string reverser.
Create a form with an input field where a user can enter a value.
After submitting, the reversed version of that input should be displayed on the screen.

Example:
abc123🤓 → 🤓321cba

3. **Security:** A secure 'forgot password' flow.
Create a "Forgot Password" page where a user can reset their password.
You may (optionally) create a basic User entity and build on top of that.

4. **Algorithms:** A matrix rotation function (90 degrees).
Create a function that takes a 2D array (e.g., [[1,2,3],[4,5,6],[7,8,9]]) of at least 3×3 in size and rotates it by 90 degrees.
Bonus: Extra points if the function can rotate in both directions.

### Example
**Input:**
 ```1 2 3
    4 5 6
    7 8 9```
**Output:**
``` 7 4 1
    8 5 2
    9 6 3```

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
