# Tic-Tac-Toe Web Game
Welcome to the Tic-Tac-Toe Web Game - a simple yet engaging implementation of the classic Tic-Tac-Toe game using pure JavaScript, HTML, and CSS. This application allows players to enjoy a fun and interactive experience as they compete against each other in this timeless game.

## Features
- **Interactive Gameplay:** Enjoy a smooth and responsive Tic-Tac-Toe game.
- **User-Friendly Interface:** Clean and intuitive design for an optimal gaming experience.
- **Responsive Design:** Play the game seamlessly on both desktop and mobile devices.
- **Reset Game:** Option to reset the game board at any time and start a new game.
- **Realtime Win Tracking:** Keeps track of the winner.

## Installation
To get started with this application, follow these simple steps:

1. **Clone the Repository:**
    ```
    git clone https://github.com/Iramfatema/TicTacToe.git
    ```
2. **Navigate to the Project Directory:**
    ```
    cd tic-tac-toe-webgame
    ```
3. **Open the index.html File:**
    You can open the index.html file directly in your web browser to start playing the game.

## Usage
After opening the index.html file in your browser, you can:

- Click on any cell in the Tic-Tac-Toe grid to make your move.
- Alternate turns between players (X and O) until there is a winner or the game ends in a draw.
- Click the "Reset" button to clear the board and start a new game.

## File Structure
- index.html: The main HTML file containing the game structure.
- style.css: The CSS file for styling the game interface.
- script.js: The JavaScript file containing the game logic.

## Future Enhancements
- Add an AI opponent for single-player mode.
- Implement score tracking to keep a record of wins, losses, and draws.
- Add sound effects and animations to enhance the user experience.

## Contributing
Feel free to fork this repository, make enhancements, and submit pull requests. Contributions are always welcome!



## Some Concepts:
document.querySelector() is a function in JavaScript and it is used to select the first element that matches a specified CSS selector.
The querySelectorAll() method returns all elements that matches a CSS selector(s).

The querySelectorAll() method returns a NodeList.

The getAttribute() method is used to get the value of an attribute of the particular element. If the attribute exists, it returns the string representing the value of the corresponding attribute. If the corresponding attribute does not exist, it will return an empty string or null.

` ` is a template literal.

In JavaScript, backticks are used to create template literals, which allow for embedded expressions and multiline strings.
Template literals provide a convenient way to create strings with dynamic content in JavaScript.

cell => cell.textContent  : 
cell is the parameter of the arrow function. It represents each element in an array or any value passed as an argument when the function is called.
=> is the arrow function syntax itself. It separates the parameters from the function body.
cell.textContent is the expression to the right of the arrow, which represents the return value of the function. In this case, it's accessing the textContent property of the cell object.
Arrow functions are often used in JavaScript for their concise syntax, especially in situations where you need to pass a callback function, such as in array methods like map(), filter(), and forEach().


#next function:
should have a undo button to erase selected cell content.