# Paper Puppets

*A lab report by Frans Fourie. Student*

## In this Report

To submit your lab, clone [this repository](https://github.com/FAR-Lab/IDD-Fa18-Lab4). You'll need to describe your design, include a video of your paper display in operation, and upload any code you wrote to make it move.

## Part A. Actuating DC motors

Video of my Vibration motor:
https://youtu.be/pyZ_rPtaAtw

## Part B. Actuating Servo motors

### Part 1. Connect the Servo to your breadboard

**a. Which color wires correspond to power, ground and signal?**<br />
Brown Wire = Ground<br />
Red Wire = Power<br />
Orange Wire = Signal<br />

### Part 2. Connect the Servo to your Arduino

**a. Which Arduino pin should the signal line of the servo be attached to?**

Digital Pin 9

**b. What aspects of the Servo code control angle or speed?**

The for loops inside the main loop function is used to change the value of the pos variable. The pos variable is used to tell the servo to whitch position to move. This line of code tells the servo motor to move to the position stored in pos ```myservo.write(pos); ``` . The delay controls the time between the servo moving thus delaying the movement between positions that is controlled in this line ```delay(15); ```. The delay also gives the servo time to do the move you have instructed it so even for maximum speed a delay is necesarry and there will need to be experimented to find the minimum value for delay but delay can be incresed to slow down the movement as the motor will move at the same speed but will wait longer between moving.

## Part C. Integrating input and output

Video of my Servo Motor in action:
https://youtu.be/QazgTuhNJv8

## Part D. Paper puppet

Video of my Paper puppet:
https://youtu.be/et45UYA08Rk

## Part E. Make it your own

**a. Make a video of your final design.**

My photo puppet works by pressing on a softpot resistor which is also its default position else you can set a specific position using a potentiometer and then pressing a button to move it to that position. After moving to a specific position from a button press the photo puppet will return to to the state indicated by the softpot.

Video of my Paper puppet that I made my own:
https://youtu.be/AEZ2-9b6rGY
 
