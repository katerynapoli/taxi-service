# Taxi Service 🚕

### Project description:
```
A simple web-application that supports authentication, registration and other CRUD operations.
```

## 🎯 Features:

- registration like a driver
- authentication like a driver
- create / update / remove a manufacturer
- create / update / remove a car
- create / update / remove a driver
- display a list of all manufacturers
- display a list of all cars
- display a list of all drivers
- add driver to a car
- get info about your current car as a driver

## 💿 Required Software:
1. IntelliJ Idea (Ultimate Edition)
2. MySQL Workbench (Optional)

## ⚙️ Getting Started:
1. Copy HTTPS / SSH of the project via clicking on the ```<>Code``` button
2. Open IntelliJ Idea and choose to create a new ```Project from Version Control```
3. Paste your HTTPS / SSH
4. Open ```main/resources/init_db.sql``` and copy all the contents
5.
- If you are using MySQL Workbench:
    - Setup new connection (set your username and password, you will need them later)
    - ```Test Connection```
    - Open your freshly made connection and paste the contents of the ```init_db.sql``` as a Query
    - Press ```Execute ⚡️```
    - After that you will have ready to use Database with all necessary tables
- If you are using ```Database``` tab in IntelliJ Idea:
    - Press ```Plus ➕``` and choose MySQL as ```Data Source```
    - Set your username and password (you will need them later)
    - ```Test Connection```
    - Paste the contents of the ```init_db.sql``` as a Query in ```console``` (it will open automatically)
    - After that you will have ready to use Database with all necessary tables
6. Open ```main/java/taxi/util/ConnectionUtil```
7. Change the values of constants *USERNAME* and *PASSWORD* to your own (set to your Database earlier)
8. Click ```Current File ▾``` tab to Select Run/Debug Configuration, then ```Edit Configurations```
9. Click ```Plus ➕```, ```Tomcat Server```, ```Local```
10. In the pop-up window click ```Fix``` and choose ```web-security:war exploded```
11. After pressing ```Run ▶️``` button the new window with the application will open in your browser
12. You are successfully set up for using the Taxi Service 🎉
