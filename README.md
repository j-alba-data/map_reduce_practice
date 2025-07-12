#### Purpose

This repo demonstrates the use of the map reduce library (mrjob), 
specifically the job module using the 'MRJob' class. The txt file contains 
repeats a few songs which the 'mapper' function yields a tuple for each line
that is a song name and the 'reducer' function yeilds a tuple of the sum of
the values for each key. 
