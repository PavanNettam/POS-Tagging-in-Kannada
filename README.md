--------------------------------------------------------------------------
README - SUPERVISED
--------------------------------------------------------------------------

Filename	 	- ./supervised.py

Description	- HMM based POS tagger using supervised learning technique.

Usage		- python supervised.py <language> <test_file_path> 
	
Run it as 	- python supervised.py 2 ./data/kannada_testing.txt
		
Output		- ./output/<language>_tags.txt
		- For each word in test file, <word>_<tag> will be printed in output file.

Argument Details
 		~ 2 - Kannada


	-- "test_file_path"

		~ Path of the file that contains testing sentences.
		~ Each line should contain one sentence.
		~ See ./data/kannada_testing.txt for reference.


--------------------------------------------------------------------------
