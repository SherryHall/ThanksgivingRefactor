# ThanksgivingRefactor
Refactor blackjack to OOP and Createtown town for inheritance

BLACKJACK:
https://github.com/SherryHall/Blackjack-OOP.git

	Moved card class from Program to it's own class file.
	Added Shoe class to create and shuffle the deck, plus deal a card
	Added Player class to fix duplication between original dealer and player. Now create Players dealer and patron.
	Moved Players Turn logic to a method in Player, PatronPlays.
	Moved Dealers Turn logic to a method in Player, DealerPlays.
	Move winner logic to method in program.


CreateTown:
https://github.com/SherryHall/CreateTown2.git

	created abstract Building class to contain duplicate objects and methods
	changed House class to be a child of Building class, only contain unique items, and run constructors for House and Building.
	changed Bank class to be a child of Building class, only contain unique items, and run constructors for Bank and Building.
	changed School class to be a child of Building class, only contain unique items, and run constructors for School and Building.
