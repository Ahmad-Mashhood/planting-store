# Paradise Nursery - e-plantShopping

Welcome to **Paradise Nursery**, a premium houseplant e-commerce application developed as a front-end React project. This repository, **e-plantShopping**, implements a fully functional shopping cart interface using React and Redux Toolkit for state management.

## Project Overview

**Paradise Nursery** is designed to provide plant lovers with a seamless, interactive shopping experience. The application consists of three main pages/views:

1. **Landing Page**:
   - Features a clean, inviting aesthetic with a welcoming nursery background.
   - Provides a brief overview/mission statement of the nursery.
   - Includes an interactive **Get Started** button to direct users to the product store.

2. **Product Listing Page**:
   - Showcases a curated collection of houseplants organized into distinct categories (e.g., *Air Purifying*, *Lush & Foliage*, and *Easy & Medicinal*).
   - Each plant card displays a thumbnail image, description, price, and an **Add to Cart** button.
   - Incorporates a sticky navigation header featuring a shopping cart icon with a badge that dynamically updates to reflect the total number of items in the cart.
   - Prevents duplicate additions by disabling the "Add to Cart" button once a product is selected.

3. **Shopping Cart Page**:
   - Lists all selected houseplants, their individual unit prices, and quantities.
   - Allows users to increase or decrease quantities or delete specific plant types from their cart.
   - Dynamically calculates and displays individual subtotals and the grand total cart amount.
   - Includes **Continue Shopping** and **Checkout** buttons (the latter triggering a "Coming Soon!" alert).

## Key Features

* **Redux Toolkit Integration**: Manages cart state globally (handling item additions, quantity modifications, removals, and checkout clearing).
* **Responsive Styling**: A grid layout customized with Vanilla CSS rules that adapt gracefully across desktop and mobile screen sizes.
* **UX Enhancements**: Visual cues such as disabled button states, custom icon overlays, and intuitive quantity controls.

## Technologies Used

* **Frontend Framework**: React (v18)
* **State Management**: Redux Toolkit & React-Redux
* **Build Tool**: Vite
* **Icons**: Inline SVG / standard assets
* **Deployment**: GitHub Pages