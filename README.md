# calorieCounterApp
Created with CodeSandbox
The Calorie Counter is a web-based application designed to help users track their daily calorie intake and expenditure. It allows users to input their daily calorie budget, log meals (breakfast, lunch, dinner, snacks), and record exercise activities. The application calculates the remaining calories based on the inputs and provides a clear summary of the user's calorie status.

This project is built using HTML, CSS, and JavaScript, making it lightweight, fast, and easy to use.

Features
Calorie Budget Input: Users can set their daily calorie budget.

Meal Logging: Log calories for breakfast, lunch, dinner, and snacks.

Exercise Logging: Record calories burned through exercise.

Dynamic Entry Addition: Add multiple entries for meals and exercises.

Calorie Calculation: Automatically calculates remaining calories.

Clear Form: Reset the form to start over.

Technologies Used
HTML5: For structuring the application.

CSS3: For styling and responsive design.

JavaScript: For dynamic functionality and calculations.

Vanilla JS: No external libraries or frameworks are used, ensuring lightweight performance.

Folder Structure
Copy
calorie-counter/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet for the application
├── script.js           # JavaScript for functionality
Installation
To run this project locally, follow these steps:

Clone the Repository:

bash
Copy
git clone https://github.com/your-username/calorie-counter.git
cd calorie-counter
Open the Project:

Open the index.html file in your preferred browser.

No Server Required:

This project runs entirely in the browser, so no additional setup is required.

Usage
Set Your Budget:

Enter your daily calorie budget in the "Budget" field.

Add Entries:

Use the dropdown menu to select a category (Breakfast, Lunch, Dinner, Snacks, Exercise).

Click "Add Entry" to add a new input field for that category.

Enter the name and calorie value for each entry.

Calculate Calories:

Click "Calculate Remaining Calories" to see your calorie status.

The application will display:

Remaining calories (deficit or surplus).

Total calories budgeted.

Total calories consumed.

Total calories burned.

Clear Form:

Click "Clear" to reset the form and start over.

Code Overview
HTML (index.html)
The structure of the application is defined here.

Includes form fields for budget, meals, and exercise.

Uses <fieldset> and <legend> for grouping inputs.

Dynamically adds input fields using JavaScript.

CSS (styles.css)
Provides a clean and responsive design.

Uses modern CSS features like flexbox and box-shadow.

Ensures the application looks great on all devices.

JavaScript (script.js)
Handles dynamic addition of input fields.

Validates user inputs to ensure they are numeric.

Calculates the remaining calories based on user inputs.

Displays the results in a user-friendly format.

Key Functions in script.js
addEntry():

Dynamically adds input fields for meals and exercise.

calculateCalories(e):

Calculates the total calories consumed and burned.

Computes the remaining calories and displays the result.

getCaloriesFromInputs(list):

Sums up the calorie values from a list of input fields.

clearForm():

Resets the form and clears all inputs.

Contributing
Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

Fork the repository.

Create a new branch for your feature or bugfix.

Commit your changes.

Push your branch and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Inspired by the need for a simple, lightweight calorie-tracking tool.

Built as a learning project for modern web development techniques.

