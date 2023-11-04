# codeWarsSolutions2

#1
----------------------
You've got a bunch of textual data with embedded phone numbers. Write a function area_code() that finds and returns just the area code portion of the phone number.

>>> message = "The supplier's phone number is (555) 867-5309"
>>> 
>>> area_code(message)
>>> //'555'

The returned area code should be a string, not a number. Every phone number is formatted like in the example, and the only non-alphanumeric characters in the string are apostrophes ' or the punctuation used in the phone number.

----------------------
#2
----------------------
rite a function, nicknameGenerator that takes a string name as an argument and returns the first 3 or 4 letters as a nickname.

If the 3rd letter is a consonant, return the first 3 letters.

nickname("Robert") //=> "Rob"

nickname("Kimberly") //=> "Kim"

nickname("Samantha") //=> "Sam"

If the 3rd letter is a vowel, return the first 4 letters.

nickname("Jeannie") //=> "Jean"

nickname("Douglas") //=> "Doug"

nickname("Gregory") //=> "Greg"

If the string is less than 4 characters, return "Error: Name too short".

Notes:

Vowels are "aeiou", so discount the letter "y".
Input will always be a string.
Input will always have the first letter capitalised and the rest lowercase (e.g. Sam).
The input can be modified

----------------------
#3
----------------------
Write a function that merges two sorted arrays into a single one. The arrays only contain integers. Also, the final outcome must be sorted and not have any duplicate.
