#Pizza Tracker App


##Description
This is a pizza tracker app that allows you to monitor the status of your pizza orders. To see how it works, follow these steps:

1.Clone this repository:

```git clone https://github.com/zm-mundrucz/personal-project-app.git
```cd "in the root folder where you cloned this app"

2.Set up environment variables:

-Copy the example environment file:
```cp .env.example .env

-Update the necessary environment variables in the .env file.
3.Install dependencies:

-Install PHP dependencies using Composer:
```composer install

-Install JavaScript dependencies using npm:
```npm install

4.Run database migrations and seed data:

```php artisan migrate --force
```php artisan db:seed

5.Start the development server:

```php artisan serve
```npm run dev

6.Register an account:

-Visit the app in your browser (usually at http://127.0.0.1:8000).
-Sign up for an account.
7.Navigate to the “Pizzas” page:

-Log in and go to the “Pizzas” section.
-Click on “View details” for a specific pizza order.
8.Update the status of the order:

-On the details page, you can modify the order status.
9.Track your pizza order:

-To check the status of a specific pizza, open a new page with the following URL format:
```http://127.0.0.1:8000/order/{pizza-id}
-Example: http://127.0.0.1:8000/order/12650
10.Future enhancements:

-In the next phase of development, we plan to add a simple button to directly view the order status.
And that’s it! We hope you enjoy using the Pizza Tracker App. 🍕🚀