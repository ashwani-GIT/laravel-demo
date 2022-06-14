# laravel-demo
create some application experiments in laravel and some demo code

windows only

1. How to install composer: 
php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === '55ce33d7678c5a611085589f1f3ddf8b3c52d662cd01d4ba75c0ee0459970c2200a51f492d557530c71c15d8dba01eae') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
php composer-setup.php
php -r "unlink('composer-setup.php');"

and after 
copy the file composer.phar into the xampp php folder.
create a file name as composer.bat
and add some lines into is that is 

php path\of\xampp\php\composer.phar %*

2. Install laravel globally using composer 
run some commands 
composer global require laravel/installer
-- laravel install intalled into your appData directory 
C:/Users/DELL/AppData/Roaming/Composer - like this


and type command *larvel* for check that properly intalled or not
if not then set the en path variable 

C:\Users\DELL\AppData\Roaming\Composer\vendor\laravel\installer\bin - like this

and create a file larvel.bat and some commnad
php C:\Users\DELL\AppData\Roaming\Composer\vendor\laravel\installer\bin\laravel %*