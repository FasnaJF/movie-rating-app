# Movie Rating App 🎬

## Project Overview

The **Movie Rating App** is a dynamic web application that displays a curated list of movies with details such as name, description, genres, images, and ratings. Built with **React**, it demonstrates key concepts like rendering lists with JSX and dynamically displaying data from arrays.  

This project is perfect for practicing **React fundamentals**, including mapping data to components, handling unique keys, and displaying dynamic content in a clean, user-friendly layout.

## Features

- Display a list of movies from a predefined dataset
- Show each movie’s:
  - Name  
  - Description  
  - Image  
  - Genres  
  - Rating (as stars, out of 5)  
- Clean and organized layout  
- Optional styling with **TailwindCSS**  

## How It Works

The movie data is stored in `./data/movies.js` as an array of objects. Each movie object contains details such as `name`, `description`, `image`, `genres`, and `rating`. The app dynamically renders this data using the `map()` function in React.  

A `StarIcon` component (or simple emoji/text) is used to visually represent movie ratings.

## Technologies Used

- React  
- TailwindCSS (preinstalled for styling)  
- JavaScript (ES6+)  

## Usage

1. Clone the repository:  

```bash
git clone <repository-url>
```

2. Install dependencies:  

```bash
npm install
```

3. Start the development server:  

```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the app in action.

## Customization

- Add more movies by editing the `ALL_MOVIES.items` array in `./data/movies.js`  
- Modify styles using TailwindCSS classes to adjust layout or theme