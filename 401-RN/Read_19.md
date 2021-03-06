# Python Regular Expression

> *Regular Expressions, regex, are a sequence of characters used to check whether a pattern exists in a given text (string) or not.* 

**If you've ever used search engines, search and replace tools of word processors and text editors you've already seen regular expressions in use.**

> > *we can use them at the server side to validate the format of email addresses or passwords during registration, used for parsing text data files to find, replace, or delete certain string, etc.* 
*They help in manipulating textual data, which is often a prerequisite for data science projects involving text mining.*

* *In Python, regular expressions are supported by the re module. That means that if you want to start using them in your Python scripts, you have to import this module with the help of import*

___

## Basic Patterns: Ordinary Characters

> *The match() function returns a match object if the text matches the pattern. Otherwise, it returns None. The re module also contains several other functions, and you will learn some of them later on in the tutorial.*



___
## Wild Card Characters: Special Characters

> *With the search function, you scan through the given string/sequence, looking for the first location where the regular expression produces a match.The group function returns the string matched by the re. You will see both these functions in more detail later.*


*If the character following the backslash is a recognized escape character, then the special meaning of the term is taken (Scenario 1)Else if the character following the \ is not a recognized escape character, then the \ is treated like any other character and passed through (Scenario 2).\ can be used in front of all the metacharacters to remove their special meaning (Scenario 3).*


* **\w** - *Lowercase 'w'*. Matches any single letter, digit, or underscore.
* **\W** - *Uppercase 'W'*. Matches any character not part of \w (lowercase w).

* **\s** - *Lowercase 's'*. Matches a single whitespace character like: space, newline, tab, return.
* **\S** - *Uppercase 'S'*. Matches any character not part of \s (lowercase s).


* **\d** - *Lowercase 'd'.* Matches decimal digit 0-9.
* **\D** - *Uppercase 'd'.* Matches any character that is not a decimal digit.

___
## Repetitions : 

> *It becomes quite tedious if you are looking to find long patterns in a sequence. Fortunately, the re module handles repetitions using the following special characters:*

> > *Checks if the preceding character appears one or more times starting from that position.*

___
## Grouping in Regular Expressions

> *The group feature of regular expression allows you to pick up parts of the matching text. Parts of a regular expression pattern bounded by parenthesis () are called groups. The parenthesis does.* 

*Not change what the expression matches, but rather forms groups within the matched sequence. You have been using the group() function all along in this tutorial's examples. The plain match.group() without any argument is still the whole matched text as usual.*

