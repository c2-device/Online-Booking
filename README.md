By default, Database is configured with postgresql.
To chagnge configuration, check .env file
---------------------------------------------------------------------------------------------------------------------------------------------------------
Create Database booking

Run the following Commands:-
php artisan optimize:clear
php artisan migrate:fresh   
php artisan db:seed --class=MeetingRoomSeeder
