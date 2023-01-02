README 
ELIMU SCHOOL
-------------------------------------
For zip file download Follow this procedure
--------------------------------------
1.Extract to xampp/htdocs

2.Open the project terminal - preferably in vscode

3.Run this command

	>composer install

4.Go to your files and you'll find a ' .env.example ' file
	Rename it to ' .env '

5.In the ' .env ' file, change

	> 'DB_DATABASE=laravel'
		to 
	> 'DB_DATABASE=elimu_sch'

6.Open your phpmyadmin dashboard and create a new DB and name it 
	>'eduweka'
 and import the 'elimu_sch.sql' file that I'll send

7.Now go back to the project and run 

>php artisan key:generate

>php artisan serve

------------------------------------
ADMIN LOGINS
------------------------------------
johnlenin@gmail.com
Pass:johnlenin

-----------------------------------
TEACHER LOGINS
----------------------------------
jackharlfofw@gmail.com
Pass:JACKLOLS

-----------------------------------
STUDENT LOGINS
-----------------------------------
>You can enroll yourself 
>All registration forms just need:
	-the names
	-email
	-password
>You can just fill them just for show but they are not collected
>Skipped them cause the code was becoming too long to track






