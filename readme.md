=== ManageMyPass Password Less Authentication ===
Contributors: Gurudatt Shenoy
Donate link: http://www.devauth.com
Tags: Password Manager, identity, login, signup, device authenticated
Stable tag: 1.0
License: Proprietary but free for non-commercial use
License URI: http://www.gnu.org/licenses/gpl.html

ManageMyPass Password Less Authentication allows users to access an online service without requiring to register an account or sign up to access an account.

== Description ==

This plugin orginally created by me for developing on online password manager that does not require users to register or 
signin and instead access the password manager securely using a unique identity stored locally in their browser.

I hope it will be of use to others who wish to develop similar accounts for the websites.

If you find bugs please get in touch with me or better yet help fix it on [GitHub](https://github.com/CryptoGuru/ManageMyPass/ "Password Less authentication on GitHub").

= Account Creation =
On visiting the website the first time, ManageMyPass creates a new account for the user by generating a unique identity using a javascript function and then stores
this unique identity in an HTML5 supported browser's local websql database.

= Account Sign-In =
When a user visits the same website the second or any number of times thereafter, ManageMyPass checks the existence of the unique
identity and returns the unique identity value to the sign-in form. The website can then use this unique identity to link it to
the users online account and retrieve the account information.


= Requirements =
The plugin requires HTML5 Browser with JavaScript enabled.

= Contents / Files =
api.js : Encrypted JavaScript code that generates a unique random code, hashed identity and hashed device id. 

apiindex.html : This is the sample HTML file from which the API is called. You can use this as an example to modify your account sign in page.

== Changelog ==

= 1.0 =
* Initial release.
