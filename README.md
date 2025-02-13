# Software Quality Engineering - System Testing
This is a repository for the system-testing assignment of the Software Quality Engineering course at the [Ben-Gurion University](https://in.bgu.ac.il/), Israel.

## Assignment Description
In this assignment, we tested an open-source software called Presta Shop (https://demo.prestashop.com/#/en/front).

PrestaShop is a free and open-source e-commerce platform that enables users to create and manage online stores.
It provides a user-friendly interface, a wide range of customizable themes, and a modular architecture that 
allows store owners to extend functionality with plugins and modules.

## Installation
In order to install PrestaShop and prepare the testing environment, do the following:

### 1. Download and install XAMPP
   
   Enter the XAMPP website, download and install the latest version of XAMPP.
   Go to C:/xampp/htdocs and create a new folder for your Presta Shop project.
   
### 2. Start XAMPP Server
   
   Open the XAMPP server, and click the "start buttons of the Apache and the MySQL modules.

### 3. Download PrestaShop

### 4. Create Database

   Open your web browser and navigate to http://localhost/phpmyadmin, then create the database.

### 5. Setup IDE

   As we chose Java as the main programming language, inststall any relevant IDE, with JDK Java 17.

### 6. Setup Selenium Server

   Download Selenium from https://www.selenium.dev/downloads/
  
   Add the JAR file to the java project dependencies built with Maven

### 7. Download Proper chromedriver

   Download proper version chromedriver according to your google chrome version, and locate it in the Selenium directory.
      
   Download Page: https://chromedriver.chromium.org/downloads

### 8. Install PrestaShop

## What we tested
Add a description of the module and the user stories that you chose to test.
For example, in the case of the Moodle example, you can write something like this:

We tested the quiz module that allows for creating and taking quizzes. We chose to test the following user stories: 

*User story:* A admin delete a product from his store

*Preconditions:* There is admin and user in the store

*Expected outcome:* The product removed from the website

*User story:* A user add comment to a product in the store

*Preconditions:* There is product in the store website accessible to the user

*Expected outcome:* The comment is added to the product

## How we tested
We used two different testing methods:
1. [Cucumber](https://cucumber.io/), a behavior-driven testing framework.
2. [Provengo](https://provengo.tech/), a story-based testing framework.

Each of the testing methods is elaborated in its own directory. 



 
