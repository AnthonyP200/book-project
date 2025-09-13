Project: number-display
Authors: Michael Kölling and David J. Barnes

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class NumberDisplay. Then inspect this 
instance and leave the inspector window open. With the inspector window open, 
call the object's methods, such as increment and setValue.


Questions:
6.An increment should be transferred from minute to hour after there is one rotation in the minute section.
8.The value is changed when it is lower than the limit but when it is higher, it does not give an output and resets to 0.
9.Both values resulted in 0 since both values were only set to 10 and not given 10 increments.
10.The method I used is not a proper method since I'm calling on the class and not the object.
11.The error mentions the prompt missing a .class to process it.
12.The change allows the increment to reach the number of the limit but not pass it without resetting.
13.Anything ( >0 but < limit )
15.! (4 < 5)=false
! false=true
(2 > 2) ((4 == 4) && (1 < 0)) ││=false
(2 > 2) (4 == 4) && (1 < 0) ││=false
(34 != 33) && ! false=true
16. (a && b) || (!a && !b)
17.(33 != 32) && ! false
20. 12cat
   cat12
21. Because the values of the objects it created are 0.
23. You would need to call the method 60 times, or you could call the setTime method and set the minutes to 60.
24. NumberDisplay digit = new NumberDisplay(10);
25. Rectangle window = new Rectangle(12, 10)
26. The second constructor allows you to create a clock display with you own limits for the hours and minutes.
It does this by adding parameters.
27. The second constructor has parameters while the first doesn't. 
The second doesn't have the updateDisplay method 
because it has the setTime display which has the updateDisplay method in it.
28.
p1.print("File", True);
p1.getStatus(1);
29. Triangles, squares, and circles.
30.
roof = new Triangle();
roof.changeSize(60, 180);
roof.moveHorizontal(20);
roof.moveVertical(-60);
roof.makeVisible();
roof.changeColor("black");
roof.changeColor("green");
31. Yes.
32. 2.
33. It accepts negative numbers.
34. Any integer ranging from -4 to 4.
35. Any integer from 0 to |m| - 1 or 0 to -(|m| - 1).
37. I found that changing the values to 1 through 12 was easier and better, 
because with the other option you're only changing the display, the front, 
however with the first option you're changing the back end of the clock.
