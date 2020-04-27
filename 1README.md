How to use
Clone the repository with git clone
Copy .env.example file to .env and edit database credentials there
Run composer install
Run php artisan key:generate
Run php artisan migrate --seed (it has some seeded data for your testing)
That's it: launch the main URL.
Click on Register on bottom-right corner, or go directly to /register URL
You can login to adminpanel by going go /login URL and login with credentials admin@admin.com - password


php artisan serve
