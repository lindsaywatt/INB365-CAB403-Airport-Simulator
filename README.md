Airport-Simulator
=================

INB365 - Systems Programming - Queensland University of Technology

Airport Simulator - Assignment 1 - 2014
(Producer/Consumer Example)

Created By - Lindsay Watt


Dependancies required to compile the AirportSimulator:  
	 AirportSimulator.c  
	 AirportSimLib.c   
	 airportsim.h  
	 Makefile


To compile, run 'make && make clean' command in the dependancy directory.

To run the AirportSimulator, usage is:

"./AirportSimulator <probability of producing a plane to land> <probability of selecting a plane to takeoff>"

Where the probabilities are integers between 1 and 90 inclusive.

pressing 'p' or 'P' followed by enter while AirportSimulator is running will print the current state of the airport parking.

pressing 'q' or 'Q' followed by enter while AirportSimulator is running will terminate the program, and print the final state of the airport parking.

