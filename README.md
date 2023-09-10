# Libre Type - Typing Speed Checker

## Introduction

Libre Type is a web-based typing speed checker application. It provides a platform for users to test and improve their typing skills by typing a randomly generated paragraph while measuring their typing speed in words per minute (WPM).

## HTML Structure

### Document Type Declaration
```HTML
<!DOCTYPE html>
```
- This line specifies that the document is an HTML5 document.
### Language Declaration

```HTML
<html lang="en">
```
- This declaration defines the document's language as English (en).
### Document Head
```HTML
<head>
    <!-- Meta Tags -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Libre Type</title>

    <!-- Favicon Links -->
    <link rel="icon" href="LibreIcon.png" type="image/png">
    <link rel="shortcut icon" href="LibreIcon.png" type="image/png">
    
    <!-- Internal Styles -->
    <style>
        <!-- CSS styles go here -->
    </style>
</head>
```
- The `<head>` section contains meta tags for character set and viewport settings, as well as links to favicon images and internal CSS styles.
## CSS Styles

- The provided CSS styles define the visual appearance of the Libre Type application. These styles include settings for dark mode, the navbar, input box, keyboard layout, and more.
## Document Body
```HTML
<body>
    <!-- Navbar -->
    <!-- Input Text Box -->
    <!-- Display WPM -->
    <!-- Paragraph Content -->
    <!-- Keyboard Buttons -->
    
    <!-- JavaScript Code -->
    <script>
        <!-- JavaScript code for interaction -->
    </script>
</body>
```
- The `<body>` section contains the application's user interface elements and JavaScript code for interactivity.
## User Interface Elements

- The user interface elements include:
    - Navbar: A navigation bar with a logo and buttons.
    - Input Text Box: A box for users to type the provided paragraph.
    - Display WPM: A section to display the typing speed in words per minute.
    - Paragraph Content: The randomly generated paragraph for typing practice.
    - Keyboard Buttons: Buttons representing the QWERTY keyboard layout.

## JavaScript Interaction

- The provided JavaScript code adds interactivity to the application, including:
    - Simulating button clicks when corresponding keys are pressed.
    - Preventing default spacebar behavior when not in the input box.
    - Generating random paragraphs for typing practice.
    - Calculating and displaying typing speed in WPM.
    - Highlighting incorrectly typed words in red.

## Conclusion

Libre Type is a web-based typing speed checker application that provides users with an interactive platform to practice typing and improve their typing speed. Users can type a randomly generated paragraph and receive feedback on their typing performance in terms of words per minute (WPM). The application also includes dark mode styles and a visually appealing user interface.
