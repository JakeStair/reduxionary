# Reduxionary

This project refactors an e-commerce platform to use Redux for state management instead of the Context API. The platform retains all original functionality while improving global state management outside of the React ecosystem.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Collaborators](#collaborators)
- [Screenshots](#screenshots)
- [Deployed Application](#deployed-application)
- [License](#license)

## Description

This e-commerce application allows users to browse products, filter by category, view product details, and manage a shopping cart. Payments are processed using the Stripe API with test credentials. Redux is implemented to handle the app's global state, providing improved scalability and maintainability.

The app is fully functional, deployed, and follows modern React and Redux practices.

## Features

- User registration and login functionality
- Product browsing and category filtering
- Detailed product view
- Add/remove items from the shopping cart
- Checkout with Stripe API integration
- State management with Redux
- Mobile-responsive design

## Technologies Used

- React  
- Redux  
- React-Redux  
- Redux Toolkit  
- Stripe API  
- Node.js  
- Express.js  
- MongoDB  
- CSS/Bootstrap  

## Installation

1. Clone the repository:  
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project folder:  
   ```bash
   cd e-commerce-platform
   ```
3. Install dependencies for both client and server:  
   ```bash
   npm install
   cd client
   npm install
   cd ..
   ```
4. Create a `.env` file in the root folder with the following variables:  
   ```
   STRIPE_SECRET_KEY=<Your_Stripe_Secret_Key>
   MONGO_URI=<Your_MongoDB_URI>
   ```
5. Start the development server:  
   ```bash
   npm run dev
   ```

## Usage

1. Navigate to the deployed application or start the local development server.  
2. Register an account or log in with existing credentials.  
3. Browse products, filter categories, and view product details.  
4. Add items to the cart, adjust quantities, and proceed to checkout.  
5. Use Stripe's test credit card credentials to simulate a payment:  
   ```
   Card Number: 4242 4242 4242 4242  
   Expiry: Any future date  
   CVC: Any 3 digits  
   ```

## Collaborators

- **Martha Watson**  
  GitHub: [Elementary-my-dear-Watson](https://github.com/Elementary-my-dear-Watson)

- **An Le**  
  GitHub: [An-109](https://github.com/An-109)

## Screenshots

### Example Screenshots

![Home Page](https://i.imgur.com/9gRNGiY.png)
![Cart Checkout](https://i.imgur.com/tNs7V3G.png)

## Deployed Application

Live URL: [Shop-Shop](<https://reduxionary.onrender.com/>) 
GitHub Repository: [Reduxionary](<https://github.com/JakeStair/reduxionary>)

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

