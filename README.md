# A simple application to learn Larave JobBatching and how to show realtime detail of jobs with NextJs.

-   Laravel

-   NextJs

1. Clone the project

   
2. Cd to the **./Laravel-JobBatching-Backend**


3. install packages via this command
   : `composer:install`
   

4. Connect to your own database and run database migration
   : `php artisan migrate`


5. Run queues via this command
   : `php artisan queue:work`
   

6. Serve your server if you are not using **VirtualHost**
   : `php artisan serve`
   
## *Now the backend is Ready*

7. Cd to the **./Laravel-JobBatching-Front**  


8. Run 
   : `npm install`


9. Go to **./pages/upload.js** and edit the **Base_Url** like this : *http://127.0.0.1:8000.com/api*


10. Serve your Next application 
   : `npm run dev`


## Done, go to the 'http://localhost:3000' and test the Application.

**Be Happy:)**


### A simple csv file is in the main folder. so you can use that but if you want to use another one, you must change and edit table. ./Laravel-JobBatching-Backend/database/migrations/*create_machines_table* 
