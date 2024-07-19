# Registraion_Page

**For Database creation follow below steps** - 
Click on windows button, search for mysql and from dropdown sselect mysql command line client or simply search for mysql command line client
Open the mysql command line client and write down your password.
1) create database login_page;
2) use login_page;
3) create table users(
 First_Name varchar(30) not null,
 Last_Name varchar(30) not null,
 Email varchar(50) not null unique,
 Password varchar(30) not null);
4) after all connection done then run this command - select * from users; to show the database

 **For Installing Django follow below steps** - 
 
 pip install django
 pip install mysql-connector-python
 then create file in VS Code using this command -  django-admin startproject Login_Form
 then make One template folder and make 4 files of html i.e signu_p.html, error.html, welcome.html, login_p.html
 and make two folder of login and sign up using following command - django-admin startapp login, django-admin startapp signup
 and run the server using this command - python manage.py startapp home
