# registration-web-service

To Run the application. If you have PHP installed locally and you would like to use PHP's built-in development server to serve your application, you may use the serve Artisan command. This command will start a development server at http://localhost:8000:


php artisan serve



First you need to migrate database to edit .env file and enter our database credentials:

DB_DATABASE=YOUR_DB
DB_USERNAME=YOUR_USERNAME
DB_PASSWORD=YOUR_PASSWORD




Then run the migration to create the table:


php artisan migrate
