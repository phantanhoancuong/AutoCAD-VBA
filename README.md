# AutoCAD-VBA

This is the 10th assignment in Applications of Computer Graphics

Problem 1:
Construct a Module that takes in the coordinates of point A and B in 2D space then draw the line AB. Prompt the user to enter the coordinates of point C and find the coordinates of projection D of C onto AB, send the coordinates of D through MsgBox if D exists.
In case D exists, draw:
 • The line CD
 • The EF segment parallel with AB and goes through C so that dAB = dEF = 3dEC
 • Circle with center C and a radius CD
 • Spline through A, E and F.
 • Adjust the camera so that the every objects drawn fit neatly onto the screen.
 
 Problem 2:
 
 • Construct a function calculating the coordinates of control points for each basic objects based on the data the user puts in.
 • An inner circle created using an offset function with an outer circle.
 • Draw basic objects like circles, lines with VBA built-in functions.

 • With objects that aren't supported by VBA like Arc (StartPoint, EndPoint, Radius), Circle (TanTanRadius), we can call through SendCommand. The specific command is constructed with a String variable.
 • Draw the dimensions of said objects onto the drawing.
 • After drawing the entire objects, return a message showing the area of the constructed object.
 
![image](https://github.com/phantanhoancuong/AutoCAD-VBA/assets/132530129/3ffb570b-92d3-4651-8d35-bd2c201f8e46)

