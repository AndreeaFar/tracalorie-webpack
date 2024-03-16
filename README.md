# Track Calories Application
 Monitor your daily calorie intake, track meals, and record workouts efficiently with an user-friendly interface and interactive elements for adding, removing, and filtering meals and workouts.

## App functionalities
 - Users have the flexibility to customize their calorie limits and reset the application to its default state, enabling a fresh start when needed.
 - User data, including meal and workout logs, are stored locally, ensuring accessibility across sessions without data loss.
 - Responsiveness across all devices
 - Add, remove, filter meals and workouts

### Application structure (OOP)
I have created 5 JavaScript classes and used them as JS Modules, following SOLID and DRY design patterns.
 - CalorieTracker: responsible for tracking the calories
 - Meal: responsible for adding / removing meals
 - Workout: responsible for adding / removing workouts
 - Storage: responsible for updating the local storage with the user's data
 - App: this is the app initializer, responsible for the event listeners

### Included the following Webpack features:
 - HTML Webpack Plugin
 - CSS Minify Extract Plugin
 - Webpack DevServer Plugin
 - Babel Loader
 - Css Loader

### Technologies Used
  - JavaScript
  - Webpack
  - HTML
  - Bootstrap

### How to run the app
 - Clone the repo
 - Open a terminal window in the cloned folder
 - Run the command ``` npm install ```
 - Run the command ``` npm run dev ```
 - Open htpp://localhost:3000
