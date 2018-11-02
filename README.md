# Assignment 04

**DUE: Monday, November 19, 2018 @ 5:00PM**

**WHERE TO GET IT**: `/users/library/csis/comp1501/assignments/4.asg.jpratt`

**SUBMISSION PROCEDURE**:

To submit your assignment, just use the usual **submit1501** on INS.
When asked for the task identifier, please use **asg04**.

**WEIGHT: 6%** _(note the increase compared to the last 3 assignments)_

**ANY QUESTIONS?** Please post any questions to [Piazza](https://piazza.com/class/jm9cg39jrr21zs?cid=9#), ideally in the **assignment4** folder.

## Overview

This assignment has 1 challenge - you are being asked to create a single application of non-trivial size. This will be the standard going forward in this course as well as your future programming courses in the program. Welcome to the big leagues.

## Suggestions for a plan of attack

Starting a major assignment can feel overwhelming...where do you start?!?

Here are my suggestions.

1. make sure you understand how cards are removed in the Parade: read that section of the rules carefully! Look at the example in the rules and make sure you get why the cards that get removed **are** removed. Look at the examples in the documentation that involve card removal as well and confirm that you get why the cards that are shown as being removed are marked as such.
1. skim through the documentation of the helper classes provided, just to get an idea of what each class can do for you
1. in the **ParadeTutor.java** file (where all of your work will be done), don't think about any of the complexities that you eventually have to tackle - just create a super-simplified version of the program and then gradually add features to it. Each step of the way, you should have a functioning program! For example, you could follow a progression like this to start:
    1. the program just prints out a welcome
    1. the program prints out the welcome and then a placeholder ("like Parade display goes here") for the cards in the parade
    1. the program does 1 and 2, and then prints the main menu
    1. the program does 1 to 3, and then prompts for the user input
    1. the program does 1 to 4, and then takes in user input and runs a stubbed-out method that just prints a message ("handling display new parade", or "handling showing a marked-up parade", or "handling quit")
    1. the program does 1 to 5, and continues to loop until the user decides to quit
    1. the program does 1 to 6, and then shows 1 card from the InfiniteDeck instead of a placeholder.
    1. continue in this fashion, taking small steps

    By working in this fashion, you always have a working program, which makes you feel like you're accomplishing something and moving forward - THIS IS SUPER IMPORTANT! A huge part of being successful in any programming task is about confidence.

    Another benefit of working this way is that it is harder for bugs to creep in, because you are working in small steps that focus on a single feature.

## Running tests

- Run the automated output tests using `make tests`
- Run the automated style tests using `make style -i`

## WARNING!

You will want to get started on this right away.

You know by now from your experiences in the last 3 assignments that programming is a time-consuming (nay, a time-_devouring_) process. To make matters more interesting, you are now entering the time of a semester when numerous things (often of significant weight) are coming due in your other courses and it's very easy to feel overwhelmed.

Persevere - you can get through this, as have others before you.
