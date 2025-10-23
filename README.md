# Docker GLPI Laravel
# 🚀 Welcome to my Docker projects in GLPI tutorial! 🚀# 

Hey there! I'm Lorraine, a 21-year-old programmer who loves working with shell scripts and Docker. Since I'm practicing my English, I decided to write this tutorial in English. Let's get started!

# Prerequisites #
Make sure you have a Laravel project ready. If not, you can clone one directly from the Laravel website and follow their documentation.
Ensure Docker is installed on your machine.
Getting Started
Clone this personal project using the following command:

bash
Copy code
git clone https://github.com/Alerpina/Docker-projects-laravel.git
Navigate to the project directory:

bash
Copy code
cd Docker-projects-laravel/project-laravel
Build and run the Docker containers:

bash
Copy code
docker-compose up -d --build
Access phpMyAdmin at http://localhost:8080.

Create a database for your Laravel project.

Attach a shell to the workspace container:

bash
Copy code
docker exec -it workspace bash
Build your Laravel project:

bash
Copy code
composer install
Copy the .env.example file to .env:

bash
Copy code
cp .env.example .env
Run database migrations:

bash
Copy code
php artisan migrate
Set appropriate permissions:

bash
Copy code
chmod -R 755 *
Access your Laravel website at http://localhost.

That's it! You're all set to explore your Laravel project within a Docker environment. If you face any issues, feel free to ask for help. Happy coding! 🎉

![image](https://github.com/Alerpina/Docker-projects-laravel/assets/101226446/49345a75-bc3e-43f5-8057-5c6ca8bc721b)
<img width="258" height="37" alt="image" src="https://github.com/user-attachments/assets/66042f48-9fad-423c-9b2b-9752c913fdc8" />
<img width="1008" height="765" alt="image" src="https://github.com/user-attachments/assets/36b63da4-676f-49c8-82a0-387c77732706" />
<img width="534" height="355" alt="image" src="https://github.com/user-attachments/assets/0a27a0ef-30b0-4d5a-8424-2879934b3637" />




