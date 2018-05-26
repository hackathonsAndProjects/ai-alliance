# AEye-Alliance
For the AI4SocialGood Hackathon -- Converting Braille Images to English 
</br>
To run the website on your computer:
</br>

## Install XAMPP: 
https://www.apachefriends.org/index.html

## Set Up:
</br>
Open XAMPP control panel and start Apache and MySQL modules. 
Go to http://localhost/dashboard/ If you see the XAMPP header, then congrats, you're in! Note: MySQL and all the pretty web package will run as long as you keep these settings on XAMPP control panel. To turn off these features, go back to XAMPP control panel and click "Stop" where applicable (MySQL and Apache), and the server will stop running. 
</br>
To access the Database (MySQL), click on phpMyAdmin. Click on Database. Create a new database and we will name it ai-alliance (note: you can choose whatever name you want, it won't matter).
Once the database has been initialized, go to MySQL and you will be able to enter SQL commands, such as create table, insert data, etc. to populate your local database (data coming soon :) ). 
To start off, you need to create a table, which will store our data. For example, run the command 
</br> create table brailledict(Picture varchar(255), Label varchar(255)); 
</br>
will create a table named brailledict with columns Picture and Label each taking a string up to length 255. 
</br> To learn more about SQL: 
https://www.w3schools.com/sql/default.asp


## Putting the files in the right place
</br>
Find the xampp folder on your computer (usually under C disk). Go to C:/xampp/htdocs.Inside htdocs, create a new folder named ai-alliance. Inside this folder, put whatever files you think pertain to the project, or just a file that you want to test. Note: you can also create more subfolders if you like. To make sure that you created the folder in the right place, go to localhost/ai-alliance. If you get an error message, you didn't do it right :(. Else congrats :). 
