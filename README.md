# Laravel Livewire CRUD Operation with Login, Logout (SPA)

Basic CRUD operation in Laravel Livewire with login and logout. Category adding, viewing, editing, and deleting operations were implemented. A simple Counter was also integrated.
## Project Details

- **GitHub Repository**: [https://github.com/shohag-cse-knu/laravel-livewire-crud.git](https://github.com/shohag-cse-knu/laravel-livewire-crud.git)

## Features

- **Login**:
- **Register**:
- **Home**: A basic home page.
- **Category**: Category Lists are shown here with view, edit, and delete actions.
- **Counter**: increements and decreements of number.

## Prerequisites

- **Laravel**: The minimum Laravel version required for Livewire is Laravel 7.x.
- **PHP**: Livewire requires PHP version 7.3 or higher.
- **Composer**: Since Livewire is installed via Composer, make sure you have Composer installed on your system.
- **JavaScript Dependencies (Laravel Mix / NPM)**:Livewire uses JavaScript for some of its features, and Laravel uses Laravel Mix (which is based on Webpack) for compiling assets. You need to have Node.js and npm installed to manage the front-end assets.

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/shohag-cse-knu/laravel-livewire-crud.git
````
### 2. Change the .env
Modify Database name, db user and password.

### 3. Composer Update
```bash
composer update
````

### 4. DB Migration
```bash
php artisan migrate
````

### 5. Run
```bash
php artisan serve
````

## Technologies Used

- **Frontend**: HTML, CSS, Blade
- **Backend**: Laravel Livewire, MySql

## Contributing

To contribute:

1. Fork the repository.
2. Create a branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## Contact

For questions or suggestions, please contact:

- **Name**: Syfur Rahaman Shohag
- **Email**: [syfur.srs@gmail.com](mailto:syfur.srs@gmail.com)
- **GitHub**: [https://github.com/shohag-cse-knu](https://github.com/shohag-cse-knu)
