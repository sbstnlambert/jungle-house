# La Maison Jungle - React Plant Shop

## Summary

"La Maison Jungle" is a React-based web application that simulates a plant shop, allowing users to explore a variety of plants, add them to their cart, and manage their purchases. This documentation provides an overview of the project structure, details about each React component, and its main features.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
- [Components](#components)
  - [1. App.js](#1-appjs)
  - [2. Banner.js](#2-bannerjs)
  - [3. CareScale.js](#3-carescalejs)
  - [4. Cart.js](#4-cartjs)
  - [5. Categories.js](#5-categoriesjs)
  - [6. PlantItem.js](#6-plantitemjs)
  - [7. ShoppingList.js](#7-shoppinglistjs)
- [Functionality](#functionality)
- [Upcoming Features](#upcoming-features)
- [Acknowledgements](#Acknowledgements)

## Overview

The project is organized into various components, each serving a specific purpose in creating an interactive plant shopping experience. Users can explore plants, add them to the cart, and manage their purchases seamlessly.

## Getting Started

This project is designed for learning purposes. To explore the project, follow these steps:

1. Clone the repository.
2. Navigate to the `/src` directory.
3. Run the application using your preferred React development environment.

## Components

### 1. `App.js`

The main application component that renders the banner, shopping cart, shopping list, and footer.

### 2. `Banner.js`

Displays the banner with the application logo and title.

### 3. `CareScale.js`

A reusable component representing care scales for light and water requirements. Clicking on it provides information about the care needs of a plant.

### 4. `Cart.js`

Manages the shopping cart, allowing users to view added items, calculate the total, and reset the cart.

### 5. `Categories.js`

Enables users to filter plants by categories, providing a dropdown menu and a reset button.

### 6. `PlantItem.js`

Displays an individual plant item with its image, name, price, and care scales. Users can click on the item to add it to the cart.

### 7. `ShoppingList.js`

Generates the list of plants based on selected categories, allowing users to add plants to the cart.

## Functionality

- Display a list of plants on the homepage.
- Filter the plant list based on plant categories.
- Open and close the shopping cart menu.
- Add plants to the shopping cart.
- Calculate the total price of items in the cart.
- Reset the shopping cart.

## Upcoming Features

As the project evolves, the following features are planned:

1. **Create a visual identity:** Develop a consistent visual design and branding for a more engaging user experience.
2. **Optimize the UI:** Enhance the user interface for improved aesthetics and usability.
3. **Integrate external plant data:** Utilize external APIs such as [Trefle](https://trefle.io/) or [Perenual](https://www.perenual.com/) to fetch comprehensive plant information dynamically using `useEffect`.
4. **Implement service files:** Integrate service files to enhance codebase architecture and maintainability.

## Acknowledgements

The project was developed with insights gained from a React course on [Openclassrooms](https://openclassrooms.com/fr/courses/7008001-debutez-avec-react). This section acknowledges the contributions and inspiration received from the course.

Feel free to explore and enhance the project! 
