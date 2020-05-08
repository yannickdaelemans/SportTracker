# SportTracker
a tracker tracking when you sported, what you did and your heartrate etc. 

This is connected to a MySQL database which keeps a log of everything you did using a 
different table for eacht sport (which is not ideal). You can use it with a terminal to add
sportevents to it, although it still is pretty limited. 
There is also a GUI (swing library), from which it is possible to go to the terminal, or add 
or show some sports. 
The code here is far from perfect, but shows the use of some different Java skills, from
using basic Java skills (if, for, while, foreach, ArrayLists, ...), to the use of abstraction
(an interface), and the connection with a MySQL database locally on the computer, as well as 
the use of some Libraries (most notably Joda Time and MySql, and later Swing) and a small bit 
of Maven. 
This project could be highly improved upon via different ways, eg. a better structure of the 
database, a better structure of the code, etc.. This project is only meant to show some basic 
skills of the programmer.

TO DO Future: 
• Connect with Python to do some data analysis on what you get back. 
• put MYSQL on Raspberry Pi and make a web server
