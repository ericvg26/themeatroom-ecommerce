The Meat Room – Online Butchery Website
A database-driven e-commerce website built for The Meat Room, a local butchery in Browns Bay, New Zealand. This project was developed to help promote the business, showcase its product range, and enable online ordering with a user-friendly interface.

While full payment processing is not implemented, the site supports user accounts, product browsing, cart management, and order placement — with data dynamically pulled from a MySQL database via PHP. Designed with both customers and the business owner in mind, with stakholder feedback. 

Features
Dynamic Product Display: All products (beef, pork, chicken, lamb) are loaded from a MySQL database using PHP, allowing easy updates without touching HTML/CSS.
User System: Secure sign-up and login with session management.
Shopping Cart & Checkout: Users can add items to cart, review their order, and submit it with contact details (email/phone) for pickup coordination.
Order History: Logged-in users can view past orders for reference.
Responsive Design: Mobile-friendly layout with hamburger menu and adaptive image stacking.
Admin-Friendly Backend: Stakeholder can update product info (name, price, image) directly in the database — changes reflect instantly on the site.
Confirmation Flow: Double-confirmation on checkout prevents accidental orders.

Tech Stack
Frontend: HTML, CSS (responsive design), JavaScript
Backend: PHP (sessions, forms, database queries)
Database: MySQL
Tools: XAMPP (local server), Visual Studio Code

Project Structure
├── index.php               # Homepage

├── shop.php                # Product listing (popular items)

├── products.php            # Category-based product display

├── product-details.php     # Individual product pages

├── cart.php                # View and manage cart

├── checkout.php            # Submit order with contact info

├── order-history.php       # View past orders

├── login.php & signup.php  # User authentication

├── db_connection.php       # Database connection script

└── assets/
    ├── css/
    ├── images/
    └── js/
    
Acknowledgements
Thanks to the owner of The Meat Room for being an engaged stakeholder and providing real-world feedback. While the site won’t be used as the official platform (due to lack of payment features), he praised its functionality, ease of use, and potential.
