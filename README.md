⚠️ Dismiss AI-generated application

# 🍳 Cooked Weight Calculator

A simple, modern, and efficient single-file web application to calculate the cooked weight of a product based on its initial uncooked and cooked weights, and a new target uncooked quantity.

## Description

This web application helps users determine the expected cooked weight of a food item when the cooking yield (or loss/gain) is known from a sample. Users input a reference uncooked weight and its corresponding cooked weight. Then, they can input any new uncooked weight to calculate its estimated cooked weight based on this reference ratio.

The application is designed to be user-friendly, responsive for use on both desktop and mobile devices, and features quick select buttons for common weight inputs.

## Features

* **Dynamic Cooked Weight Calculation**: Calculates the cooked weight based on a user-defined ratio.
* **Three Main Inputs**:
    * Initial Uncooked Weight (base reference)
    * Resulting Cooked Weight (base reference)
    * New Uncooked Weight (for calculation)
* **Quick Select Preset Buttons**: Convenient preset buttons (150g, 180g, 280g, 300g, 330g) for all three input fields, allowing for faster data entry.
* **Responsive Design**: Adapts to different screen sizes, ensuring usability on desktops, tablets, and smartphones.
* **Modern UI**: Clean and intuitive interface for a pleasant user experience.
* **Input Validation**: Basic validation to ensure inputs are numerical and logical (e.g., initial uncooked weight > 0).
* **Error Messaging**: Clear error messages for invalid inputs.
* **Single File Application**: Entirely self-contained in a single HTML file for easy portability and deployment.

## How to Use

1.  **Download the File**:
    * Save the provided HTML code as a single `.html` file (e.g., `cook_calculator.html`).

2.  **Open in Browser**:
    * Open the saved `cook_calculator.html` file in any modern web browser (like Chrome, Firefox, Safari, Edge).

3.  **Input Base Product Information**:
    * In the "Base Product Information" section:
        * Enter the **Initial Uncooked Weight (g)** of your reference product (e.g., 150).
        * Enter the **Resulting Cooked Weight (g)** for that same reference product after cooking (e.g., 300).
    * You can type the values directly or use the preset buttons (150, 180, 280, 300, 330) below each input field.

4.  **Input New Quantity for Calculation**:
    * In the "Calculate for New Quantity" section:
        * Enter the **New Uncooked Weight (g)** for which you want to calculate the cooked weight (e.g., 100).
    * Again, you can type the value or use the preset buttons.

5.  **Calculate**:
    * Click the **"Calculate Cooked Weight"** button.

6.  **View Result**:
    * The calculated cooked weight will be displayed in the output section below the button.
    * If there are any issues with your input (e.g., non-numeric values, missing fields), an error message will be shown.

## Technology Stack

* **HTML5**: For the structure of the application.
* **CSS3**: For styling and responsive design.
* **JavaScript (ES6+)**: For the calculation logic, DOM manipulation, and event handling.
    * All code (HTML, CSS, JavaScript) is contained within a single `.html` file.

## File Structure

The entire application is contained in a single HTML file.