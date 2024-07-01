
# Turing Cafe - Reservation Portal

This project is a single-page application for managing reservations at Turing Cafe, built with React.

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Set Up](#set-up)
- [Features](#features)
- [Future Extensions](#future-extensions)
- [Screenshots](#screenshots)
- [Author](#author)

## Overview

Turing Cafe is a reservation management portal that allows users to view, create, and manage reservations. The application interacts with an API to persist reservation data and provides a seamless user experience with real-time updates.

## Technologies Used

### Languages
- JavaScript

### Frontend
- React
  - react-dom

### Testing
- Cypress
- jest-environment-jsdom-sixteen

### Build Tools
- react-scripts

### Others
- ESLint
- Browserslist
- fsevents (for filesystem events)
- Node.js (for package management and scripts)

## Set Up

To set up the project locally, follow these steps:

1. **Fork and Clone the Repository:**
   - Fork the repository to your own GitHub account.
   - Clone the forked repository to your local machine.

   ```bash
   git clone https://github.com/your-username/turing-cafe-ui.git
   cd turing-cafe-ui
   ```

2. **Install Dependencies:**
   - Run `npm install` to install all required dependencies.

   ```bash
   npm install
   ```

3. **Start the Development Server:**
   - Run `npm start` to start the React development server.

   ```bash
   npm start
   ```

4. **Run Cypress Tests:**
   - Run `npm run cypress` to start the Cypress testing server.

   ```bash
   npm run cypress
   ```

## Features

- **View Reservations:** Displays all existing reservations on page load.
- **Create Reservations:** Allows users to create new reservations through a controlled form.
- **Persist Data:** Saves new reservations to the API, ensuring data persists across page reloads.
- **Delete Reservations:** Users can cancel reservations, and the deletion persists across page reloads.

## Future Extensions

- **Error Handling:** Add error handling for form validation and network requests.
- **Menu Viewing:** Add functionality to view the cafe's menu by integrating a new API endpoint.
- **Sorting Reservations:** Implement sorting options for reservations by date.
- **Additional Tests:** Write additional tests to cover edge cases and improve test coverage.

## Screenshots

![turing-cafe-screenshot](https://user-images.githubusercontent.com/20754511/57332366-dbd59d00-70d7-11e9-9de6-967d7aca98a4.png)

Feel free to reach out with any questions or feedback!
