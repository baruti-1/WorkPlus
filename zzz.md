# Extensions

- PHP Intelephense, Laravel Snippets, Laravel Blade Snippets, (GitHub Theme)

# Installation

- Laravel Herd (herd.laravel.com), to secure the domain run: herd secure in terminal
- Laragon (windows only)
- Composer (after installation use composer to create the project i.e. create-project laravel/laravel projectname)

- After creating the project use laravel artisan command line tool to manage the project (php artisan)

# NOTE - sending POST request using curl: curl -X http://endpoind

# Routes

- To list all routes in the project: php artisan route:list

# SOME NAMING CONVENTIONS

- Routes: name routes in plural. i.e. /jobs/{id}
- Controllers: name controllers in singular and use Pascal case. i.e JobController
- Models: name models in singuler and use Pascal case. i.e Job

# Resource methods

- index() list all resources
- show() list single resource
- create() Display create form
- store() Submit create form
- edit() Show edit form
- update() Submit edit form
- destroy() Delete resource
  = Generate all these methods in the controller: php artisan make:controller YourController --resource

# Type Hinting

- It refers to the way to specify the data type of variables in PHP for readability and maintenability. It helps to catch errors early in the development process.
- Common Types:
    - Illuminate\Http\Request
    - Illuminate\Http\Response
    - Illuminate\Http\RedirectResponse
    - Illuminate\Http\RedirectResponse
    - Illuminate\Http\JsonResponse
    - Illuminate\View\View
    - Illuminate\Support\Collection
    - Illuminate\Auth\Access\Response

# Layout Components

- php artisan make:component Yourcomponent
