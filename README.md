# laravel-questions-answers
This repo contains general/mostly asked laravel questions for interview preps.

# Laravel Interview Questions and Answers
The answers are without any order. It is as per search so there is a chance that you can get advanced questions in the beginning and starter questions at the end. Enjoy it!

## 1. What is Laravel?
Laravel is a PHP web application framework with expressive, elegant syntax. It aims to make development easier by providing common tasks like routing, sessions, caching, and authentication.

## 2. Name the latest Laravel version.
As of October 2024, the latest stable Laravel version is 10.

## 3. Explain some important directories you would use in a Laravel application.
- `app/`: Holds core application logic (e.g., Models, Controllers).
- `config/`: Stores configuration files.
- `routes/`: Contains route definition files (e.g., `web.php`, `api.php`).
- `resources/`: Contains views, raw assets, and language files.
- `database/`: Holds database migrations, seeds, and factories.
- `public/`: Contains front-facing assets (e.g., CSS, JavaScript).

## 4. Describe reverse routing.
Reverse routing generates URLs based on named routes, allowing Laravel to create consistent links and making URL changes easier to manage globally.

## 5. What is Composer?
Composer is a dependency manager for PHP, used by Laravel to install packages and manage project dependencies.

## 6. What templating engine do programmers use in Laravel?
Laravel uses Blade, a simple yet powerful templating engine.

## 7. How would you register service providers?
Service providers are registered in the `config/app.php` file within the `providers` array.

## 8. Can you use Laravel for full-stack development?
Yes, Laravel supports backend and frontend functionality through Blade views, controllers, and tools like Laravel Mix and Inertia.js.

## 9. Talk me through the steps of putting Laravel applications in maintenance mode.
Run `php artisan down` to enable maintenance mode and `php artisan up` to disable it.

## 10. Explain the default route files in Laravel.
- `web.php`: Handles routes that require session state, CSRF protection.
- `api.php`: Defines stateless routes primarily for APIs.
- `channels.php`: Defines event broadcasting channels.
- `console.php`: Defines custom Artisan commands.

## 11. How do you define environment variables?
Environment variables are defined in the `.env` file. You can access them with `env('VARIABLE_NAME')` or via configuration files.

## 12. What are migrations?
Migrations are version control for the database, allowing schema changes to be tracked and shared easily.

## 13. What is HTTP middleware?
Middleware filters HTTP requests entering your application, useful for tasks like authentication and CSRF protection.

## 14. How should you implement soft delete in Laravel?
Add `use SoftDeletes` in the model and add a `deleted_at` column to the database table.

## 15. What is a route? How do you use one?
A route directs HTTP requests to specific controllers or closures, defined in `routes/web.php` or `routes/api.php`.

## 16. State the differences between the GET and POST methods.
- `GET`: Used to request data, no data modification.
- `POST`: Used to submit data, often modifies server state.

## 17. What are the advantages of using Laravel?
Features include a modular packaging system, Eloquent ORM, extensive libraries, Blade templating, and a vibrant community.

## 18. What does ORM stand for?
ORM stands for Object-Relational Mapping, a technique that connects objects in code to database tables.

## 19. How can you reduce memory usage?
Memory usage can be reduced by eager loading, reducing object instantiation, or using queued jobs for deferred processing.

## 20. Name some databases that Laravel supports.
Laravel supports MySQL, PostgreSQL, SQLite, and SQL Server.

## 21. How do you use a custom table?
Define the table name in the model by setting the `$table` property, e.g., `protected $table = 'custom_table_name';`.

## 22. What are the popular features of Laravel?
Key features include MVC architecture, Artisan CLI, Eloquent ORM, Blade templating, task scheduling, and caching.

## 23. Describe the structure of a typical Laravel project.
Common directories include `app`, `config`, `resources`, `routes`, `public`, and `database`, each containing specific parts of the application.

## 24. What are the server requirements for installing Laravel version 8?
PHP >= 7.3, OpenSSL, PDO, Mbstring, Tokenizer, XML, Ctype, and JSON extensions.

## 25. What are the available router methods in Laravel?
Laravel offers `get`, `post`, `put`, `patch`, `delete`, and `options` router methods.

## 26. What is the purpose of a session in Laravel?
Sessions store user information across requests, enabling persistence (e.g., login status) within the application.

## 27. Describe what authorization means.
Authorization manages user permissions, ensuring only authorized users can access specific resources or actions.

## 28. What are some common HTTP error codes?
404 (Not Found), 500 (Internal Server Error), 403 (Forbidden), 401 (Unauthorized).

## 29. How can you generate URLs?
Use the `url()` and `route()` helpers to generate URLs.

## 30. Explain the concept of contracts in Laravel.
Contracts are interface definitions for core Laravel services, ensuring consistent usage and dependency injection.
"""

