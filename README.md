# php-scraper
It was written PHP scraper which parses iBus job offers. 

Description
1.Have obtained data from a web site saved in a json file (in 1 file and in 3 json files)
2.It was written "API endpoint" that returns processed data, this is equivalent to one-json/src/jobs-data.php(1-way) and multiple-json/src/jobs-data.php (2-way).
This file (jobs-data.php) need to be opened on the server, collected in localhost and path to file
for example: my case will be http: //localhost/job/one-json/src/jobs-data.php.
3. It was written "CLI task" which checks the generated json file, this file is equivalent to one-json/scripts/ validate.php.This file will need to be opened at the command prompt
for example: my case will be > cd:\Users\user\Desktop\job\one-json\scripts\validate.php
>c:\php\php.exe  validate.php and enter 
