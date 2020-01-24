# Life Insurance Management System
A dashboard website for a Life Insurance Company
Built using PHP, mysql, HTML, CSS

Login, logout, session, multilevel access, image uploads
are implimented here

## Features
- Agents can create clients
- Agents can only edit and delete info of the client they created
- Master Agent can create update, delete all clients and agents info
- Payment records and nominees can be added and managed by agents

## Deploy on localhost
Assuming **XAMPP** is already installed

1. Clone into your **xampp/htdocs** folder
2. Edit the **lims/connection.php** file with your database username and password
2. Goto http://localhost/phpmyadmin
3. Create a database named **lims**
3. import the **lims.sql** file provided in **database backup** folder
4. Goto http://localhost if you see a login page, its working

##DEMO
This project is hosted at https://lims.nafisulbari.com for you to play with.
Username: 555 
Password: 666