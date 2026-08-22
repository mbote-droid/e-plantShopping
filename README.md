# e-plantShopping – Online Plant Store

Welcome to e-plantShopping! This is a frontend React application built for plant lovers to browse, select, and buy various types of house plants online.

## Features

* **Interactive Plant Catalog**: Browse plants with clear images, pricing, and quick-add actions.
* **Shopping Cart**: Real-time cart updates to add items, change quantities, or remove plants.
* **Responsive Layout**: Designed to look great on desktop, tablet, and mobile browsers.
* **State Management**: Built using Redux to handle cart actions and state changes seamlessly.

## Project Structure

```text
├── public/              # Static public assets
│   └── vite.svg         # Vite logo icon
├── src/
│   ├── assets/          # Project images and graphics
│   │   └── react.svg
│   ├── AboutUs.css      # Styling for the about section
│   ├── AboutUs.jsx      # About page component
│   ├── App.css          # Global root styling overrides
│   ├── App.jsx          # Main application core layout
│   ├── CartItem.css     # Styling for individual cart items
│   ├── CartItem.jsx     # Shopping cart item and summary component
│   ├── CartSlice.jsx    # Redux toolkit slice managing cart state
│   ├── ProductList.css  # Gallery page styling
│   ├── ProductList.jsx  # Main store catalog display grid
│   ├── index.css        # Main baseline CSS entry point
│   ├── main.jsx         # React application entry point
│   └── store.js         # Redux store configuration setup
├── .eslintrc.cjs        # Linter rules configuration
├── .gitignore           # Ignored files for version control
├── LICENSE              # Project license file
├── README.md            # This documentation file
├── index.html           # Main HTML shell template
├── package-lock.json    # Locked dependency tree record
├── package.json         # Project manifests and build scripts
└── vite.config.js       # Vite bundler server configurations
```

## Getting Started

Follow these steps to run the store locally on your computer.

### Prerequisites

Make sure you have Node.js installed on your machine.

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/mbote-droid/e-plantShopping.git
   ```

2. Open the project folder:
   ```bash
   cd e-plantShopping
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

### Running the App

To start the development server:
```bash
npm run dev
```

Open your browser to the local address shown in your terminal (usually `http://localhost:4173`) to view the application.

### Building for Production

To compile the application into static files ready for deployment:
```bash
npm run build
```
