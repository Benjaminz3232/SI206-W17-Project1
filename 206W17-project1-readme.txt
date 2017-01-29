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
	instance -- a singular instance of class Card represents a literal card of some rank and suit. The class Card "initializes" a ranking system for the deck of cards (created buy class Deck).
	input -- two inputs: suit (string) and rank (integer).
	methods -- init: input is suit and rank (which are a defual of 0 and 2, respectively); initializes the ranking system with suits and ranks with the inputs.
		   str: no input (just self); returns a string twith the appropriate rank and suit of the card being created.

Class Deck:
	instance -- one instance creates a list which represents a deck of 52 cards each with their own suits and ranks, and is sorted by these attributes.
	input -- no input needed for class Deck (to create a deck of cards), and depends on from the Card class created above it.
	methods -- init: no inputs (just self); creates a sorted list of cards by value (suit and rank).
		   str: no inputs (just self); returns a multi-line string listing each card, shows up in whatever order the cards are in.
		   pop_card: optional input is referring to the last card in the list; removes and returns the card from the deck with the default being the last card in the deck, this card will no be longer in the deck -- it's been taken out.
		   shuffle: no inputs(just self); it randomly sorts the list of cards in the deck.
		   replace_card: input of card; for each card in the list it will append that card to the list card_strs in case it was removed from the pop_card method.
		   sort_cards: no inputs (just self); remakes the deck in a sorted way (assuming you cannot have more than the normal 52 cars in a deck).

Class Hand:
	instance -- represents a hand of cards for the game, with basic functionality (number of cards) attribute.
	input -- same inputs as the init method (see init method inputs below).
	methods -- init: The init method takes in a deck and automatically 5 cards. It creates a hand, with the number of cards that are passed in from the deck class and card class used earlier.
		   place_card: optional input represents the first card in the hand; basically the same as pop_card method from the class Deck, but referencing the HAND's cards.
		   get_suits_available: no input (just self); returns a list of all the suits thgat are in the hand.
		   get_ranks_available: no input (just self); returns list of all the ranks that are in the hand.
		   specific_card: 2 inputs, suit (string) and rank (int); look for a specific card in the hand and return it if it's there.
		   add_card: input of a card; add card to hand (if there is no identical one, assuming working with 1 deck here).
		   str: takes no input; returns a multi-line string listing each card.









