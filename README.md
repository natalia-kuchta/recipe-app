# Recipe App

The Recipe App is a web application that allows users to search for recipes by meal name. 
It fetches recipe data from an external API and displays the results dynamically on the web page. 
Users can view detailed ingredients and instructions for each recipe in a popup window.

> Table of Contents

[1.File Structure](#file-structure)

[2.HTML Structure](#html-structure)

[3.JavaScript Functionality](#javascript-functionality-exaple)

[4.CSS Styling](#css-styling-exaple)

[5.Usage](#usage)

[6.External Resources](#external-resources)

[7.Notes](#notes)

## File Structure

```
.
├── index.html   Contains the HTML structure of the web page.
├── Makefile     Startup script of node js server (make up)
├── script.js    Contains the JavaScript code for API interaction and DOM manipulation.
└── style.css    Contains the CSS styles for the application.
```

External Resources: Font Awesome CDN for icons used in the app.

## HTML Structure

The HTML file defines the structure and layout of the Recipe App.

![HtmlRecipe](https://github.com/user-attachments/assets/8917fec5-2c73-4163-8da1-3f182a890a02)


## JavaScript Functionality exaple

The script.js file contains the JavaScript code for fetching and displaying recipes.

![JsRecipeApp](https://github.com/user-attachments/assets/aaca3f2f-8661-4b7e-95ac-cf7a1309bdfb)


## CSS Styling exaple

The style.css file defines the appearance of the app


![CSSRecipeApp](https://github.com/user-attachments/assets/54b2b0c1-25d3-4e88-9730-bd12ec3fe6a0)




## Usage

Search for Recipes: Enter a meal name into the search box and click "Search".

View Recipe Details: Click "View Recipe" on any recipe card to see detailed ingredients and instructions.

Close Recipe Popup: Click the "X" button in the recipe details popup to close it.

![Screenshot from 2024-08-04 12-18-17](https://github.com/user-attachments/assets/84d9b030-dc61-4a5a-bc51-1648845754c8)

## External Resources

Font Awesome: Used for the close button icon.

CDN Link: https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.9.0/css/all.min.css

## Notes

This app utilizes an external API (https://www.themealdb.com/api/) to fetch recipe data based on user input.
Ensure an active internet connection for proper functionality.
