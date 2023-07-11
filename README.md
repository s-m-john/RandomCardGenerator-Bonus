# </> Random Card Generator

In this project, you will learn how to change your website styles during the runtime using VanillaJS (plain normal js).

📝 Instructions
Create an algorithm that randomly builds a card on every refresh:

Every time the website refreshes a new random card needs to show.

The card must have one of the possible suits: Hearts, Spades, Clubs and Diamonds.

The card value must be one of the following: 2 to 10, King, Queen, Jack or Ace, (no joker).

## 😎 Feeling Confident?
The following requirements are not needed to successfully finish this project, but you can try and challenge yourself!

+1 Add a button that generates a new card when clicked.

+1 Add a timer that generates a new card every 10 seconds.

+1 Allow the user to specify the card width and height using text inputs.

##💡 Hints
Remember that the first event of a website lifecycle is onLoad (your code starts running there). You should generate a random number between 1 and 4 to pick a suit and another random number between 0 and 12 to pick a card number.

Create a general .card class that applies the general styles to each card, and one additional CSS class for each suit: .spade, .club, .heart & .diamond.

Apply the .card class to the entire div, but only apply one of the suit classes at a time, depending on what suit you want to apply. For example, a 3 of Hearts will have this HTML declaration:

    <div class='card heart'></div>

You can grab the icons from here (copy and paste into your code): ♦ ♥ ♠ ♣

### Thank you

This template was built as part of the 4Geeks Academy [Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) by [Alejandro Sanchez](https://twitter.com/alesanchezr) and many other contributors. Find out more about our [Full Stack Developer Course](https://4geeksacademy.com/us/coding-bootcamps/part-time-full-stack-developer), and [Data Science Bootcamp](https://4geeksacademy.com/us/coding-bootcamps/datascience-machine-learning).

You can find other templates and resources like this at the [school's GitHub page](https://github.com/4geeksacademy/).
