/online-shopping
    ├── /assets
    ├── /css
    ├── /js
    ├── /config
    ├── /includes
    ├── /templates
    ├── /db
    ├── index.php
    ├── README.md
    ├── LICENSE
    └── .gitignore


# Online Shopping for Electricals Product

## Description
This is a PHP and MySQL-based web application designed for an electronic products online shopping platform. Users can browse products, add items to their cart, and proceed to checkout. The application includes a user-friendly admin panel for managing products, orders, and users.

## Features
- User Authentication (Login/Signup)
- Product Listings with Categories
- Add to Cart & Checkout functionality
- Admin Panel (CRUD operations for products)
- Responsive Design
- Order History and Tracking

## Tech Stack
- **Backend**: PHP
- **Database**: MySQL
- **Frontend**: HTML, CSS, JavaScript
- **Frameworks/Libraries**: Bootstrap (for styling)
  
## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/online-shopping.git
    ```
2. Navigate to the project folder:
    ```bash
    cd online-shopping
    ```
3. Import the SQL file into your MySQL database:
    ```sql
    source db/online_shopping.sql
    ```
4. Set up the `config.php` file with your database credentials:
    ```php
    define('DB_HOST', 'localhost');
    define('DB_USER', 'your_user');
    define('DB_PASS', 'your_password');
    define('DB_NAME', 'your_database');
    ```
5. Start your local development server:
    ```bash
    php -S localhost:8000
    ```
6. Open the browser and visit `localhost:8000`.

## Admin Panel
To access the admin panel, login with the admin credentials (can be set in the database).

## Contribution
Feel free to open issues or submit pull requests for improvements.

## License
This project is licensed under the MIT License.
