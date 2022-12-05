# Exam2
Quick notes: I haven't actually used github before so I'm not sure how to import files. I did all the coding on a different software. In the dropbox, I also attached the .java file and the 4 txt testfiles that I made

a)
  numbers = [0-9]
  letters = [a-z]*[A-Za-z0-9_]*
  whitespace = \\s+
  punctuation = (?=\\p{Punct})|(?<=\\p{Punct})
  quotations = (?=([^\"]*\"[^\"]*\")*[^\"]*$)
  
b) For operations, I would have to do parentheses first, then multiplication/division/module, then addition/subtraction.
Comparing comes after that (<, >, <=, >=, ==, !=)

c) coding
d) coding
e) in code
f) in code

g) I included text files in dropbox and provided the contents in the .md file
* lexical error - sequence of characters that doesnt match the pattern of any token.
  - exceed length of identifier/numeric constants
	- appearance of illegal character (ex: $ after ;)
	- unmatched string (ex: forgot to close comment /*)
	- spelling error (ex: int 3num -> identifier cant start with a number)
	- replace character w/ incorrect character (ex: int x = 1$2 -> $ doesnt belong)
	- remove char that should be present (ex: include <#iostream> -> missing o)
* syntactical (syntax) error - deal more w/ coding basic
	- incorrect capitalization (ex: capitalize keywords/class names/variables)
	- missing () or {}
	- forgetting to import a class
	- splitting string over 2 lines (will object if string contains newline character)
	- treating static method as instance method
	- forgetting class/object name as part of method call
	- omitting break clause from switch statements or return statement
	- mistyping header for main() method
To make it easier to implement:
For lexical error, I only show spelling error (ex: int 3num -> identifier cant start with a number)
For syntax error, I only show missing "", {}, and ()

h) incomplete
