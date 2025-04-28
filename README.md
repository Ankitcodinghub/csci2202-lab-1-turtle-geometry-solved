# csci2202-lab-1-turtle-geometry-solved
**TO GET THIS SOLUTION VISIT:** [CSCI2202 Lab 1-Turtle Geometry Solved](https://www.ankitcodinghub.com/product/csci-2202/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116953&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI2202 Lab 1-Turtle Geometry Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Introduction to Programming with Turtle Geometry

Lab Goals:

• Gain familiarity with IDLE.

• Learn about assignments and objects.

• Learn about the looping constructs in Python

Part 1: Using IDLE

(1) Start IDLE.

(2) Consider throwing a ball up in the air. The vertical position of the ball y changes with time time according to:

(ignoring air resistance)

(3) Enter the following formula in your IDLE prompt and press Enter:

&gt;&gt;&gt; 5 * 0.6 – 0.5 * 9.81 * 0.6**2

Note: (0.6)2 is written as 0.6**2. This simply uses the python interpreter as a calculator. Now, if you wanted to find the y position of the ball at t = 1s, you would have to type in the formula once more.

However, there is an alternative: Use variables in the program (specifically v0,t and g).

(4) From the IDLE menu click on: (File→New File) and type in the following:

# Create a variable for storing initial velocity in m/s v_0 = 5

# Create a variable for storing the desired time in seconds t = 0.6

# Calculate the ball position in metres y = v_0 * t – 0.5 * g * t**2

1

2

# Inform the user of the current ball position

print( “At t = ” + str(t) + “the position of the ball is” + str(y))

The “#00 above each assignment is a comment. It is there to remind you what some code (in this case a variable assignment) is doing. Everything after the “#00, to the end of the line, is ignored by the interpreter. Comments should be used to make clear what the code is doing. Commenting is good programming practice.

There are other (equivalent) ways to print:

print( “At t = ” , t , ” the position of the ball is “, y). (Note the commas)

Ex. 1 For the next exercise, create a program c2f.py to convert temperatures from Celsius (C) degrees into corresponding Fahrenheit (F) degrees with the formula: + 32. The output of your program should be of form:

16 degrees Celsius is 60.8 degrees Fahrenheit.

Once the above program is running properly, you can instead prompt the user for a temperature after the program is running. To do this, replace the variable assignment C = 16.0 line with:

C = float(input(‘‘Enter a temperature in degrees C: ’’))

… contd. →

3

Part 2: Turtle Graphics:

• Python has a built-in module that supports turtle graphics called the “turtle” module. The module provides an environment that allows you to create and control the movements of a turtle object on a screen. The turtle has a pen that draws the path it is instructed to follow using python commands. We use the turtle module to draw simple geometric shapes. These exercises allows us to explore the fundamental constructs of programming in an entertaining way.

• Create a new Python file. Name it anything except turtle.py

• First we have to make sure Python knows we want to use the commands found in the Turtle module. To do this, we include the following line at the top of our file:

import turtle

• Next, we need to create a window and a turtle to place in the window. To do so, we use the following Python commands:

# Create a window and store it for later use turtleWindow = turtle.Screen()

# Optional: Set the name of the turtle’s window turtleWindow.title(‘‘Turtle Drawing Demo’’)

# Create a turtle named mickey in the shape of a turtle mickey = turtle.Turtle(shape=’’turtle’’)

• Time to draw some interesting things!

The turtle module has (among other things), a collection of functions defined to control a ‘turtle’ object’s motion. Some of these functions have synonyms: e.g. forward( d ) &amp; fd( d ) to move the turtle a distance d, in the direction the turtle is facing.

To have the turtle object (say) mickey, have one of these functions operated on it, write: mickey.functionName(value). For example, mickey.setposition(-200, 100) moves mickey to the location x = −200,y = 100 on the screen.

Once the turtle module is loaded, the following functions available to you: forward( d )/fd( d ) moves turtle in the direction it’s facing by d units. backward( d )/bk( d ) will move your turtle backwards d units. left( d )/ lt( d ) rotates turtle d degrees counter-clockwise.

right( d )/rt( d ) rotates turtle d degrees clockwise.

penup( )/pendown( ) tells turtle to stop/start drawing lines resp.

By default, a newly created turtle will be in pendown() mode.

setposition( x, y )/ goto( x, y ) sends turtle to the position (x, y).

4

The two instructions shown below, draw a line and turn the turtle counter-clockwise by 90o.

mickey.fd(100) mickey.lt(90)

By default, the turtle starts at (0,0), at the centre of the window.

Moving East/North is to move along +x/ + y direction and to move West/South is to move along −x/ − y For example, mickey.setposition(10,-40) will make your turtle move East and South. (However, unless you insert penup() before the setposition (…) command, your turtle will to draw a line (from the its initial position to (10,−40). To end your turtle program, make sure to include turtle.done() as the last command in your file to let Python know you’re done drawing with your turtle.

• Create a new file, type the commands in the order described above and run the program. Experiment by adding 4 or 5 more forward(), back(), left() and right() commands. Add the command mickey.pencolor(“blue”) before you move your turtle. What happens if you remove shape=‘‘turtle’’ from the turtle.Turtle() function?

Deliverables: The code for each exercise should be in a separate file.

Put all your solutions in a folder titled: Lab1 &lt;name&gt; &lt;B00number&gt; Ex. 2 Once you have a grip on the above instructions, make a program to draw a square of size 100, each of whose sides are a different colour. Use only the commands shown above (you can cut-and-paste). Save it in a file called square.py. Show the result to the T.A. before proceeding.

Ex. 3 It is tedious to repeat the same commands. Change your program to use a loop for the repeated commands in Ex. 1.

Ex. 4 Make a program to draw a regular hexagon (a six-sided polygon).

Try working on the first problem for the 2nd lab:

Ex. 1 (a) Start by modifying polygon.py from the last lab. The modified program should ask the user to input a value for the variable numSides.

(the Python command numSides = int(input(‘‘Enter the number of sides ’’)) does the job. The input always reads the user input as a String. The int to the left of the input casts the input string into an integer.)
