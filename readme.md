# Take Your Gadget - Client

#### <i> "Take Your Gadget - Client" is a full-stack multivendor e-commerce project developed using the MERN stack (MongoDB, Express.js, React.js, Node.js). It provides a platform for selling gadgets from multiple vendors.</i>

## <b> Features </b>

- User registration and authentication
- Vendor registration and authentication
- User and vendor profile management
- Product listing and browsing
- Product search and filtering
- Shopping cart functionality
- Order placement and tracking
- Payment integration (e.g., Stripe)
- Vendor dashboard for managing products, orders, and inventory
- User dashboard for managing orders and profile information
- Admin panel for managing users, vendors, and site settings

## Special Features

Sure! Here's a table in Markdown format that includes the provided special features and functionality:

| Special Features       | Description                                                                              | Implementation                                                                                                               |
| ---------------------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Searching System       | Enables users to search for specific products or content within the application          | Implement search functionality using search algorithms and integrate it with the front-end and back-end                      |
| Pagination             | Breaks down content into multiple pages for easier navigation and improved performance   | Implement pagination logic to display limited results per page and provide navigation to other pages                         |
| Protected Routes       | Restricts access to certain routes or pages only to authenticated users                  | Implement authentication and authorization logic to allow access to protected routes based on user authentication status     |
| Protected API’s        | Secures access to specific APIs by requiring authentication and authorization            | Implement authentication and authorization mechanisms for API endpoints to ensure only authorized users can access them      |
| Single Payment System  | Provides a streamlined payment process for purchasing a single product or service        | Integrate a payment gateway (e.g., Stripe) to enable users to make a one-time payment for a selected product or service      |
| Cart Payment System    | Enables users to add multiple products to a cart and make a payment for the entire cart  | Implement a shopping cart functionality that allows users to add items, update quantities, and make a payment for the cart   |
| Category Filter        | Allows users to filter products or content based on specific categories                  | Implement category filtering functionality to display products or content based on user-selected categories                  |
| Product Filter         | Enables users to filter products based on specific attributes or criteria                | Implement product filtering functionality to display products based on user-selected attributes or criteria                  |
| Sort by Price          | Allows users to sort products or content based on price in ascending or descending order | Implement sorting functionality to arrange products or content based on their price, either in ascending or descending order |
| Sort by Rating         | Enables users to sort products or content based on rating or user feedback               | Implement sorting functionality to arrange products or content based on their rating or user feedback                        |
| Coupon                 | Provides a system for applying discounts or promotional offers to products or orders     | Implement coupon functionality to allow users to apply valid coupons or discount codes during the checkout process           |
| Mailing System         | Sends automated emails or notifications to users based on specific actions or events     | Integrate an email service provider (e.g., SendGrid) and implement email triggers for specific actions or events             |
| Image Uploading System | Allows users to upload images or files to the application                                | Implement an image uploading system that enables users to upload and store images or files within the application            |
| Facebook Login         | Enables users to authenticate using their Facebook credentials                           | Integrate the Facebook Login API to allow users to log in to the application using their Facebook accounts                   |
| Google Login           | Enables users to authenticate using their Google credentials                             | Integrate the Google Sign-In API to allow users to log in to the application using their Google accounts                     |

Please note that the "Implementation" column provides a brief description of how each feature can be implemented. You will need to incorporate these features into your specific project based on the chosen technologies and frameworks.

## <b> Pages </b>

Apologies for the confusion. Here's a revised table with six columns:

| Page                    | Public Routes | Private Routes for Buyer | Private Routes for Seller | Private Routes for Admin | Package & Libraries                                                                                      |
| ----------------------- | ------------- | ------------------------ | ------------------------- | ------------------------ | -------------------------------------------------------------------------------------------------------- |
| Home                    | ✅            |                          |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios, Tanstack Query, Swiper JS |
| Product                 | ✅            |                          |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Categories              | ✅            |                          |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Category Products       | ✅            |                          |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Login                   | ✅            |                          |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Registration            | ✅            |                          |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Product Details         | ✅            |                          |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Contact us              | ✅            |                          |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Terms and condition     | ✅            |                          |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Shipping policy         | ✅            |                          |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Privacy policy          | ✅            |                          |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| About us                | ✅            |                          |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Carts                   |               | ✅                       |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Payment                 |               | ✅                       |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios, Stripe                    |
| Order History           |               | ✅                       |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| User-Info               |               | ✅                       |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Track order             |               | ✅                       |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Review products         |               | ✅                       |                           |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| My products             |               |                          | ✅                        |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Add Products            |               |                          | ✅                        |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Discount and coupon     |               |                          | ✅                        |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Seller-info             |               |                          | ✅                        |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Ordered-Products        |               |                          | ✅                        |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Shipped-Products        |               |                          | ✅                        |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Delivered-Products      |               |                          | ✅                        |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Product-Selling History |               |                          | ✅                        |                          | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Manage Users            |               |                          |                           | ✅                       | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Manage orders           |               |                          |                           | ✅                       | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |
| Sales Dashboard         |               |                          |                           | ✅                       | React, React-Router-Dom, Tailwind, Daisy UI, Firebase, React-Hook-form, Axios                            |

## CSS Framework installation

install Tailwind

```bash
npm install tailwindcss postcss autoprefixer
```

init Tailwind

```bash
npx tailwindcss init
```

import following style in index.css

```bash
@import 'tailwindcss/base';
@import 'tailwindcss/components';
@import 'tailwindcss/utilities';
```

Install daisyUI:

```bash
npm i -D daisyui@latest
```

Then add daisyUI to your tailwind.config.js files:

```bash
module.exports = {
  //...
  plugins: [require("daisyui")],
}
```

## React Router Dom installation

```bash
npm install react-router-dom localforage match-sorter sort-by
```

## Firebase Installaion

```bash
npm install firebase
```
