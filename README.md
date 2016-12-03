# _Cipher Central_

#### _Encryption tools website with shift cipher, made in Drupal, 12/2/16_

#### By _**Molly LeCompte**_

## Description

_The shift cipher tool in this website takes user-inputted text and encrypts it by replacing each letter with the letter x places before or x places after it. The user selects a shift value and a shift direction, then enters a phrase to encrypt via a validated form (the form only accepts integers for shift value, 'left' or 'right' for shift direction, and alphanumeric characters or basic punctuation & spaces for the phrase). The encryption function replaces each letter according to the user's specifications, leaving spaces and punctuation as is._

## Setup/Installation Requirements

* _Clone this repository_
* _Launch MAMP and set web server document root to main project folder_
* _Access phpMyAdmin by directing browser to http://localhost:8888/phpMyAdmin/_
* _Import database by navigating to 'Import' tab in phpMyAdmin and uploading the database zip file located in the project's /sites/db-backup folder (make sure the selected character set is utf-8)._
* _Once database (named 'cipher') is imported, navigate to 'Privileges' tab in phpMyAdmin and add a user, setting both the username and password to 'cipher'._
* _Direct browser to http://localhost:8888_

_Both the username and password for the Drupal site maintenance account is 'cipher'. Use these credentials to make administrative changes to the site._

## Known Bugs

_None_

## Support and contact details

_Reach me at mollyklecompte@gmail.com with any questions or issues with the site._

## Technologies Used

_PHP, Drupal, MYSQL_


### License

*This software is protected under the MIT license*

Copyright (c) 2016 **_Molly LeCompte_**
