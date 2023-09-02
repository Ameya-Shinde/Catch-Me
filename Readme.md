# Catch Me Game

## Description

The "Catch Me" game is a simple interactive web game implemented using HTML, CSS, and JavaScript. In this game, the user's objective is to catch a moving text element within a designated area.

The game features:

- A div element with the ID `di`, containing the text "Catch Me".
- The div element moves to a random position within the viewport when the user hovers over it.
- When the user clicks on the moving text, a congratulatory message is displayed.

The game is designed to provide an enjoyable and engaging user experience using basic web technologies.

## Hosted Link
https://ameya-shinde.github.io/Catch-Me/

## JavaScript Functionality Used

The "Catch Me" game leverages several key JavaScript functionalities to create an interactive gaming experience:

- **getElementById():** This method is used to retrieve the element with the specified ID from the HTML document. In this game, it is used to select the `<div>` element with the ID "di."

- **addEventListener():** The `addEventListener()` method is employed to add event listeners to HTML elements. In the game, it is used to listen for mouseover and click events on the selected `<div>` element.

- **Math.random():** The `Math.random()` function generates a random floating-point number between 0 (inclusive) and 1 (exclusive). In the game, it is used to generate random numbers for determining the new position of the moving text.

- **style.left and style.top:** These properties are used to manipulate the CSS properties of an HTML element. In the game, they are used to dynamically set the left and top positions of the "di" element, causing it to move to random positions within the viewport upon mouseover.

- **createElement():** The `createElement()` method creates a new HTML element specified by the tag name. In this game, it is used to create an `<h1>` element dynamically.

- **innerText:** The `innerText` property is employed to set the text content within an HTML element. In the game, it is used to populate the dynamically created `<h1>` element with a congratulatory message.

- **appendChild():** The `appendChild()` method is used to append a child element to another element in the HTML document. In the game, it is used to add the dynamically created `<h1>` element to the `<body>`, displaying the congratulatory message to the player.

These JavaScript functionalities work seamlessly together to create the interactive gameplay and user feedback in the "Catch Me" game, offering an engaging and enjoyable experience for players.
