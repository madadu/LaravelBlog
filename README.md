in this directory we've got all  neccessary folders (has changes) in main project 
txt file is a project_documentaion

also we've got all necessary methods in (migration,routes,blades,models,controllers)



here is procedures  to run laravel blog on your system

0 install composer 
1 install laravel (composer global require laravel/installer 
2.  go to directory (type cmd then   press enter   ---->  laravel new 
3.  go to project folder (type cmd then press enter )
4. install ui package (composer require laravel/ui)
4.1: run auth (php artisan ui --auth bootstrap)		doesn't need 
5. replace zip folders (app,database,public,resources,routes,...)
6. install and run npm (npm install && npm run dev)
7. 
  7.1 create dataBase
  7.2 set db credential (.env file)

8. run dataBase migrations ( php artisan migrate
8.1 run seeders (php artisan db:seed)	admin@example.com , madadi123123
9. makes images publicly accessible (php artisan storage:link)	
10.start dev sever ---> php artisan serve

last changes:	6/16/202
