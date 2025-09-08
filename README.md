# keywords
A lex program to identify keywords

Description
This LEX program checks whether the given input string is a C keyword or not a keyword (identifier).

Keywords:
Predefined reserved words in C such as int, float, if, while, return, etc. These words cannot be used as variable names or identifiers.

Working of the Program:

The definition section defines a regular expression named keyword which includes all standard C keywords such as auto, int, return, while, etc.

The rules section consists of two rules:

1. If the input matches any of the words in keyword, it prints is a keyword.
2. If the input starts with an alphabet and is followed by letters or digits, it prints is not a keyword.
   
Sample Input:
int
hello
while
variable

Sample Output:
int is a keyword
hello is not a keyword
while is a keyword
variable is not a keyword
