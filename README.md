# BackgroundColorChanger
Interactive web app that allows users to change a container's background color using predefined buttons or a custom color picker. Color choices are saved in local storage for persistence.

Background Color Changer
The Background Color Changer is a simple, interactive web application that allows users to dynamically change the background color of a container either by selecting a predefined color from multiple buttons or by choosing a custom color through a color picker input. The selected color is also persisted across browser sessions using local storage.

Features
Predefined Color Buttons: Click any of the color buttons to instantly apply that color to the background of the main container. Each button's color is defined in the CSS and can be easily customized.
Custom Color Picker: Utilize an HTML color picker to select and apply a custom background color. As you choose a color, the hexadecimal value of the color is displayed in an input field for reference.
Persistent Color Selection: The application uses local storage to remember your last selected background color. When you revisit the page, it retains the color choice from your previous session.
How It Works
Color Selection:
Click on any predefined color button to change the background color of the container.
Or use the color picker to select a custom color. The hex code of the color will display in real-time as you pick a color.
Storage:
The chosen color (from a button or the color picker) is stored in the browser's local storage.
Upon reloading or revisiting the page, the background color of the container is restored to the last selected color, thanks to data retrieved from local storage.
Usage
Setup:
Clone the repository.
Open the HTML file in a browser to view the application.
Interaction:
Interact with the buttons or color picker to change the background color as desired.
Technologies Used
HTML5
CSS3
JavaScript
This project is ideal for learning how to manipulate DOM elements, handle events in JavaScript, and use local storage to maintain state across browser sessions.
