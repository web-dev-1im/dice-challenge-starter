# Dice challenge
Showing two random dice on load, calculating the winner.

## The task

### Cloning starter files
Start by cloning the starter files into your vscode. You must have [https://gitforwindows.org/](https://gitforwindows.org/)
installed first.

Open the terminal and type:
```bash
git clone https://github.com/web-dev-1im/dice-challenge-starter.git
```
If you want to clone it to the folder `My-dice-task` inside your current folder, type:
```bash
git clone https://github.com/web-dev-1im/dice-challenge-starter.git My-dice-task
```

### Dice Challenge Step 1 - Create an External Javascript File
Create a new Javascript file called `index.js` and link to it from the `index.html` file.

### Dice Challenge Step 2 - Add Dice Images
In the Dice project, there is a folder called images, add the images of `dice6.png` as the source to both of the `<img>` elements.

### Dice Challenge Step 3 - Create a Random Number
Inside index.js, create a new variable called `randomNumber1` then set the value of this variable to a random number between 1 and 6. Test it out in the console to make sure it works as expected.

### Dice Challenge Step 4 - Change the <img> to a Random Dice
Use the random number you created in the last step to pick out a random dice image between dice1.png to dice 6.png then place this image inside the left `<img>` element.

### Dice Challenge Step 5 - Change both <img> Elements
Do the same for the right hand side image element.

### Dice Challenge Step 6 - Change the Title to Display a Winner
Change the text in the h1, (which currently says Refresh Me) to show which user won or if there was a draw depending on the dice values of player 1 (left) and player 2 (right).

Tip: You can select the `<h1>` by using `document.querySelector("h1")`. This will return the first h1 in the body.
