# Teeny-Lil-Chat-Modular-Thingy
 Teeny lil template chat modular thingy  i uploaded to perchance to test with no imports or actual code, just a nice template to work from.

Dev log
 Teeny lil template chat modular thingy
 no imports or actual code, just a nice template to work from.

# design thingys :
* Red and Black theme interface.
* black background with red moving particles populated with a dynamic three.js background. 
* Beneath is a left panel container.
* Two centre containers perfectly sized with no overlap.
* A lower container panel at the bottom rectangular chat style.  
* a navbar with three buttons.

# Note #
I tried the make the code as small and light and singular as possible without any imports so it can be easily modified.

If you want to use this locally offline with ollama or easy diffusion or other offline stuff.




# Linux 

1. update your py3 and pip in terminal

 sudo apt install python3
 sudo apt install python3-pip

2. Then inside the folder you want to serve,
   open a terminal and type:

 python3 -m http.server 8000

!! Boom !! Instant server. 
!! Your browser goes to: http://localhost:8000/




# Windez : Here's a lil Bat Skript.

1. Open a text file and copy the following : 



:: Tidy Intro
@echo off
cls

:: Fancy Layout
set n=^&echo.

:: Step 1: Tidy Intro
echo =================================================
echo Welcome to the Teeny Python Server!
echo =================================================
echo.
echo Date: %date%
echo Time: %time%
echo Starting a Local Python Server... %n%

:: Step 2: Start a local server
start "" python -m http.server

:: Step 3: Show the user the address
echo -------------------------------------------------
echo Your local server is up and running!
echo Open a browser and navigate to:
echo http://localhost:8000
echo -------------------------------------------------
echo Press any key to exit.
pause >nul



2. Save it as Teeny-PyServer.bat
3. Run it and..

!! Boom !! Instant server. 
!! Your browser goes to: http://localhost:8000/


Anyways, just a little project to share and hope its helps as a good starting point.
Enjoy.


!! Oh I Added a Generator Views and a lil Three.js particle system for fun.
And to see if people like it.

# This is the views part you can remove
generatorStats = {import:generator-stats-plugin}
// <small><i> version [generatorStats("views")]</i></small>
