# Custom Tokenization using Regular Expressions
Provides a simple example showing how regular expressions can be used to create custom tokenization rules. This example defines a regular expression which is passed to the nltk.RegexpParser method to demonstrate how we can create custom text parsing.

## Overview
This example uses the natural language toolkit (NLTK) to preprocess a text input using word tokenization and part of speech tagging. Then a regular expression is defined to look for an optional determiner (DT), or possessive pronoun, followed by any number of adjectives, and then a noun. A second rule is also added which searches for proper nouns. Both of these rules are defined such that 'NP' (noun phrase) is returned when passed to the nltk.RegexpParser method.

## Example Input and Output
Here is a screenshot of the code with a sample input, and the resulting output.

![alt text](https://github.com/edwardsta/tokenization-regular-expressions/blob/master/NLP_RegExpToken.PNG)
