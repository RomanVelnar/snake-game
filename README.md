# snake-game

The beloved Nokia 3310 game. Its beginnings go further back to the year of 1976, where game publisher Gremlin, designed and developed it for the arcade game Blockade. The game was further cloned by many large game developers at that time. It had its most success with the old Nokia monochrome phones.

## How does the game work

The game is played with the up, down, right and left keyboard keys. The snake’s position is randomly set with each start of the game. The goal is to make the snake as long as possible, this is done by consuming squares that are displayed randomly on the play-field. These squares will be referred as "food" in the bottom sections. The game end if the snake touches the edges of the playfield or touches its own body.  

## Project Description

Remembering the game has made me feel nostalgic and I wanted to recreate it. I thought that this would also display my Vanilla JavaScript skills and creativity in expanding on the game features that we did see before. This game was developed in several phases depending on my coding skills. 

### Technologies used and why

The game was developed using only JavaScript, CSS and HTML, it is uncertain if in the future further libraries or programming languages will be implemented.

### Challenges faced and features for the future

First challenge was to set the continuous loop that updates the snake’s position and sets the snake’s body. Especially, how the snake body moves after you move its head. The issue I had that the body was expanding its body and did move with the head. I had to set the gameBoard.innerHTML = " " to nothing, therefore the it clears everything in the view. 



#### Features

 - Add the simple feature where the game counts the length of the snake’s body at the end of each game and saves top5 results in local storage. 

 - Add "food" that are two and tree squares long and positioned either vertically or horizontally. Snake has to eat the food at a certain angle or its game over. These could come occasionally as a "mini-boss". 

 - Make different version of the game, one could be where the tail end of the "snake" could be in fixed position and the "food" would shorten the snake’s body by a certain amount.


## How to install and run the game 

Install it using 

```

git clone https://github.com/RomanVelnar/snake-game.git

```

best to use it with the liveServer extention in VS Code

