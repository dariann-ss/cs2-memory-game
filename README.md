# cs2-memory-game

# Project Setup
1. Install *Live Server*
2. Create ```script.js```
3. Add ```console.log("Script started")``` to begining of ```script.js```
4. Add ```<script src="script.js"></script>``` before ```</body>``` tag in ```index.html``` to link the script
5. Create ```styles.css```
6. Add a ```body``` selector and set the background color and text color to whatever you like
7. Add ```<link rel="stylesheet" href="styles.css">```  in the ```<head>``` section to link the stylesheet to ```index.html```
8. Go live and verify that you see your CSS styles and use the inspection tool to check that you see ***Script started*** in the console to verify your script is linked correctly to your html 

## Game Play
1. All cards are hidden to start
2. The user clicks a card which reveals the "other side"
3. The user clicks another card which reveals that card
    - If the cards match, they stay flipped (maybe change color to show the match)
    - If the cards don't match, they flip back over
    - In either case, it counts as one guess
4. When all cards are matched, the game is over


## Create the basic HTML/CSS layout for the game
Design the webpage. It should include a heading, instructions, grid of 8 cards, and a display of the number of guesses
1. Create a heading h1 and instructions p
2. Create a gameboard using a div or section tag
2. Create a card using a div with .card class
3. Create two rows of four cards using divs with .row class
4. Create a heading h2 to display the number of guesses