# Paradise Nursery - E-Plant Shopping

This project was forked from IBM's e-commerce template and expanded with additional features and Redux integration.

## Features

### Navigation

-   Responsive navigation bar with the Paradise Nursery branding
-   Easy access to product listings and shopping cart
-   Seamless transition between different sections of the application

### Product Listing

-   Plants organized by categories including:
    -   Air Purifying Plants
    -   Aromatic Fragrant Plants
    -   Insect Repellent Plants
    -   Medicinal Plants
    -   Low Maintenance Plants
-   Individual plant cards featuring:
    -   High-quality plant images
    -   Plant names and descriptions
    -   Pricing information
    -   Add to Cart functionality

### Shopping Cart

-   Comprehensive cart management system
-   Item cards with plant thumbnails and details
-   Quantity adjustment functionality
-   Unit and total price calculations
-   Remove item capability
-   Continue Shopping and Checkout options

## Technologies Used

### React

-   **Function Components**: Modern component architecture for better code organization and reusability
-   **Props**: Efficient data passing between components
-   **Conditional Rendering**: Dynamic UI updates based on state and user interactions
-   **Event Handling**: Responsive user interactions with onClick events

### React Hooks

-   **useState**: Local state management for UI controls and component behavior
-   **useEffect**: Side effect management for component lifecycle events
-   **Custom Hooks**: Abstracted logic for cleaner component structure

### Redux

-   **Store**: Centralized state management for the entire application
-   **Actions**: Clear, predictable state changes with:
    -   `initializeCart`: Set up initial cart state
    -   `addItem`: Add new items to cart
    -   `updateQuantity`: Adjust item quantities
    -   `removeItem`: Remove items from cart
-   **Reducers**: Functional state updates maintaining immutability
-   **Selectors**: Efficient state access via `useSelector`
-   **useDispatch**: Action triggering throughout the application

### CSS

-   Custom styling for responsive design
-   Flexbox layout for dynamic arrangement of content
-   Component-specific CSS for modular styling

### Local Storage

-   Cart persistence between sessions
-   User preference preservation

## Getting Started

### Prerequisites

-   Node.js (v14 or later)
-   npm (v6 or later)

### Installation

1. Clone the repository

```
git clone git@github.com:SawZiDunn/e-plantShopping.git
cd e-plantShopping
```

2. Install dependencies

```
npm install
```

3. Start the development server

```
npm start
```

4. Open your browser and navigate to `http://localhost:5173`

## Future Enhancements

-   User authentication and profiles
-   Order history tracking
-   Plant care guides
-   Wishlist functionality
-   Search and filter options
