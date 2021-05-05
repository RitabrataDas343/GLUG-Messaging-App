# GLUG-Messaging-App

This is GLUG Messaging App built in Django and Django-Rest-Framework.

![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)<br>

> The app allows you to chat with other GLUG members in realtime. This app is basically inspired from WhatsApp.

##  Starting the Project


1. Clone the project in the virtual environment directory.

    ```
    git clone https://github.com/RitabrataDas343/GLUG-Messaging-App.git

    ```

2. Create a **virtual environment** with venv (install virtualenv, if its not installed).

    ```
    python3 -m venv env

    ```

3. Activate the virtual environemnt.
 
    ```
    source env/bin/activate

    ```
    
4. Install the requirements.

    ```
    cd reviewbook
    pip3 install -r requirements.txt

    ```


5. Run the Migrations
    ```
    python3 manage.py makemigrations
    python3 manage.py migrate

    ```
6. Run the development server
    ```
    python3 manage.py runserver

    ```
7. Head to server http://localhost:8000


## Tech-Stack used

GLUG-Messaging-App uses the following technologies:

+ HTML/CSS/JavaScript
+ Python(Django)
+ Django Rest Framework

