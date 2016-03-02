# Stats

### Description
This shell script gives the average and median values of each row of scores given as input to the program. This script can also be used to calculate the average and median values of each column of the given input. Input can be given as an input file or as standard input where the user enters values to be calculated over manually. The format of the input files must be as follows:

> a1 a2 a3 a4 ... an<br>
> b1 b2 b3 b4 ... bn<br>
> c1 c2 c3 c4 ... cn<br>
> .&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.<br>
> .&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.<br>
> .&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.<br>
> m1 m2 m3 m4 ... mn<br>

where all of the above characters [a1, mn] represent integers [0, 9].
There must be an equal number of values contained in each row. Each 
value must be separated by whitespace.
 
The script is run with the following syntax:

> stats {-rows|-cols} [input_file]

If the input_file is not given, standard input is the default method
of input entry, input terminated by entering 0 <Enter>.
