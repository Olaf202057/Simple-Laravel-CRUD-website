# Simple Laravel CRUD
Simple Laravel Web Application with CRUD (Create, Read, Update, Delete) functions.

### Updates
- 26/08/2018
  - Upgraded Laravel version from 5.4 to 5.6
  - Fix forms styles to display errors correctly
  - Change some codes to be more 'Laravel ways'
- 07/02/2017
  - Upgraded Laravel version from 5.3 to 5.4
- 29/01/2017
  - Now have table migration script
  - Updates table columns in pages, to lowercase
  - Form now will display errors and success message
  - Update edit, delete, search pages.
- 09/11/2016
  - Added pagination to the data results (view stock and search page)
- 31/10/2016
  - Added stock image upload
  - Create user authentication, user can now register and login

# Purpose
- First web application that I developed using Laravel Framework. Developed during my learning process.
- This project will be keep on updated during my learning process, where I will improve my Laravel knowledge.

# Developed By
- Afif - https://fb.me/afzafri

# Installation
- Download or Clone this repository
```
git clone https://github.com/afzafri/Simple-Laravel-CRUD.git
```
- Create a new database
- Copy or rename file ```.env.example``` to ```.env```, and edit the file to change the attributes for database to your database configurations (host,username,password etc)
-  Open up Command Prompt(CMD) or Terminal in the project directory and run these commands:
```
composer install
php artisan key:generate
php artisan migrate
php artisan storage:link
```
- Launch web server
```
php artisan serve
```

# Credits
- Laravel PHP Framework - https://laravel.com/docs/5.3/installation
- Bootstrap Framework - http://getbootstrap.com/
- jQuery Library - https://jquery.com/
- Font Awesome - http://fontawesome.io/

# License
This library is under MIT license, please look at the `LICENSE` file
