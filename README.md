# Dicer

Dicer is a simple web application that simulates a dice roll for two players. It randomly generates dice results for each player and displays the winner based on the dice values.

## Overview

- **HTML**: Provides the structure of the webpage.
- **CSS**: Styles the page to give it a visually appealing look.
- **JavaScript**: Handles the dice roll logic and updates the dice images and the winner announcement.

## Features

- Displays dice images for two players.
- Rolls the dice randomly for each player.
- Updates the dice images based on the roll.
- Announces the winner based on the dice results.

## Files

- `index.html`: The main HTML file that structures the webpage.
- `styles.css`: The CSS file for styling the webpage.
- `index.js`: The JavaScript file for the dice roll logic.

## How It Works

1. The webpage displays two dice images, one for each player.
2. When the page is refreshed, the `index.js` script generates two random numbers between 1 and 6.
3. These numbers determine the dice images displayed for each player.
4. The script then compares the two numbers to determine the winner and updates the header to show the result.

