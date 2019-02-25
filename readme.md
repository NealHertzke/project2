# Project 
Interactive Frontend Development Milestone Project - 
CREATE A MEMORY GAME (SIMON)
In this project I made a single page application that uses html, css, and js to create a memory game called SIMON.

## Getting Started
run the simonboard.html file using c9, It will link you to the app directly.
without c9, you would need css and javascript installed. otherwise I would migrate the project from c9 to desktop through a .rar file.

### Rules of the game
The aim of the game is to memorize the color sequence and try and remember it as it gets longer.
You have to try and reach the highest amount of color sequences that your memory will allow by clicking on the same color sequence.

#### Function
In Every Sequence the function runs off a true or false statement, it runs a random number which is connected to a color on the board.
It continues along a pattern of sequences that the player manages to follow, but when the player puts in the wrong sequence an error appears, and causes the player to lose,
the player has to manually restart the game by hitting the Reset Button. I also added a sound for each color to help the players memory. The program used for the functionality of the game is Javascript.

##### Tests
I ran all my tests manually (trial and error), until the game actually was working and running logically how it should. the only error left in my code is that you have to manually reset the game, 
losing it doesnt reset the game automatically as was intended. I also used dev kit tools and google searches to find the obvious bugs and found where the code would go wrong.
I also tested the app on a mobile device, the sound is quite buggy there, and the game isnt well optimized to be played on a mobile device, I recommend it be tested using a computer as this was the platform i primarily designed it around.

###### Design/structure
Design- I used Css for the design of the game, I created pixel based measurements to create each color as part of a circle, I created a smaller circle with divisions using a border method.
the font i used is Raleway, sans-serif for most of the text such as the Rules, however I used Staatliches, cursive for the "Start" and "Reset" buttons. 
for the background i wanted a stale color that lets the game itself on the app standout more. I did not use a specific font for the "SIMON" title of the switch board, as I was content with the initial base design of it.

Structure- The html file consists of the base code for this app, it has all the classes and divs for each of the buttons, and also includes the information that comes with the app, such as the rules.

###### Acknowledgements
-Root Tech- his youtube channel gave me alot of insight overall on how to code the simon game using html, css, and js.
soundjay.com used 4 generic sounds from this website.
