# Green Galores

**Green Galores** is a React-based e-commerce application that allows users to browse and manage a selection of plants. The application includes features for viewing product details, managing a shopping cart, and handling user authentication.

## Key Features

- **Product Browsing**: View and explore a variety of plant categories and products.
- **Shopping Cart**: Add, update, and remove items from the cart. See the total amount and checkout.
- **User Authentication**: Register, log in, and manage reviews for authenticated users.
- **Dynamic UI**: Responsive design with smooth transitions between product listings and cart views.

## Technologies Used

- **Frontend**: React, Redux, CSS
- **State Management**: Redux for managing cart state and user authentication.
- **Routing**: React Router for navigation and page transitions.

## Usage

- **Homepage**:  
  Displays a welcoming message and a "Get Started" button to access the product list.

- **Product List**:  
  Browse through different categories of plants, view details, and add items to your cart.

- **Shopping Cart**:  
  Manage cart items, view total amount, and proceed to checkout.

- **User Authentication**:  
  Register a new user and log in to manage book reviews.

## Code Overview

### Components

- **`App.js`**:  
  Main component that manages the application state and routing.

- **`ProductList.js`**:  
  Displays the list of plants and handles adding items to the cart.

- **`CartItem.js`**:  
  Manages cart items, including updating quantities and removing items.

- **`AboutUs.js`**:  
  Provides information about the application.

### Redux

- **`CartSlice.js`**:  
  Contains Redux slices for managing cart items, including actions and reducers.

- **`AuthSlice.js`**:  
  Handles user authentication, including registration and login.

### Styles

- **`CartItem.css`**:  
  Styles for the shopping cart.

- **`App.css`**:  
  General styles for the application, including landing page and product list.


