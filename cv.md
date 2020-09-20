Mishyn Pavel
================
Contact Info
----------------
* [Github](https://github.com/MishynPavel)
* [Gmail](mishynpn@gmail.com)
* [Linkedin](https://www.linkedin.com/in/pavel-mishyn-a59b161a9)
* [Repl](https://repl.it/@PavelMishyn)

Summary
----------------
I strive to realize myself in front-end development. I have a small but useful and fundamental experience in project development at IT Academy. And working in other organizations and in other areas is a good example of using new ideas and interesting solutions in the field of programming. I actively expand my capabilities, knowledge and skills in my free time from work.

Skills
----------------
**Programming Languages**
:
	* JavaScript
	* HTML
	* CSS
	* PHP
	
**Additional Stuff**
:
	* Git
	* Bootstrap
	* Photoshop
        * 3D programs


Code Example
----------------
An example from a training project to create a PHP website:
```<?php
  //print_r($_POST);
  $email = $_POST['email'];
  $message = $_POST['message'];
  $error =''
  if(trim($email) == '')
    $error = 'Not entered email!';
  else if(trim($message) == '')
    $error = 'Not entered message!';
  else if(strlen($message) <10)
    $error = 'Enter a message more than 10 characters!';
  if($error != '') {
    echo $error;
    exit;
  }
  $subject = "=?utf-8?B?".base64_encode("Test message")."?=";
  $headers = "From: $email\r\nRiply-to: $email\r\nContent-type: text/html; charset=utf-8\r\n";
  mail('mpndesign@mail.ru', $subject, $message, $headers);
  header('Location: /about.php');
?>
```

Experience
----------------
* [IT Academy-FD1](https://FD1projectSmallFish.pavelmishyn.repl.co)
* [IT Academy-FD2](https://FD2projectColoring.pavelmishyn.repl.co)
* [Repl-Bootstrap](https://Bootstrap.pavelmishyn.repl.co)
* [Repl-php](https://PHPsite.pavelmishyn.repl.co)

Education
----------------
2019-2020
:   **Self-education**
2019-2020
:   **IT Academy**; FD_1 - Websit development with html, CSS & javascript. (Minsk)
2019
:   **IT Academy**; FD_2 - Web application development with javascript. (Minsk)
2008-2013
:   **Minsk Innovation University(МИУ)**; Design (Minsk)

Languages
----------------
* Russian (native speaker)
* English (Elementary possession)
