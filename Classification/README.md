# Ghostbusters
In this project, I designed three classifiers: a perceptron classifier, a large-margin (MIRA) classifier, and a slightly modified perceptron classifier for behavioral cloning. I tested the first two classifiers on a set of scanned handwritten digit images, and the last on sets of recorded pacman games from various agents. Even with simple features, my classifiers will be able to do quite well on these tasks when given enough training data.

Optical character recognition (OCR) is the task of extracting text from image sources. The data set on which you will run my classifiers is a collection of handwritten numerical digits (0-9). This is a very commercially useful technology, similar to the technique used by the US post office to route mail by zip codes. There are systems that can perform with over 99% classification accuracy (see LeNet-5 for an example system in action).

Behavioral cloning is the task of learning to copy a behavior simply by observing examples of that behavior. In this project, I used this idea to mimic various pacman agents by using recorded games as training examples. My agent will then run the classifier at each action in order to try and determine which action would be taken by the observed agent.

The code for this project consists of several Python files.
Description: 


	data.zip 	Data file, including the digit and face data.
	naiveBayes.py 	The location where you will write your naive Bayes classifier.
	perceptron.py 	The location where you will write your perceptron classifier.
	mira.py 	The location where you will write your MIRA classifier.
	dataClassifier.py 	The wrapper code that will call your classifiers. You will also write your enhanced feature extractor here. You will also use this code to analyze the behavior of your classifier.
	answers.py 	Answer to Question 2 goes here.
	classificationMethod.py 	Abstract super class for the classifiers you will write.
	samples.py 	I/O code to read in the classification data.
	util.py 	Code defining some useful tools. You may be familiar with some of these by now, and they will save you a lot of time.
	mostFrequent.py 	A simple baseline classifier that just labels every instance as the most frequent class.

**************************************************************************
How to run

	To play the Pacman game type "python pacman.py"
	To run a perceptron classifier type "python dataClassifier.py -c perceptron"
	To run a MIRA classifier type "python dataClassifier.py -c mira --autotune"
	To run Digit Feature Design using Naive Bayes type "python dataClassifier.py -d digits -c naiveBayes -f -a -t 1000"
	To run Behavioral Cloning type "python dataClassifier.py -c perceptron -d pacman"

**************************************************************************
Note-

This Project is a part of a 3 part project to take the old arcade game MS PACMAN and use various A.I. techniques to achieve different results.

*************************************************************************