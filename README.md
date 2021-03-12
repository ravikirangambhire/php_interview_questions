# php_interview_questions
1) What is PHP?

PHP is a web language based on scripts that allow developers to dynamically create generated web pages.

2) What do the initials of PHP stand for?

PHP means PHP: Hypertext Preprocessor.

3) What is the correct and the most two common way to start and finish a PHP block of code?

The two most common ways to start and finish a PHP script are:

 <?php [   ---  PHP code goes here---- ] ?> and <? [---  PHP code goes here  ---] ?>
 
 4) What is the main difference between require() and require_once()?

require(), and require_once() perform the same task except that the second function checks if the PHP script is already included or not before executing it.

(same for include_once() and include())

5) How can we connect to a MySQL database from a PHP script?

To be able to connect to a MySQL database, we must use mysqli_connect() function as follows:

<?php $database = mysqli_connect("HOST", "USER_NAME", "PASSWORD"); mysqli_select_db($database,"DATABASE_NAME"); ?>
