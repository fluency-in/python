# Python Exercises

Each subdirectory in this repository is an exercise.

Each exercise consists of a README.md and some automated tests.

To work on an exercise, change to the directory of the exercise:

    cd hello-world

This contains the files for the exercise.

    .
    ├── README.md
    └── hello_world_test.py

To run a test file, pass it as an argument to the `python` command:

    python hello_world_test.py

If you want to stop the tests after the first failure, then you can use the pytest library.

Install pytest with pip:

    pip install pytest

Run the tests with the `py.test` command using the `-x` flag to exit after the first failure.

    py.test -x hello_world_test.py



## Exercises

These are ordered roughly in order of difficulty.
The README.md file for each exercise explains in more detail what the exercise is about.

  **leap**
  Write a program that will take a year and report if it is a leap year.

  **clock**
  Implement a clock that handles times without dates.

  **pangram**
  Determine if a sentence is a pangram.

  **rna-transcription**
  Write a program that, given a DNA strand, returns its RNA complement (per RNA transcription).

  **hamming**
  Write a program that can calculate the Hamming difference between two DNA strands.

  **word-count**
  Write a program that given a phrase can count the occurrences of each word in that phrase.

  **gigasecond**
  Write a program that calculates the moment when someone has lived for 10^9 seconds.

  **bob**
  Bob is a lackadaisical teenager. In conversation, his responses are very limited.

  **run-length-encoding**
  Implement run-length encoding and decoding.

  **meetup**
  Calculate the date of meetups.

  **difference-of-squares**
  Find the difference between the sum of the squares and the square of the sums of the first N natural numbers.

  **anagram**
  Write a program that, given a word and a list of possible anagrams, selects the correct sublist.

  **allergies**
  Write a program that, given a person's allergy score, can tell them whether or not they're allergic to a given item, and their full list of allergies.

  **series**
  Write a program that will take a string of digits and give you all the contiguous substrings of length `n` in that string.

  **robot-simulator**
  Write a robot simulator.

  **sieve**
  Write a program that uses the Sieve of Eratosthenes to find all the primes from 2 up to a given number.

  **atbash-cipher**
  Create an implementation of the atbash cipher, an ancient encryption system created in the Middle East.

  **sum-of-multiples**
  Write a program that, given a number, can find the sum of all the multiples of particular numbers up to but not including that number.

  **acronym**
  Convert a long phrase to its acronym

  **say**
  Write a program that will take a number from 0 to 999,999,999,999 and spell out that number in English.

  **largest-series-product**
  Write a program that, when given a string of digits, can calculate the largest product for a contiguous substring of digits of length n.

  **kindergarten-garden**
  Write a program that, given a diagram, can tell you which plants each child in the kindergarten class is responsible for.

  **grade-school**
  Write a small archiving program that stores students' names along with the grade that they are in.

  **roman-numerals**
  Write a function to convert from normal numbers to Roman Numerals.

  **space-age**
  Write a program that, given an age in seconds, calculates how old someone is in terms of a given planet's solar years.

  **grains**
  Write a program that calculates the number of grains of wheat on a chessboard given that the number on each square doubles.

  **luhn**
  Write a program that can take a number and determine whether or not it is valid per the Luhn formula.

  **etl**
  We are going to do the `Transform` step of an Extract-Transform-Load.

  **prime-factors**
  Compute the prime factors of a given natural number.

  **pig-latin**
  Implement a program that translates from English to Pig Latin

  **simple-cipher**
  Implement a simple shift cipher like Caesar and a more secure substitution cipher

  **scrabble-score**
  Write a program that, given a word, computes the scrabble score for that word.

  **crypto-square**
  Implement the classic method for composing secret messages called a square code.

  **sublist**
  Write a function to determine if a list is a sublist of another list.

  **pythagorean-triplet**
  There exists exactly one Pythagorean triplet for which a + b + c = 1000. Find the product a * b * c.

  **circular-buffer**
  A data structure that uses a single, fixed-size buffer as if it were connected end-to-end.

  **robot-name**
  Write a program that manages robot factory settings.

  **matrix**
  Write a program that, given a string representing a matrix of numbers, can return the rows and columns of that matrix.

  **rail-fence-cipher**
  Implement encoding and decoding for the rail fence cipher.

  **nth-prime**
  Write a program that can tell you what the nth prime is.

  **saddle-points**
  Write a program that detects saddle points in a matrix.

  **beer-song**
  Write a program which produces the lyrics to that beloved classic, that field-trip favorite: 99 Bottles of Beer on the Wall.

  **perfect-numbers**
  The Greek mathematician Nicomachus devised a classification scheme for natural numbers.

  **secret-handshake**
  Write a program that will take a decimal number, and convert it to the appropriate sequence of events for a secret handshake.

  **twelve-days**
  Write a program that outputs the lyrics to 'The Twelve Days of Christmas'

  **binary**
  Write a program that will convert a binary number, represented as a string (e.g. '101010'), to its decimal equivalent using first principles

  **palindrome-products**
  Write a program that can detect palindrome products in a given range.

  **bracket-push**
  Make sure the brackets and braces all match.

  **hexadecimal**
  Write a program that will convert a hexadecimal number, represented as a string (e.g. "10af8c"), to its decimal equivalent using first principles (i.e. no, you may not use built-in or external libraries to accomplish the conversion).

  **minesweeper**
  Write a program that adds the numbers to a minesweeper board

  **queen-attack**
  Write a program that positions two queens on a chess board and indicates whether or not they are positioned so that they can attack each other.

  **wordy**
  Write a program that takes a word problem and returns the answer as an integer.

  **phone-number**
  Write a program that cleans up user-entered phone numbers so that they can be sent SMS messages.

  **ocr-numbers**
  Write a program that, given a 3 x 4 grid of pipes, underscores, and spaces, can determine which number is represented, or whether it is garbled.

  **house**
  Write a program that outputs the nursery rhyme 'This is the House that Jack Built'.

  **triangle**
  Write a program that can tell you if a triangle is equilateral, isosceles, or scalene.

  **poker**
  Pick the best hand(s) from a list of poker hands.

  **zebra-puzzle**
  Write a program that solves the zebra puzzle.

  **rectangles**
  Count the rectangles in an ASCII diagram.


## Source

These exercises are from the [Python][python] track on [Exercism][exercism]

[exercism]: http://exercism.io
[python]: http://exercism.io/languages/python
