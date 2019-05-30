# Search
Pacman spends his life running from ghosts, but things were not always so. Legend has it that many years ago, Pacman's great grandfather Grandpac learned to hunt ghosts for sport. However, he was blinded by his power and could only track ghosts by their banging and clanging.

In this project, you will design Pacman agents that use sensors to locate and eat invisible ghosts. You'll advance from locating single, stationary ghosts to hunting packs of multiple moving ghosts with ruthless efficiency.
The code for this project consists of several Python files.
Description: 

	search.py 	Where all search algorithms will reside.
	searchAgents.py 	Where all search-based agents will reside.
	pacman.py 	The main file that runs Pacman games. This file describes a Pacman GameState type, which we use in this project.
	game.py 	The logic behind how the Pacman world works. This file describes several supporting types like AgentState, Agent, Direction, and Grid.
	util.py 	Useful data structures for implementing search algorithms.
	graphicsDisplay.py 	Graphics for Pacman
	graphicsUtils.py 	Support for Pacman graphics
	textDisplay.py 	ASCII graphics for Pacman
	ghostAgents.py 	Agents to control ghosts
	keyboardAgents.py 	Keyboard interfaces to control Pacman
	layout.py 	Code for reading layout files and storing their contents
	autograder.py 	Project autograder
	testParser.py 	Parses autograder test and solution files
	testClasses.py 	General autograding test classes
	test_cases/ 	Directory containing the test cases for each question
	searchTestClasses.py 	Project 1 specific autograding test classes

**************************************************************************
How to run

	To play the Pacman game type "python pacman.py"
	To Finding a Fixed Food Dot using Depth First Search type "python pacman.py -l bigMaze -z .5 -p SearchAgent"
	To Finding a Fixed Food Dot using Breadth First Search type "python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5"
	To Finding a Fixed Food Dot using Uniform Cost Search type "python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs"
	To Finding a Fixed Food Dot using A* Search type "python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic"
	To Get Pacman to eat all the dots type "python pacman.py -l trickySearch -p AStarFoodSearchAgent"

**************************************************************************
Note-

This Project is a part of a 3 part project to take the old arcade game MS PACMAN and use various A.I. techniques to achieve different results.

*************************************************************************