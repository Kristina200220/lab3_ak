#### Лабороторна робота №3
Simple program for simple list manipulation.
### Використання
## --help (-h)
Simply showing the manual for the program.
# Example
./simple_program --help
## --version (-v) 
Simply showing program version.
# Example
./simple_program --version
## --create (-i)
Simply creation of a list of numbers.
# Example
./simple_program -i1,2,3
./simple_program -create=1,2,3
## --sum (-s)
Simply summing the first n members in the list (all if n is not specified).
# Example
./simple_program --create=1,2,3 --sum
./simple_program --create=1,2,3 -s2
## --count (-c)
Simply counting the number of members in the list.
# Example
./simple_program -i1,2,3 -c
## --reverse (-r)
Simply reversing order of all members in the list.
# Example
./simple_program -i1,2,3 -r
