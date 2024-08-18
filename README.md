# usePopcorn

This project is a React application designed to help users manage and rate movies they have watched. The app includes features such as searching for movies, viewing details about movies, and rating them using a custom star rating component.

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

#### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

#### `npm run eject`

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

## Project Structure

- `index.js`: The entry point for the React application, where the root component is rendered.
- `App.js`: The main component that includes logic for displaying movies, searching, and showing details about watched movies.
- `StarRating.js`: A reusable component for displaying star ratings, with customizable options for color, size, and messages.
- `index.css`: Contains all the styles used in the application to ensure the app is visually appealing and responsive.

## Project Overview

The application consists of features that allow users to:

1. **Search for Movies**: Users can search for movies by title.
2. **View Movie Details**: Users can view details about movies such as title, year, and poster image.
3. **Rate Movies**: Users can rate movies using a star rating system.

### Components

- **App.js**: The main application logic, including rendering movie lists, showing summaries, and handling user interactions.
- **StarRating.js**: A customizable star rating component used throughout the app to rate movies.
- **NavBar.js**: Handles navigation elements such as the search bar and logo.
- **MovieList.js**: Displays a list of movies retrieved from an API or static data.
- **WatchedSummary.js**: Shows a summary of the movies the user has watched, including average ratings and total runtime.
- **index.css**: Defines the styling for the application, including color schemes, layout, and responsive design elements.

### Styling

- **index.css**: Provides the necessary styles for the application, including layout design, color schemes, and responsive elements to ensure a good user experience across devices.

### Dependencies

- `react`: The core library for building the user interface.
- `react-dom`: Handles the rendering of React components.

### Author

- **Olha Chernysh**
