# Regex-Explainer

Hello this is a tutorial on regex which is used to give a computer specific inputs or to tell it to do something very specific



## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
anchors are used to to tell the computer where specificly a string would be affected or a pattern to look for
### Quantifiers
a quantifire tells the computer how manytimes it should preform and operation on certian code
### Grouping Constructs
a grouping consturuct helps a regular expresion see a input string
### Bracket Expressions
bracket expression indicate a set of characters to match

"car".match(/[abcd]/) // -> matches 'a'

the letters within the bracket are looking for the abcd whitch then find an a
### Character Classes
character classes will search for characters that are within it to match them

in this example gr[ae]y which as an input it looks for grey or gray
### The OR Operator
with a or operator we can receive only certain strings as an input

^I like (dogs|penguins), but not (lions|tigers).$

with our example for the first part we have an option for either dogs or penguins the second field has to different answers but the same operation
### Flags
 
a flag is a regex that tells the computer to search different 

like using "i" means to ignore casing or "g" lets the regex search globally

### Character Escapes

character escapes deal with telling regex to exclude certian parts of strings

## Author


hey the name is junior cabriales im a front end dev and you can find my github at https://github.com/Jacksonwolfd20
