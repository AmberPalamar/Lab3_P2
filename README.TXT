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

Answers

21. The clock starts at 00:00. It starts at this time because that is the beginning of the clocks cycle.
22. Calling the timeTick method made the time go from 00:00 to 00:01. setTime method allows you to choose the time displayed on the clockDisplay. 
23. You would need to call the method 60 times. Another way to make it display that time is by using the setTime method and choose 1:00 as the time.
24.
25. Rectangle window (int 5,10)
26.
27. The second constructor allows you to choose the time that the clock is set at when created. Difference between the 2 constructors is that the first will automatically start at 00:00 and the second lets you choose the time its set at. 
28. 
