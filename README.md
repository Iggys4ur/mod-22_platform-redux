# Platform (via) Redux

## What I Learned From This Project

This project involved refactoring an existing e-commerce platform to utilize Redux for state management instead of React's Context API. By implementing Redux, I gained a deeper understanding of managing global state outside of the React ecosystem, which is essential for developing scalable and maintainable applications. This experience also enhanced my ability to read and interpret technical documentation independently, a critical skill for any software engineer.

## Project Overview

"Platform (via) Redux" is a refactored version of an e-commerce platform where Redux is used to manage global state. The application allows users to browse products, view product details, add items to a shopping cart, and proceed to checkout. By integrating Redux, the application's state management is more structured and efficient, providing a better user experience.

## Features

- **Redux Store**: The application uses a Redux store to manage the state, ensuring that state management is decoupled from the React ecosystem.
- **Product Browsing**: Users can browse products by categories and view detailed information for each product.
- **Shopping Cart**: Users can add and remove products from the shopping cart and view the total price.
- **Checkout Process**: Users can proceed to checkout, where they can review their cart items before completing the purchase.

## Getting Started

### Prerequisites

- Node.js installed on your machine.
- Basic understanding of React and Redux.
- Familiarity with REST APIs.

### Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/iggys4ur/platform-via-redux.git
    ```

2. Navigate to the project directory:

    ```bash
    cd platform-via-redux
    ```

3. Install the dependencies:

    ```bash
    npm install
    ```

4. Start the development server:

    ```bash
    npm start
    ```

### Deployment

The application can be deployed on any cloud platform that supports Node.js, such as Render or Heroku. Ensure you have set up the necessary environment variables and have a production build ready for deployment.

## Usage

- **Browse Products**: Navigate through different product categories and explore the available products.
- **Add to Cart**: Click on the "Add to Cart" button to include a product in your shopping cart.
- **View Cart**: Access your shopping cart to see the products added, and adjust quantities or remove items as needed.
- **Checkout**: Proceed to the checkout page to finalize your purchase.

## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **Redux**: State management library for JavaScript applications.
- **Node.js**: JavaScript runtime built on Chrome's V8 JavaScript engine.
- **Express**: Web application framework for Node.js.
- **Stripe API**: Used for processing payments.

## Lessons Learned

- **Redux Integration**: How to set up and configure Redux in a React application, including creating actions, reducers, and managing middleware.
- **Decoupling State Management**: Understanding the benefits of decoupling state management from the React components and how Redux facilitates this process.
- **Working with APIs**: Gained experience in integrating third-party services like Stripe for handling payments.

## Future Enhancements

- **Enhanced Security**: Implement OAuth for more secure user authentication.
- **Product Reviews**: Allow users to leave reviews for products to enhance the user experience.
- **Advanced Filtering**: Provide more advanced product filtering options to improve usability.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the Redux documentation and community for providing extensive resources and support.
- Special thanks to the creators of the original e-commerce platform for providing the base project for this refactor.
