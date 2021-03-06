# OrdersCounter
**by @fvlgnn || @cianaweb**

---

## System

* AMP (Apache2, MySQL5+, PHP7+)
---

## Framework

* CodeIgniter 3.1.*
* Grocery Crud 1.6.*
---

## Style

* Bootstrap 3.*
* StartBootstrap - SB Admin
* font-awesome 4.7.*
---

## JavaScrip

* jQuery 1.12.*
* morris.js
* bootstrap-datepicker.js 
---

## Setup

* import MySQL db from `orderscounter.sql` file (some demonstration data and login user are already present)
* configure `application/config/database.php` file
* configure `application/config/email.php` file
* configure `application/config/configCustom.php` file in `email array();` set your sender address `'fromEmail'	=> 'sender@server.com'`
* configure `application/config/config.php` file. Set url `$config['base_url']` of webapp. Ex.  `$config['base_url'] = 'http://localhost/orderscounter/';` if it runs on `localhost` under `orderscounter` folder
* configure `.htaccess` file. Set the base path `RewriteBase` of webapp. Ex. `RewriteBase /orderscounter/` if it runs orderscounter` folder 
* First login
	* username: *demo@server.com*
	* password: *password*
* create a new *Admin* user and delete *demo@server.com* user

---

## Description

* **Dashboard**: Insert orders (automaticaly split for first and second shift)
* **Statistics**: Show all orders statistics
* **Settings**: Set Orders, Items (foods/drinks), Types(tipology of foods/drinks), Users
* **User/Profile**: Edit your profile or change password
