
How to run the code :
-------------------

	step 1:
	------
	
		1. The files have been saved as: AB_bot.cpp, MinMax_bot.cpp, AB_bot.so, MinMax_bot.so


	step 2:
	------
		To generate .so files,

	a. Change Lines 9, 10 in Makefile from MyBot to MinMax_bot and bot.so to MinMax_bot.so, to generate MinMax_bot.so file.

	b. Change Lines 9, 10 in Makefile from MyBot to AB_bot and bot.so to AB_bot.so, to generate AB_bot.so file.


	step 3:
	-------
		Command to play game amongst Minimax and Alpha Beta bots:

		$./bin/Desdemona ./<path to MinMax_bot.so file> ./<path to AB_bot.so file>

	step 4:
	-------	
		To print the game board after every move use this command:

		$./bin/Desdemona -v ./<path to MinMax_bot.so file> ./<path to AB_bot.so file>

Authors :
-------

-   [@chidaksh](https://github.com/chidaksh)
-   [@krupakar](https://github.com/Sai-Krupakar)
