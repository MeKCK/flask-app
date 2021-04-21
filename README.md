# Zanah Flask App

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This project is a simple python flask blogging app 
	
## Technologies
Project is created with:
* Ubuntu OS: 20.04
* VS Code 
* Python version: 3.6.9
* Flask version: 1.1.2
* Werkzeug library version: 1.0.1
* MySQl database version: 14.14
	
## Setup
To run this project:
1. Create database and tables 
* articles table  schema 
    CREATE TABLE articles (id INT(11) AUTO_INCREMENT PRIMARY KEY, title VARCHAR(255), author VARCHAR(100), body TEXT, create_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP);
* users table schema:
    CREATE TABLE users(id INT(11) AUTO_INCREMENT PRIMARY KEY, name VARCHAR(100), email VARCHAR(100), username VARCHAR(100), password VARCHAR(100), register_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP );


2. Create and activate venv

    $ python3 -m venv myenv
    $ source myenv/bin/activate

3. Install dependancies 

    $   pip3 install -r requirements.txt

4. Run the flask app

    $ flask run

                                _enjoy, code is good._ 
