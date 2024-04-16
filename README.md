# Calorie Counter Application

This repository contains a simple calorie counter application implemented using HTML, CSS, and JavaScript. The application allows users to set a daily calorie budget and track their calorie intake throughout the day by adding entries for breakfast, lunch, dinner, snacks, and exercise.

## Deployment

The project is deployed on [Netlify](https://calorie-counter-validation.netlify.app/).

## Functionality

The application provides the following functionality:

- **Add Entry**: Users can add entries for food consumption (breakfast, lunch, dinner, snacks) or exercise. Each entry includes a name and the number of calories consumed or burned.
- **Calculate Remaining Calories**: Upon submitting the form, the application calculates the remaining calories based on the user's budget and the calories consumed and burned. It displays the remaining calories along with a summary of the budgeted, consumed, and burned calories.
- **Clear**: Users can clear all entries and reset the form.

## How to Use

1. **Set Daily Calorie Budget**:

   - Enter your daily calorie budget in the "Budget" input field.
   - This represents the maximum number of calories you aim to consume in a day.

2. **Add Entries**:

   - Select the appropriate option from the dropdown menu (Breakfast, Lunch, Dinner, Snacks, Exercise).
   - Enter the name of the food item or exercise in the corresponding text field.
   - Enter the number of calories consumed or burned in the adjacent text field.
   - Click the "Add Entry" button to add the entry to the list.

3. **Calculate Remaining Calories**:

   - Once you have added all your entries, click the "Calculate Remaining Calories" button.
   - The application will calculate the remaining calories based on your budget and the calories consumed and burned.
   - It will display the remaining calories along with a summary of the budgeted, consumed, and burned calories.

4. **Clear Entries**:

   - To start over or clear all entries, click the "Clear" button.
   - This will reset the form and clear all entries.

5. **View Results**:
   - The application will display the remaining calories and a summary of the calorie budget, consumed calories, and burned calories.
   - If there's a surplus, it indicates you have consumed fewer calories than your budget.
   - If there's a deficit, it indicates you have consumed more calories than your budget.

## Technologies Used

- **HTML**: Markup language used for structuring the web page and defining its content.
- **CSS**: Stylesheet language used for styling the appearance of the web page.
- **JavaScript**: Programming language used for implementing interactive behavior and functionality.

## Coding Approach

The application follows a structured approach, separating the HTML, CSS, and JavaScript code into different files. Event listeners are used to handle user interactions such as adding entries and calculating remaining calories. The code also includes error handling to ensure valid input from the user.
