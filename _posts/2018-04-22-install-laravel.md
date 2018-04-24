---
layout: post
title: 'Laravel Installation in 3 Steps  '
subtitle: Easy way to Learn Laravel Framework ...
tags:
  - Laravel
  - PHP Framework
  - Web Application
  - Programing
  - laravel tutorial
  - laravel installation
published: true
---


## Learn By Doing It.

Here I’m sharing with you my recent experience with Laravel 5.5 the most popular and committing PHP Framework in present time.
If You want to learn a new programming language or a framework you should learn by following their official documentation. Because no one can teach, help and suggest you better than them. So I would like to suggest you to get up to date with the official sites. 

Installation:

Apache Server:  If you are not using Laravel Homestead virtual machine for Server support than you can a apache local server like XAMPP, WAMP, LAMP, MAMP any of them according to your Operating system. But one thing you must remember that Local Server must meet the requirements to run the Laravel Framework Version.  Since We’re using Laravel 5.5 we need to check these criteria before installing any local server. Requirements:
•	PHP >= 7.0.0
•	OpenSSL PHP Extension
•	PDO PHP Extension
•	Mbstring PHP Extension
•	Tokenizer PHP Extension
•	XML PHP Extension

 Here I’m using the latest version of WAMP SERVER for my Windows Operating system which have 3 version of PHP. 
Link for WAMP server : http://www.wampserver.com/en/#download-wrapper

Composer: After successfully Installation of your local server you need another thing to setup in your machine to create the environment for Laravel. You need to install composer   - a PHP package manager that is integrated with Laravel Framework. You can either download the composer than install or you can install it from CLI. During Installation you must show the PHP path of your system. 
Checking composer: Go to your command prompt than write composer and hit enter. 

Composer Link:  https://getcomposer.org/download/
Now the exciting part of your work, you are ready to rock with Laravel.
 We got WAMP.  Check.
 We got Composer. Check. 

Create First Laravel Project:
You can create your own project in two different ways those are:
1 Using Laravel Installer
For Laravel Installer you should install Laravel installer first. 
Go to your command prompt as Administrative user type:
 >composer global require “Laravel/installer” 

then hit enter. 
After that type:
 >larval new YourProjectName

hit enter.

2 Using Composer: 
Go to your command prompt and type
>composer create-project --prefer-dist laravel/laravel YourProjectName "5.5.*"

Then hit enter. It you take some moment to download and install files for you. 
Congrats!! You have successfully installed your first. Now check the project weather it’s working or not.

Go to Your File Directory and open the command prompt here.
Trick: Press Shift and Click on the Right Button of your mouse and you will see the open command prompt in the pop up menu select it. Type this command on command prompt and hit enter.
>php artisan serve

You will see something like this, which means project is running successfully: 
Laravel development server started: http://127.0.0.1:8000
Now copy the url and open it in your internet browser you will see the welcome page of laravel project.
 


# Stay Tune. I will be Right Back.
