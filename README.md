## Handy Shell Scripts

### Trim
Useful when you want to see the first few lines of another command. You can pipe the outputs to it like this:

`seq 100 | trim`

`1
2
3
4
5
... with 95 lines remaining`

It takes an optional arg to show the desired number of lines.


### Valcount
It acts like .value_counts() method in pandas; tells you the number of each unique value in stdin.

`echo "hi\nbye\nhi\nhi" | valcount`

`3 hi
1 bye`


