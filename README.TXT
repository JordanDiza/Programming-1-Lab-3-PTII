Project: clock-display
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class ClockDisplay. Then inspect this 
instance and leave the object inspector window open. With the inspector window open, 
call the object's methods, such as timeTick and setTime. Watch the 
"displayString" in the inspector.

The displayString field simulates the actual clock display device. Were this 
program running in a real clock, it would change the real, physical display 
hardware instead of this string. The timeTick method would be triggered once 
every minute by some timer hardware.

Everything else could be pretty much the same.


Note: This project does not implement adequate handling of errors.

Hello 

test test

Lab 3 Pt II

#21  
getTime method is at 00:00
Its like that because I didnt put the number of hours and minutes in it yet

#22 when I use the method timeTick() the private String displayString goes to "00:01"
when setTime(2,40) the displayString show "02:40"

#23 I have to call it 60 times
I can also use the setTime() method setTime(1,00)

#24 digit = new NumberDisplay(10);

#25 Rectangle window = new Rectangle(width, length);

#26 There are 2 constructor here hours, minutes
the constructor minute lets the NumberDisplay max out at 60 (it rolls over at 60)

#27 When you put the values for hour it already updates so you dont need to put it there

#28 p1.print("myfile.txt, true");
int status = p1.getStatus(6);

#29 wall, window, roof, sun, drawn

#30
