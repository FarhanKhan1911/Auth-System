# Auth-System

## Pictures

<p align="center" width="100%">
    <h2> Main Page </h2>
    <img src="https://github.com/FarhanKhan1911/Auth-System/blob/main/assests/home.jpg"> 
    <h2> Login Page </h2>
    <img src="https://github.com/FarhanKhan1911/Auth-System/blob/main/assests/login.jpg">
    <h2> Register Page </h2>
    <img src="https://github.com/FarhanKhan1911/Auth-System/blob/main/assests/register.jpg">
    <h2> Logout Page </h2>
    <img src="https://github.com/FarhanKhan1911/Auth-System/blob/main/assests/logout.jpg">
    <h2> Main Page (Login) </h2>
    <img src="https://github.com/FarhanKhan1911/Auth-System/blob/main/assests/home(login).jpg">
    <h2> Mobile Responsive </h2>
    <img width="20%" src="https://github.com/FarhanKhan1911/Auth-System/blob/main/assests/responsive.png">
</p>


## Requirement 

Python v.3.8+

## Usuage

### Clone Repository

Copy Paste the following commands to clone the repo

```bash
  git clone https://github.com/FarhanKhan1911/Auth-System
```
Go inside the directory and install the module from requirements.txt

```bash
  pip install -r requirements.txt
 ```
 
 Then make the migrations and then migrate the database
 
 ```bash
    python manage.py makemigrations
    python manage.py migrate
  ```
  
  Create the superuser 
  
  ```bash
    python manage.py createsuperuser
  ```
  
  Now run the django server
  
  ```bash
    python manage.py runserver
  ````
  
  <h2>Now you goto localhost:8000 to see the website</h2>
  
  ```bash
      http://127.0.0.1:8000/
  ```
  
