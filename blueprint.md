
# Blueprint: Lotto Number Generator

## Overview

This project is a web-based lottery number generator. It provides users with a set of randomly generated numbers for lottery draws, along with a history of previously generated sets. The application is built using modern web technologies, including HTML5, CSS3, and JavaScript (ES Modules), and features a clean, responsive, and visually appealing design.

## Project Structure & Design

### **HTML (`index.html`)**

*   **Header:** Contains the main title of the application.
*   **Main Content:**
    *   A section to display the currently generated lottery numbers.
    *   A button to trigger the generation of new numbers.
*   **Aside/History:** A section to display a history of previously generated number sets.
*   **Footer:** Contains basic information about the application.

### **CSS (`style.css`)**

*   **Layout:** A centered, single-column layout that is responsive to different screen sizes.
*   **Theme:**
    *   **Color Palette:** A modern and energetic color scheme with gradients.
    *   **Typography:** Clear and readable fonts with good hierarchy.
    *   **Effects:** Subtle shadows and animations to enhance the user experience.
*   **Components:**
    *   **Number Display:** Each number is displayed in a styled circle (a "lotto ball").
    *   **Button:** A prominent button with a clear call-to-action.
    *   **History List:** A styled list to show past results.

### **JavaScript (`main.js`)**

*   **ES Modules:** The code is organized into modules for better maintainability.
*   **`lotto-ball` Web Component:**
    *   A custom element (`<lotto-ball>`) is defined to represent each lottery number.
    *   It uses a Shadow DOM to encapsulate its style and structure.
    *   It accepts a `number` attribute to display the corresponding number.
*   **Main Application Logic:**
    *   An event listener on the "Generate" button triggers the number generation process.
    *   A function generates a set of 6 unique random numbers between 1 and 45.
    *   The generated numbers are displayed using the `lotto-ball` component.
    *   The set of numbers is added to a history array, which is then rendered in the history section.

## Current Task: Initial Implementation

1.  **Update `index.html`:**
    *   Set up the basic structure with a title, a container for the lotto balls, a generate button, and a history section.
2.  **Update `style.css`:**
    *   Apply a modern and visually appealing style to the page, including a background texture, color palette, and styles for the components.
3.  **Update `main.js`:**
    *   Create the `lotto-ball` custom element.
    *   Implement the logic to generate and display the lottery numbers when the button is clicked.
    *   Implement the logic to track and display the history of generated numbers.
