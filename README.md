  
## Pixel Positions
Pixel Positions is a job platform that connects job seekers to employers using search filters, job tags, and featured jobs. A Fullstack Website built using PHP Laravel 11.

![homepage](https://github.com/user-attachments/assets/650a1f18-11a7-47a3-a587-e1eb0ad6db8b)

The website includes standard account authentication, job search filers, job tag filters and featured jobs

## Requirements

- **Laravel Herd:** Recommended for a seamless development experience.
- **Node.js and npm:** Required for frontend assets compilation.
- **PHP:** Required for running the Laravel application.

### Setup:
- Clone the project on your Laravel Herd project folder. Default is `C:\Users\(PC name)\Herd`
- Run Laravel Herd to automatically run the project.
- Open a terminal and cd into the folder of the cloned repository.
- Run `composer install` to install PHP dependencies.
- Run `npm install` to install frontend dependencies.
- Run `php artisan migrate` to create the database tables.
- Run `php artisan db:seed` to seed the database tables with data.
- Run `npm run dev` to start the frontend assets.
- Open the url `pixel-positions.test` which is automatically created with Herd using the folder name.

You should now see the website with seeded data.

### Testing

- Run `php artisan test` to test the application features.


## The Website

### Homepage
![pixel-positions test_](https://github.com/user-attachments/assets/76588570-031d-4287-8b43-cd5dcd3d1888)

### Registration Page
![pixel-positions test_register](https://github.com/user-attachments/assets/a3b30a51-5d15-458c-b497-5eb4afb63729)

### Create Job Page
![pixel-positions test_jobs_create](https://github.com/user-attachments/assets/465e3bd0-2458-48a3-9dc0-9b91132f9eef)

### Database
![Job Database](https://github.com/user-attachments/assets/20e46cdd-275c-4212-927a-db3ae150bcd1)

## To do list:
- add tags as search parameter
- check auth redirect when creating job while not logged in
- change tag input type in create jobs form
