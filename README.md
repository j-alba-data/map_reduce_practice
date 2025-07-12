#### Purpose

This repo demonstrates the use of the map reduce library (mrjob), 
specifically the job module using the 'MRJob' class. The txt file contains 
repeats of a few songs which the 'mapper' function yields a tuple for each line
which is a song name and the 'reducer' function yields a tuple of the sum of
the values for each key. 
