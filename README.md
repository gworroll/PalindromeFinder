This is my submission for the Reddit Daily Programmer Easy Challenge #232, which was to test for 
palindromes. The bonus involved a large wordlist in which we were to find the number of two word
palindromes we could make from this list.

It finishes in just over 15 seconds using tries to speed up comparisons by only testing words where
the combination word matches the first and last, as well as the second and second to last, letters. 
It also uses the multiprocessing module to leverage multiple CPU cores to further speed up the checks.
