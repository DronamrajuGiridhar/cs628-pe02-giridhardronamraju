# Input

The application accepts user interaction through a dropdown menu and mouse clicks. The user selects a movie genre from the dropdown list, which contains all available genres along with an "All Genres" option. The user can also click on any movie card displayed on the screen. These actions serve as the input for the application and determine how the movie list is displayed and what information is presented to the user.

# Process

The application is built using React functional components and the useState hook. A predefined array of movie objects stores the title, genre, and release year of each movie. When the user selects a genre, the selected value is stored in the component state. The application filters the movie array based on the selected genre and dynamically re-renders the matching movie cards using JSX. When a movie card is clicked, an event handler displays an alert containing the selected movie's title.

# Output

The application displays a responsive list of movie cards showing each movie's title, genre, and release year. If a specific genre is selected, only movies belonging to that genre are displayed. Selecting "All Genres" restores the complete movie list. Clicking on any movie card generates a pop-up alert displaying the movie title, providing immediate feedback to the user.