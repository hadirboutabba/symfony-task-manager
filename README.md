# Symfony Task Manager

A simple Symfony app to help you keep track of tasks.  
You can add, edit, and delete tasks with titles and descriptions.

## Features

- Add new tasks with title and description  
- Edit existing tasks  
- Delete tasks  
- Clean, simple UI with custom CSS  

## Requirements

- PHP 8.1 or higher  
- Composer  
- Symfony CLI (optional but recommended)  
- MySQL or MariaDB  

## Installation

1. Clone the repository:  
   `git clone https://github.com/hadirboutabba/symfony-task-manager.git`

2. Install dependencies:  
   `composer install`

3. Configure your database in `.env` file.

4. Create and migrate the database:  
    php bin/console doctrine:database:create
    php bin/console doctrine:migrations:migrate

5. Start the Symfony server:  
`symfony server:start`

6. Open [http://localhost:8000](http://localhost:8000) in your browser.

## Usage

- Visit the homepage to see the task list.  
- Add new tasks using the "Add New Task" button.  
- Edit or delete tasks from the list.