# Android Pattern Guesser
 Guesses every single androind password pattern

# How it works

As we all know Android has a unique password system where it gives you a set of 9 dots and you draw a pattern to unlock it. It looks like this:

<img width="200px" src="https://img.gadgethacks.com/img/original/71/62/63581195904113/0/635811959041137162.jpg">
It is organized in a such way to look like this:

**1 2 3**<br>
**4 5 6**<br>
**7 8 9**<br>

You have about 1/1,000,000 chance of guessing the patern correct. The software crunches those numbers in a way like this starting with a 1 digit code:

**1**->**2**->**3**->**4**->... 

Then once cycled through the ones place moves on to double digits:

**1-2**->**1-3**->...

and so and so fourth all the way to the nine digits. By the time it cycles through the 9 digits it will have eventualy generated every possible combination.

