# DigitsWordsdMap

## Question

Digits on a phone have a list of letters associated with them. For example, 2 can be 'A', 'B', or 'C'. Phone numbers can be expressed as letters, which makes them easier to remember. For instance, 2655328 maps to COLLECT.
Write a function that takes a phone number as a string (e.g. "3278227") and prints words that can be made with the phone number. Find translations that are made up of one or more words which are at least 3 characters long. 

Example:

Dict: ['FASTCAR', 'FAST','CAR', 'VISITED']

Input: "3278227" , Output: [['FAST','CAR'], ['FASTCAR']]

Input: "8474833" , Output: [['VISITED']]

## File Description:

`utils.py`: some utils to do jobs while initialize variables like digits-chars mapping.

`constants.py`: constants of the question

`tree.py`: simple tree structure implements.

`digits_words_map.py`: main function of this question.

`tests.py`: unit tests which are used to verify the answer.