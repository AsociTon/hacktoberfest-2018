Objective : To implement operations of Binary Search Tree and carryout few performance studies.

Given a dataset containing records where each record has four fields namely, Year(Y), Totalcount(T),
Malecount(M), Femalecount(F), and Name (N).
A record in the dataset indicates, the number of male (M) and female (F) born with name N in a
given year Y. Totalcount (T) indicates the count of both male and female having the same name
in a specific year.
considered N name as a key and merge the duplicate names coming across the years. And
implement the following operations.

1. Build a binary search tree with the data in the dataset.
2. Search for a given name and display corresponding entries of the record.
3. Find a given name in the dataset.
4. Find the height of binary search tree.
5. Determine the depth of a given key in binary search tree.
6. Delete a specific record that is presented in binary search tree.
7. Find all names appearing in a given range.
8. Find most popular name in the dataset.

Source data file shall be made available through Moodles. All other input must be given through
command-line arguments. Input is case insensitive.
Executable file name: namedb

format of execution:
./namedb option [KEY] [KEY X..KEY Y]
option:
1. to search a given KEY
2. to display the height the tree
3. to display the depth of given KEY
4. to delete a specific KEY
5. to display the keys in specific range KEY X to KEY Y
6. to display most popular name
Arguments mentioned in [ ] brackets are optional. They are relevant for Options 1, 3, 4, and 5.


Example:
./namedb 1 “vijay kumar” - find the name “vijay kumar” in the database. If exists, print its
frequency.
./namedb 4 arun - delete the record with Key “arun”
./namedb 5 “arun” “vijay kumar” print all the names appearing in the range [“arun”, “vijay
kumar”]
Submission:
A single tar.gz named after your roll number (in lower case), containing all source files and a
Makefile.
