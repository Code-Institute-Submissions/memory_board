# **Football Memory Game**

![Game Caption](/assets/images/gamecaption.PNG)


## **The Aim of This Game.** ##

The main aim for this project is to design a game that is easy to play and, with the varying degrees of difficulty, is challenging but not impossible.
It is aimed at all age groups with the purpose if trying to improve your score by using the lowest amount of flips you can. 
The easy level would work well for younger children while improving their memory and also their hand eye coordination. 

The most important aim is for the user to have fun and enjoy the challenge. 


## **UX**

1. As a user I want a game that is quick and easy to understand.

2. I would want basic instructions that are easy to follow.
3. As a player,  I want a subject matter that interests me (in this case football).
4. As a player, I need a game that is challenging but also achievable with practice.
5. I want a game that is playable by all age groups.
6. As a parent I would want a game that helps a childs development.
7. As a player I want to have a target to beat to encourage me to continue. 
8. As a user I would want a site that is easy to understand and navigate through.


## **Features** ##

### **Existing Features** ###

On the front page all buttons are clear.

- *How to Play:* When clicked this gives full and concise insruction on how to play the game.

- *Time:* This will count down from 90 seconds, showing how much time you have left to play before GAME OVER.
- *Levels:* There are three levels, Easy, Medium and Hard. The level you are on is clearly highlighted. 
To move to another level just click on whichever you want to try. 
All levels have a time limit of 90 seconds but become increasingly more difficult due to the amount of pairs required. 

1. Easy Level has 24 cards so 12 pairs to be found
2. Medium Level has 32 cards so 16 pairs to be found 
3. Hard Level has 40 cards so 20 pairs to be found. 

- *Flips:* This shows the number of cards you have flipped over in order to complete the level. The object is to try to finish the level with the fewest amount of flips. 

- *YOU WIN:* On completion of the game you will see a pop up message saying "YOU WIN" Click to play again. 
When you click on it the game will restart with the cards shuffled into different positions. 

- *GAME OVER:* If you fail to complete the game within the 90 seconds you will see a pop up message saying "GAME OVER" Click to restart.
 When you click on it the game will restart with the cards shuffled into different positions.

 - *Levels:* When you change level the screen will automatically adjust to show the cards in play as well as the time and flips count.
 This is useful on larger screens but on smaller screens some levels will not be able to show the full amount of cards and you will need to scroll through 


### **Features Left to Implement** ###

1. I would like to add some music and sound effects to the game. For instance
- Background music whilst the game is being played.
- Sound effect on finding a matching pair.
- Sound effect for winning the game.
- Sound effect for losing game.

2. Scoreboard. If you have completed a level a scoreboard showing the number of flips and the time remaining. There would be a top 5 scores showing for the day and an all time top score to beat.

3. Within the scoreboard a place to type you name to show who has the best score if you had a competition.

4. I would add a HELP button that, when pressed, would flash up two or three pairs within the game to help if you are stuck and time is running out.


## **Technologies Used** ##

Languages Used

1. *HTML:* The main language for this site was HTML.

2. *CSS:* The site was styled using CSS.
3. *JavaScript:* All the movement of cards and the timing/flips count was conducted using JavaScript
4. *Bootstrap:* https://getbootstrap.com/ To simplify the process of the layout  for the cards, buttons and modal I used Bootstrap.

## **Testing** ##

During the build of the site I regularly tested different sequences etc to ensure all was as it should be. I did find one or two bugs that I managed to overcome. 

1. Initially on start up, regardless of what I clicked on the clock would start to run. This occurred even if I clickd on a level or even on the "How to Play" button. 
I solved this by decreasing the size of the start button and the area in which you had to click. 

2. The next Issue I encountered during testing was the screen sizes for smaller screen sizes. The only solution was to add the @media styling in CSS for each screen size I could. 
I feel that generally this type of game is not really designed for phone size screens although it is still possible. 

3. The biggest problem I came across was, that if I was to fail to complete the level I was on, I was able to continue turning cards over. 
This happened even though the "Game Over" text appeared. Also if I was to carry on the "flips" would continue to be counted. 
I only found this out by accident when playing the game on the Hard Level. To solve this problem I added the line this.hideCards() in JS within the game over section. 
As soon as the "Game Over" text appeared the cards all flipped back to face down and the flips count returned to zero. 

4. Other than the above comments I made sure that the link between each level worked effectively and the each level was achievable.
Admittedly the Hard Level probably had more "Game Over" messages than "You Win" but after time I was able to complete it with some regularity.
I felt that this was a good thing as I was very pleased when I managed to complete it and made me want to try again. 

5. The "How to Play" button worked on all pages without an issue. 
6. I have run all CSS and HTML files through a validator and all appear error free


## **Deployment** ##

Step by step guide for deployment is :- 

After final git push I went onto my GitHub page at https://github.com/Craggy19/memory_board. 

Once there I went to settings and scrolled down to GitHub Pages, from there I changed the dropdown menu from None to Master Branch and hit enter. 

Local deployment.

Within the Memory_Board repository I clicked on green code button. This gave me an option of 
https or ssh. I chose https and clicked on the download zip option. This then downloaded to my laptop which I have unzipped and am able to play locally. 

## **Credits** ##

My initial inspiration was from a you tube video from PortEXE. I took much of this code and adapted it to my own style.
https://www.youtube.com/watch?v=3uuQ3g92oPQ

While I still used this shuffle technique I needed to understand how it worked and I found this information at 
https://www.w3schools.com/js/js_array_sort.asp

The images for the back and face of the cards were taken from various sites in google images. 

The background was taken from Wallpaperswide.com via google images. 

### **Acknowledgements** ###

I had three discussions with my mentor and was advised at the beginning that a Pairs Memory Game is probably the best route forward at this stage. 
I combined the game with my personal interest in Football. I discussed with friends and colleagues and 
the team badges was the outcome of these discussions. 
