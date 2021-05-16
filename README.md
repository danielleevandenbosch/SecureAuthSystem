# SecureAuthSystem
A secure PHP login system made from scratch with protections against several common attacks

Check out the youtube playlist here: https://www.youtube.com/playlist?list=PLG5M8QIx5lkwT6ly5V34uLpX_5anpUEB3


### Features / Protections
- Login (protected against brute force/dictionary attacks)
- Sign Up
- password reset (done in a secure and friendly manner)
- Email Validation (ensure user has access to the email they used to make the account)
- CSRF protection for all features/forms
- Account Deletion 
- All features are protected from SQL Injection using PHP prepared statements
- XSS protection (see video for how to impliment when adding your own pages with untrusted data on them)
- All passwords are hashed so that even with access to the database attackers could not obtain users passwords (passwords are hashed and salted)

... Possibly more that I did not think of at the time of writing this

***Some features may not have been implemented yet***


### How to Use
1. Download and install either MAMP/XAMPP (alternatively individually download php, mysql, and an apache server if you know what you are doing)
2. Copy and paste all files into the public directory
3. Start mysql and apache server services
4. Done! It should be that easy
