206 Project 1 - Code for playing cards

README



Your name:
 Benjamin Zeffer
Anyone you worked with: David Nguyen, Sadie Staudacher, Danielle Colbert, Ankita Avadhani, Mike Kim, Ava Randa



----- Add your README file content for the Project 1 code.



Overall Description:
	This is a recreational code which aims to replicate the classic card game: "War". The
	code pits two players against one another many times by randomly choosing cards from 
	each player's deck and playing them against each other unil one player reaches a
	certain number of wins, then program announces the winner as well as the final score.
	The program shows each "war" of two cards in the terminal and specifies who wins each
	time.

Class Card:
	instance -- a singular instance of class Card represents a literal card of some rank
		    and suit. The class Card "initializes" a ranking system for the deck of 
		    cards (created buy class Deck).
	input -- two inputs: suit (string) and rank (integer).
	methods -- init: initializes the ranking system with suits and ranks with the inputs.
		   str: returns a string twith the appropriate rank and suit of the card being
			created.

Class Deck:
	instance -- one instance creates a list which represents a deck of 52 cards each with
		    their own suits and ranks, and is sorted by these attributes.
	input -- no input needed for class Deck (to create a deck of cards).
	methods --

Class Hand:
	instance --
	input --
	methods --