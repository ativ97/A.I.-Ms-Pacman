# Ghostbusters
Pacman spends his life running from ghosts, but things were not always so. Legend has it that many years ago, Pacman's great grandfather Grandpac learned to hunt ghosts for sport. However, he was blinded by his power and could only track ghosts by their banging and clanging.

In this project, I designed Pacman agents that use sensors to locate and eat invisible ghosts. It advance from locating single, stationary ghosts to hunting packs of multiple moving ghosts with ruthless efficiency.
The code for this project consists of several Python files.
Description: 

	bustersAgents.py 	Agents for playing the Ghostbusters variant of Pacman.
	inference.py 	Code for tracking ghosts over time using their sounds.
	busters.py 	The main entry to Ghostbusters (replacing Pacman.py)
	bustersGhostAgents.py 	New ghost agents for Ghostbusters
	distanceCalculator.py 	Computes maze distances
	game.py 	Inner workings and helper classes for Pacman
	ghostAgents.py 	Agents to control ghosts
	graphicsDisplay.py 	Graphics for Pacman
	graphicsUtils.py 	Support for Pacman graphics
	keyboardAgents.py 	Keyboard interfaces to control Pacman
	layout.py 	Code for reading layout files and storing their contents
	util.py 	Utility functions

**************************************************************************
How to run

	To play the Pacman game type "python pacman.py"
	To run Exact Inference Observation type "python autograder.py -q q1"
	To run Exact Inference with Time Elapse type "python autograder.py -q q2"
	To run Exact Inference Full Test type "python autograder.py -q q3"
	To run Approximate Inference Observation type "python autograder.py -q q4"
	To run Approximate Inference with Time Elapse type "python autograder.py -q q5"
	To run Joint Particle Filter Observation type "python autograder.py -q q6"
	To run Joint Particle Filter with Elapse Time type "python autograder.py -q q7"

**************************************************************************
Note-

This Project is a part of a 3 part project to take the old arcade game MS PACMAN and use various A.I. techniques to achieve different results.

*************************************************************************