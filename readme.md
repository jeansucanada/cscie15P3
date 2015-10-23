# CSCI E-15 Project 3 by Jean Yu Chun Su

## Live URL
[http://p3.meiosise.com](http://p3.meiosise.com)

## Description
This project is to generate random paragraphs of text, users or xkcd style password to help developers obtain useful unit testing data in our daily work.
The application is created with Laravel framework and Composer is used to manage packages applied in the project.
Controllers were used to route pages and views were used to organize GUI page html.

Users can select maximum of 99 paragraphs to generate lorem ipsum text placeholder.

Users can select maximum of 20 users to generate random user data with their name, birthdate, profile and favorite food data shown in the result.

Users can select maximum of 9 words to generate a xkcd style password. Moreover, a number or special symbol can be appended to the password. Users can also change all letters in the password to uppercases.
 

## Demo
[https://youtu.be/hYT6I4txkbs](https://youtu.be/hYT6I4txkbs)

## Details for teaching team 
No login required.

A Random class was created to support random user creation with object storage in array collection. The class source code was stored at app/Http/Library folder (Library folder is a new folder added by author to store src of new classes added outside Laravel framework).

welcome.blade.php file created by Laravel framework was moved to views/home folder to better organize views corresponding to controller action.

The source code of the project can be found at my github repository: <https://github.com/JeanYSu/cscie15P3>

## Outside code
* Bootstrap: http://www.w3schools.com/bootstrap/
* css style for sticky footer http://getbootstrap.com/examples/sticky-footer-navbar/
* Package: backcow/lorem-ipsum used for lorem ipsum generator
* Package: fzaninotto/faker used for random user generator and xkcd style password generator