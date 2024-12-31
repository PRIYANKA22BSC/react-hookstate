# Hook State Task for Shoe Products

Live Demo-https://react-hookstate.vercel.app/

This project demonstrates the use of React hooks to manage the state of a shoe product list with the functionality to add products to a cart, and adjust the quantity of each product in the cart.

## Features

1. **Product List**: Display a list of shoe products with details such as name, price, and an image.
2. **Add to Cart**: Add a product to the cart using the "Add" button.
3. **Quantity Adjustment**: 
    - Increase the quantity of a product in the cart using the "Increase" button.
    - Decrease the quantity of a product in the cart using the "Decrease" button.
4. **Dynamic State Management**: All state is managed using React's `useState` hook.
5. **Cart Management**: The cart updates dynamically, reflecting the addition and removal of products as well as quantity adjustments.

## Technologies Used

- React.js
- JavaScript (ES6+)
- CSS (for basic styling)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/shoe-cart-hooks.git
   ```
2. Navigate to the project directory:
   ```bash
   cd shoe-cart-hooks
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
5. Open your browser and navigate to `http://localhost:3000` to view the app.

## Code Structure

### `App.js`

Contains the main application component which renders the product list and cart.

### `ProductList.js`

Displays all available shoe products with an "Add to Cart" button.

### `Cart.js`

Displays products added to the cart with options to increase or decrease quantities.

### `hooks/useCart.js`

Custom hook to manage cart state.

## Components

### Product Card

- Displays product information: name, price, and image.
- Contains an "Add" button to add the product to the cart.

### Cart Item

- Displays product information in the cart.
- Contains "Increase" and "Decrease" buttons to adjust the quantity.
- Removes the product from the cart if the quantity is reduced to zero.

## Usage

1. View the list of shoe products.
2. Click "Add" to add a product to the cart.
3. Go to the cart to see the added products.
4. Use "Increase" to add more of the same product.
5. Use "Decrease" to reduce the quantity or remove the product if the quantity reaches zero.

## Example

### Adding a Product

1. Click the "Add" button on a product in the product list.
2. The product appears in the cart with a default quantity of 1.

### Adjusting Quantity

1. Navigate to the cart.
2. Use the "Increase" button to add more units of a product.
3. Use the "Decrease" button to reduce the quantity or remove the product if the quantity reaches zero.

## Contributing

Feel free to fork this repository and submit pull requests to enhance the functionality or fix issues.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
