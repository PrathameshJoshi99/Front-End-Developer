Milkybar World Map - Front-end Project
This is a simple front-end project based on the provided design in Figma. It includes several functionalities to interact with the UI elements.

Table of Contents
Project Overview
Functionalities
Project Structure
Getting Started
Known Limitations
License
Project Overview
This project aims to replicate the design provided in the Figma link and implement the following functionalities:

Users can tap on the fallback image placeholder to open the camera.
Users can click an image to convert it into base64 format, save it in local storage, and replace the fallback image with the clicked image.
Users can edit the name value.
There is validation in the name input field that allows only letters, and the maximum allowed characters are 30.
The entered name value is saved in local storage.
Continents images are separate images (not included in this basic example).
Download functionality is provided for the modified image.
The "Home" button is ignored.
Project Structure
The project includes the following files:

index.html: The HTML structure of the project.
styles.css: CSS styles to define the appearance of the project.
script.js: JavaScript code to implement the described functionalities.
Getting Started
To run the project locally, follow these steps:

Clone the repository to your local machine:

bash

git clone <repository-url>
Open the index.html file in your web browser.

Interact with the UI to test the implemented functionalities.

Known Limitations
The project provides a basic example to demonstrate the described functionalities but does not include separate continent images as in the Figma design. You will need to replace the fallback_image.jpg with actual continent images as per your design.
This project does not include a server backend or database for storing user data, so data is stored in local storage, which is not suitable for production use.
