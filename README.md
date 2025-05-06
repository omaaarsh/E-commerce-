Wearly Frontend
This is the frontend code for Wearly, a clothing e-commerce platform. Built with HTML, CSS, and JavaScript, it uses Bootstrap for responsive design. The frontend integrates with multiple backend APIs to fetch and manage data for products, categories, user accounts, cart, and wishlist, creating a dynamic shopping experience.
Code Structure

index.html: Homepage with category navigation, brand highlights, and API-driven content.
men.html: Men’s clothing category page, populated with API data.
women.html: Women’s clothing category page, updated via API calls.
kids.html: Kids & Baby clothing category page, sourced from APIs.
product.html: Product details page, dynamically loaded with API data.
cart.html: Shopping cart page, syncing with backend APIs.
login.html: User login page, posting to authentication API.
Signup.html: User registration page, sending data to backend API.
profile.html: User profile page, fetching and updating via API.
photos/: Folder for product images and media, linked to API data.
.vscode/: VS Code settings for development.

Technologies

HTML5: Page structure and layout.
CSS3: Custom styles with Bootstrap for responsiveness.
JavaScript: Handles multiple API calls (GET/POST) using fetch API for data retrieval and updates.
Bootstrap 5.3.4: Responsive grid, components, and icons.
Bootstrap Icons: Icons for wishlist (heart), cart (bag), and profile (person).

API Integration
The frontend communicates with multiple backend APIs (default at http://localhost:5107) for various functionalities:

Product APIs:
GET /api/v1/products: Fetches all products for category pages (men.html, women.html, kids.html).
GET /api/v1/products/{id}: Retrieves specific product details for product.html.


Category APIs:
GET /api/v1/categories: Loads category data for navigation and filtering.


User Account APIs:
POST /api/v1/accounts/register: Submits signup form data from Signup.html.
POST /api/v1/accounts/login: Handles login form submission from login.html.
GET /api/v1/accounts/status: Checks authentication status to update navbar (profile or login link).
GET /api/v1/accounts/profile: Fetches user data for profile.html.
POST /api/v1/accounts/logout: Logs out the user, clearing session.


Cart APIs:
GET /api/v1/cart: Retrieves cart items for cart.html.
POST /api/v1/cart/add: Adds items to the cart.
POST /api/v1/cart/remove: Removes items from the cart.


Wishlist APIs:
GET /api/v1/wishlist: Fetches wishlist items.
POST /api/v1/wishlist/add: Adds products to the wishlist.
POST /api/v1/wishlist/remove: Removes products from the wishlist.


Implementation Details:
Uses fetch API with credentials: 'include' to manage session cookies.
Handles API responses in JavaScript to dynamically update DOM elements.
Includes basic error handling (e.g., alerts for failed API calls).



Setup

Clone the repo:git clone https://github.com/omaaarsh/Wearly-Clothing-ECommerce-front-end-.git


Open index.html in a browser, or use a local server (e.g., VS Code Live Server) for API testing.
Ensure the backend APIs are running at http://localhost:5107 for full functionality.
Use browser dev tools (Network tab) to monitor API calls and responses.

Features

Responsive navbar with API-driven user status (profile or login link).
Category pages (men.html, women.html, kids.html) populated with product data from APIs.
Product details page (product.html) with dynamic API-sourced content.
Cart and wishlist pages with real-time updates via API calls.
Login/Signup forms posting data to backend APIs.
Profile page fetching user data via API.

