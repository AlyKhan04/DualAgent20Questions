## Overview
The following script is an experiment to see how well two agent's both powered by the openAI API interact with one another with minimal input by the user. To simulate this, I recreated the popular game "20 Questions" and made two agent's, each selected at random be the guesser and the answerer.<br>
The User simply adds the object to be guessed (be careful of spelling errors) and presses enter, the game starts and the agents start the loop of asking questions and answers.<br>
Since each API call to the chatGPT model is unique (no concept of memory), there is no way for the "guesser" to know what the "answerer"'s object is. <br>
Again since each call is unique, to narrow the scope of the questions as you would in an actual human game (and no guesses before 20), a history of the previous turns Questions and Answers are given to the "guesser" with each passing question being added. This allows the Guesser to ask more revelant questions each turn. <be>
Please find the how to run below and enjoy testing the capabilities of AI powered agents.

## How to Run
1. Download the .ipynb file.
2. Add your openAI API key
3. Press run, and add the object to be guessed
4. To make sure you see the AI's response every step of the way, after every question is asked and answered, just press enter to get the loop to continue.
5. Watch and see how far the AI makes it before it can make a guess, if it can at all.
