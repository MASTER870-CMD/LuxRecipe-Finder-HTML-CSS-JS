# Recipe Finder Web Application

## Short Description

This is a web application that allows users to search for recipes using the MealDB API. Users can search for recipes by keyword, view recipe details, and save favorite recipes to a local storage. The application is built with HTML, CSS, and JavaScript, and uses Bootstrap for styling and Font Awesome for icons.

## Features

*   **Recipe Search:** Allows users to search for recipes by ingredient or dish name using the MealDB API.
*   **Recipe Display:** Displays search results with recipe images and titles.
*   **Recipe Details:** Enables users to view detailed information about a recipe, including ingredients and instructions.
*   **Favorites:** Allows users to save and manage a list of favorite recipes using local storage.
*   **Responsive Design:** Provides a user-friendly experience on various screen sizes.
*   **Loading indicator:** Shows a visual cue while recipes are being fetched.

## Requirements

*   Web browser (Chrome, Firefox, Safari, etc.)
*   Internet connection (for searching recipes from the MealDB API)

## Installation

No installation is required. Simply open the `index.html` file in a web browser.

## Usage

1.  **Search for Recipes:** Enter a keyword (e.g., "chicken", "pasta") in the search input field and click the "Search" button or press Enter.
2.  **View Recipe Results:** The search results will be displayed with recipe images and titles.
3.  **View Recipe Details:** Click on a recipe card to view detailed information, including ingredients and instructions.
4.  **Add/Remove Favorites:** Click the "Add to Favorites" button on a recipe detail page to save it to your favorites list. Clicking the same button on a favorite recipe will remove it.
5.  **View Favorites:** Navigate to the "Favorites" section using the navigation link to see your saved recipes.

## File Structure

```
recipe-finder-app/
├── index.html    # Main HTML file
├── styles.css    # CSS stylesheet
├── script.js     # JavaScript file
└── README.md     # Documentation
```

*   `index.html`: The main HTML file containing the structure of the web page. Includes links to Bootstrap CSS, custom CSS, and Font Awesome.
*   `styles.css`: The CSS file containing custom styles for the web application. Includes custom variables for colors and fonts.
*   `script.js`: The JavaScript file containing the logic for fetching recipes, displaying results, and managing favorites.
*   `README.md`: This file, providing information and instructions for the project.

## Testing

To test the application:

1.  Open `index.html` in a web browser.
2.  Use the search functionality to find recipes.
3.  Verify that recipe results are displayed correctly.
4.  Click on a recipe to view details.
5.  Add and remove recipes from the favorites list.
6.  Verify that favorites are saved and displayed correctly.
7.  Test the application on different screen sizes to ensure responsiveness.
8.  Make sure no errors appear in the browser's console.

## Configuration

*   **API URL:** The `API_URL` variable in `script.js` is set to the MealDB API endpoint (`https://www.themealdb.com/api/json/v1/1/`).  This should not need to be changed unless the API changes.
*   **Local Storage Key:** The key 'recipeFavorites' is used to store the favorite recipes in local storage.

## Contributing

Contributions are welcome! To contribute to the project:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with descriptive messages.
4.  Push your changes to your forked repository.
5.  Submit a pull request to the main repository.

## License

This project is open source and available under the [MIT License](LICENSE).

## Improvements

*   **Enhanced UI/UX:** Improve the user interface and user experience with better design and interactions.
*   **Advanced Search:** Implement advanced search options, such as filtering by cuisine, dietary restrictions, etc.
*   **Error Handling:** Implement more robust error handling for API requests and user input.
*   **Caching:** Implement caching to improve performance and reduce API requests.
*   **User Accounts:** Add user account functionality to allow users to save favorites and create their own recipes.
*   **Recipe Submission:** Allow users to submit their own recipes to the application.
*   **More Detailed Recipe Information:** Add nutritional information or other recipe details.