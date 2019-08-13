# Creating and handling passwords

This is a project for a website with a form where the user can fill in a password and through a **RESTful** API there is a check if the password is valid according to same constraints:

* At least 1 letter lowercase;
* At least 1 digit;
* At least 1 capital letter;
* At least 1 character from  `($, #, @, _, -)`;
* It must not be a single dictionary word (even substituting numbers to letters) - e.g. `#H0m3` should **not** be accepted;
* Minimum length of password: 5;
* Maximum length of password: 15.

