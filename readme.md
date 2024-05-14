
## About Screening Form
Few simple point to make this tool working on your local machine


# Required Php 8.1 or greater, Mysql 8.0

1. subject-screening folder need to place in your /var/www/html/ or WAMP , XAMPP
2. open .env file in subject-screening folder and change the database connection credentials as per your DB credentials.
3. Create Database in your mysql using PhpMyadmin interface or using terminal command, Inside that database Import subject-screening.sql file.
4. Run NPM command to install node_modules from package.json
5. Run Composer command to install vendor folder from composer.json
#	Or 
4. If you don't want to do this stuff then run migration using php artisan then Table schema will be created.  
5. Once all set then run #php artisan serve# command in terminal your project folder will be ready to run on browser & Folder link display on terminal, you need to copy & hit on browser.

#Thanks  
