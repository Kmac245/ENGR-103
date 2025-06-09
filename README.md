# ENGR-103
ENGR 103 Project Final

Title: Letter Lister

Device: Adafruit Circuit Playground Express Arduino IDE


**Dependencies**

Adafruit Circuit Playground: https://github.com/adafruit/Adafruit_CircuitPlayground.git


**Game Function**

Objective - press the button for each letter in the word heard.

The speaker will sound a random word and then start a 10 second timer. To increase your letter guess count, press the right button. To decrease your guess count press the left button. Once you have the correct amount of LEDs lit from your guess, you must submit the answer by placing your finger over the A1 pad. If your answer is submitted and correct when the timer runs out you will gain a point. Win 3 rounds in a row and you will go to the next level where time decreases to 8 seconds. Win another 3 rounds in a row and you will go to the final level where time decreases to 6 seconds. Pass all three levels with no losses to win!


**Inputs**

Right Button - Increases guess count and LED.
Left Button - Decreases guess count and LED.
A1 Sensor - Detects capacitance.


**Outputs**

Speaker - Speaks a random word at the begining of each round from library of 9 words.

LED 0 - Glows for 1 point scored that round. Changes color based on round. Blue -> Purple -> Green. Will flash white to indicate next round. 

LED 9 - Glows for 2 points scored that round. Changes color based on round. Blue -> Purple -> Green. Will flash white to indicate next round. 

LED 1-8 - Glow white from 1 to 8 to display the count of the guessed letter values.

LED 0-9 - Spins red if incorrect answer. Spins green if you win.

Serial Monitor - Displays time, level, and win or loss status.
