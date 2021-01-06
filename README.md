# CortexPrime
Character sheet(s) for Cortex Prime focusing on a Cortex Plus Marvel Heroic-compatible implementation.
The dice pool controls are at the top of the character sheets. They are inspired in part by the DiceStream app that was once available in Google Hangouts. 
Buttons on the sheet add dice to your pool, or you can add them in the roller itself.
The d20 button in the roller rolls your dice into the chat.
The sheet requires the ChatSetAttr API script to function properly.

The Dice Pool
The controls on the left are the dice pool itself and the buttons to manually add, remove, roll, and clear dice.

To roll any single die, click on the picture of that die. That die will be rolled in the Roll20 Chat window.

To add dice to the pool, click the roller wheel below the picture of a die to increase to counter below the chosen die type.

Once you've selected how many of each type of die you want in your pool, press the ROLL button. Your dice will be rolled in the Roll20 Chat window.

There is also a CLEAR button to clear your old pool, or clear the pool if you need to start fresh. The CLEAR button has a pop up "Are you sure" window to avoid inadvertently erasing a nice large dice pool you have just lovingly created.

The Dice Pool Actions
The controls on the right are for dice pool manipulation according to the Cortex System rules. The radio buttons in the top row are selected first, then the appropriate action button is clicked.

NOTE: These dice pool functions do not check to confirm that you have the right dice already in your pool to take these actions. As such, it is up to you to make sure you don't click an action button when there are not enough dice of the selected size in the pool to complete that action. Doing so can produce "spurious" results.
The buttons are

2X - Doubles a die of the selected size. This function should only be used when there is at least one of the selected dice in the pool.

UP - Steps Up a die of the selected size. This function should only be used when there is at least one of the selected dice in the pool. Stepping up a d12 results in a d12 being replaced with a d12 and a d6.

DN - Steps Down a die of the selected size. This function should only be used when there is at least one of the selected dice in the pool. Stepping down a d4 removes it from the pool.

/2 - Split a Die into Two Smaller Dice. This function removes a die and replaces it with 2 dice one step down. Using this on a d4 just removes it from the pool.

/3 - Split a Die into Three Smaller Dice. This function removes a die and replaces it with 3 dice two steps down. Using this on a d4 or d6 just removes it from the pool.

/4 - Split a Die into Four Smaller Dice. This function removes a die and replaces it with 4 dice three steps down. Using this on a d4, d6, or d8 just removes it from the pool.

2->1 - Combine Two Dice Into a Larger Die. This function removes 2 dice and replaces them with 1 die one step up. Using this on a pair of d12s just removes them from the pool. 



The character sheets themselves have additional interfaces to the dice pool roller that are explained in their handouts.

Also, in the event that you just want to use ROLL20 and this dice pool roller and not the specific character sheets, there is a Dice Pool Roller Only button available for just that scenario. I use a Dice Pool Roller Only as a "character sheet" for my Doom Pool.
