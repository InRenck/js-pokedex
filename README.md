# Trilha JS Developer - Pokedex

## Description
This project is a simple Pokedex web application that allows users to explore a list of Pokemon. It leverages the PokéAPI to fetch Pokemon data and display it in a visually appealing manner. The project is built using HTML, CSS, and JavaScript.

## Table of Contents
Project Structure
Usage
CSS Styles
License

## Project Structure
The project structure includes:

HTML file (index.html):

Contains the structure of the web page, including the Pokedex title, Pokemon list, and a "Load More" button.
CSS files (in /assets/css/):

global.css: Normalizes CSS styles using the Normalize library and sets the global styles.
pokedex.css: Defines styles specific to the Pokedex, including grid layout and Pokemon card styles.
JavaScript files (in /assets/js/):

pokemon-model.js: Defines the Pokemon class to model Pokemon objects.
poke-api.js: Contains functions to interact with the PokéAPI and fetch Pokemon data.
main.js: Implements the main logic for loading and displaying Pokemon data.
Fonts:

The project uses the Roboto font from Google Fonts.

## Usage
To use this project, follow these steps:

Clone the repository:
git clone <repository-url>
Open the index.html file in your preferred web browser.

Explore the Pokedex, view Pokemon details, and load more Pokemon using the "Load More" button.

## CSS Styles
The CSS styles are organized to create a visually appealing and responsive design. The Pokedex layout adjusts based on the screen size, providing a better user experience.

Color Classes:

Various color classes define the background color for each Pokemon type, making it visually distinguishable.
Responsive Design:

The grid layout (pokemons class) adapts to different screen sizes, with a single column for small screens and multiple columns for larger screens.
Pagination Button:

The "Load More" button is styled with a distinctive color, providing a clear call-to-action.

## License
This project is licensed under the MIT License.
