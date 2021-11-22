# What we will learn

- Python Regular Expression

- Shutil

The source of this summary [The first link](https://www.datacamp.com/community/tutorials/python-regular-expression-tutorial)

The source of this summary [The second link](https://pymotw.com/3/shutil/)

______________________________________

## Regular Expression

**A regular expression or often shortened as regex is a special sequence of characters that helps you match or find other strings or sets of strings, using a specialized syntax held in a pattern.The Python module re provides full support for Perl-like regular expressions in Python.**

### Regular Expressions in Python

*In Python, regular expressions are supported by the re module. That means that if you want to start using them in your Python scripts, you have to import this module with the help of import. The re library in Python provides several functions that make it a skill worth mastering.*

      import re

### We can use several functions provided by the re module

1. match() : returns a match object if the text matches the pattern. Otherwise, it returns None

2. search() : you scan through the given string/sequence, looking for the first location where the regular expression produces a match.

3. group() : returns the string matched by the re.

4. start() : Returns the starting index of the match.

5. end() : Returns the index where the match ends.

6. span() : Return a tuple containing the (start, end) positions of the match.

7. findall() : Finds all the possible matches in the entire sequence and returns them as a list of strings

8. split(): This splits the strings wherever the pattern matches and returns a list.


### Special Characters

* . - A period. Matches any single character except the newline character.
* ^ - A caret. Matches the start of the string.
* $ - Matches the end of string
* [abc] - Matches a or b or c
* [a-zA-Z0-9] - Matches any letter from (a to z) or (A to Z) or (0 to 9).
* \ - Backslash
     - If the character following the backslash is a recognized escape character, then the special meaning of the term is taken (Scenario 1)
     - Else if the character following the \ is not a recognized escape character, then the \ is treated like any other character and passed through (Scenario 2).
     - \ can be used in front of all the metacharacters to remove their special meaning (Scenario 3).
* \w - Lowercase 'w'. Matches any single letter, digit, or underscore.
* \W - Uppercase 'W'. Matches any character not part of \w (lowercase w).
* \s	Lowercase s. Matches a single whitespace character like: space, newline, tab, return.
* \S	Uppercase S. Matches any character not part of \s (lowercase s).
* \d	Lowercase d. Matches decimal digit 0-9.
* \D	Uppercase D. Matches any character that is not a decimal digit.
* \t	Lowercase t. Matches tab.
* \n	Lowercase n. Matches newline.
* \r	Lowercase r. Matches return.
* \b	Lowercase b. Matches only the beginning or end of the word.
* "+"	Checks if the preceding character appears one or more times.
* "*"	Checks if the preceding character appears zero or more times.
* ?	∙ Checks if the preceding character appears exactly zero or one time.
* ∙ Specifies a non-greedy version of +, *
* { }	Checks for an explicit number of times.
* ( )	Creates a group when performing matches.
* < >	Creates a named group when performing matches.

______________________________________

## shutil High-level File Operations

**The shutil in Python is a module that offers several functions to deal with operations on files and their collections. It provides the ability to copy and removal of files. In a way, it is similar to the OS Module; however, the OS Module does have functions dealing with collections of files.**

### Copy File

**copyfile() copies the contents of the source to the destination and raises IOError if it does not have permission to write to the destination file.**

### Copying File Metadata

**By default when a new file is created under Unix, it receives permissions based on the umask of the current user. To copy the permissions from one file to another, use copymode().**

### Working With Directory Trees

**shutil includes three functions for working with directory trees. To copy a directory from one place to another, use copytree(). It recurses through the source directory tree, copying files to the destination. The destination directory must not exist in advance.**

### Finding Files

**The which() function scans a search path looking for a named file. The typical use case is to find an executable program on the shell’s search path defined in the environment variable PATH.**

