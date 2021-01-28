# Amazing-Tetris-master
 
1.SRS document
Use case ID 1
Use case Name First use case example
Goal The purpose of the project is developing the
application for the devices with Android OS.
Actor Players
Trigger Button:Start game
Precondition 1 Open main menu of the application
Primary Scenario 1. When an actor opens an application, firstly
she/he needs to input a name, then the
actor clicks a new game button, then the
game is started, when the game is over the
player can see the title “Game over tap to
play again.”
2. If the actor clicked the High score button,
she/he sees the new open table of score.
3. Game over tap to play again.
4. When the actor clicked the setting button,
he/she could change the level of difficulty of
the game, set number of rows or columns or
set speed.
Exceptions -
Postcondition When game over actor could close the application
Priority hight





1.1 Purpose
This project is a ”Tetris” application that displays various shapes on the
screen randomly and drops them. The developed application is designed to
entertain players, improve their coordination and logical thinking. Of course
this application was done with thinking about best GUI design to make it
bright and attractive for playing.
1.2 Document Conventions
Use Case: A board level diagram of the project showing a basic overview.
User: Generally any logged in player.
1.3 Intended Audience and Reading Suggestions
The intended audience for this document are the team members of ”Tetris”
project, the project Supervisor: Katarzyna Mazur and members of other
projects. This document will be reviewed every week above audiences to
check the progress of our project, until our project will be done;
1.4 Project Scope
The concept of Tetris is that colored bricks fall downward, one at a time,
within a rectangular playing board, the falling brick’s sideways movements
and rotation being controlled by the player’s keystroke commands. A falling
brick stops when it cannot fall further without crossing the lower boundary
or would enter a space occupied by a previously fallen brick. A new brick
then starts falling from the top row. The game ends when a brick stops with
some part touching the top boundary. The goal of the game is for the player
to maximize the number of bricks before the game stops, by controlling the
fall of the bricks to maximize the number of landed bricks that are packed
into the playing board.
1.5 Revision history
Name Date Reason for changes
Diana 2020-11-09 creating and updating srs document
Diana 2020-11-23 updating srs document
Diana 2020-12-21 updating srs document
Diana 2021-01-11 updating srs document
Kateryna 2021-1-13 updating new information

2

1.6 References
The GitHub repository for ”Tetris” project: https://github.com/KaterinMisik/TetrisProject
2 Overall Description
2.1 Product Features

Figure 1.
The functionality is simple - the user has the opportunity to start a new
game, see the highest scores, pause, change the settings: the complexity of
the game, the number of rows and columns, the speed of falling objects.
More about each Use Case: So, first is input name function is based in

3

Main Menu, where user provide the name which will be saved in the device
memory. New Game activity is opening new window with game, when it is
too many bricks game is over. Then user could choose New Game option
and repeat the game, or choose Check Score option to check whole score
table and see the winner results. Of course player could click Pause option
while playing. User also can open High Score function from Main Menu, or
Settings function to change the the level of difficulty for next game.
2.2 Use-Case Diagram
Use case ID 1
Use case Name First use case example
Goal The purpose of the project is developing the application for

the devices with Android OS

Actor Players
Trigger Button: Start Game
Precondition Open Main Menu of the application

Primary Scenario

1. When an actor opens an application, firstly she/he needs
to input a name, then the game is started, when the game
is over the player can see the title ”Game over tap to play
again” 2. If the actor clicked the High Score button, she/he
sees the new open table of score 3. Game over tap to play
again 4. When the actor clicked the setting button, she/he
could change the level of difficulty of the game, set number
of rows or columns or set speed

Exceptions -
Post-condition When game over actor close the application
Priority high

4

2.3 Operating Environment

Figure 2. UML class diagram
2.4 Design and Implementation Constraints
The project will be written in Java, the main developing tool is Android
Studio and GitHub Desktop.
3 External Interface Requirements
3.1 User Interfaces
User interface - a type of interface in which one side is represented by a
person (user), the other-a machine/device. It is a set of tools and methods
by which the user interacts with various, most often complex, machines,

devices, and equipment. Very often the term is used in relation to com-
puter programs, but it can mean a set of tools, methods, and rules for the

interaction of any system controlled by a person. The interface is bidirec-
tional (interactive) – the device, after receiving commands from the user

5

and executing them, gives information to the user by means available to it-
visual, sound, tactile, etc. (after accepting which, the user gives the device

subsequent commands by means provided to it: buttons, switches, regu-
lators, sensors, voice, etc.). Since the interface is a collection, it consists

of elements that, in themselves, can also consist of elements (for example,
the display screen can contain other windows, which, in turn, can contain
panels, buttons, and other interface elements).
