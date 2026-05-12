# Problem Set Unit 5

## Create a Text Analyzer:



### Option 1: Basic Text Analyzer (80%)

Create a text analyzer program where the user inputs a sentence or paragraph and the program analyzes the text.</br>
The program must follow the following specifications:</br>

Display a welcome message.</br>
Ask the user to input a sentence or paragraph.</br>
Count and output:</br>

  - Total number of characters
  - Total number of words
  - Total number of vowels
  - Total number of spaces
  - All unique words and how many times they occur.
  - Ignore capitalization when counting words. For example, "Java" and "java" should count as the same word.

Do not forget to comment and document your code!

Example Run:

```
Welcome to the Text Analyzer.

Please enter a sentence or paragraph: Java is fun and java is powerful.

Total Characters: 37
Total Words: 7
Total Vowels: 12
Total Spaces: 6

Word Frequency:

java - 2
is - 2
fun - 1
and - 1
powerful - 1
```

### Option 2: Remove Punctuation and Ignore Common Words (+10%)

Do all of the above but add one extra feature.</br>
Before analyzing the text, remove punctuation from all words.</br>

For example:

  - "hello,"
  - "hello!"
  - "hello."

should all count as:

  - "hello"

Also ignore the following words for the purpose of word frequency:

  - the
  - a
  - an
  - and
  - is

Example Run:

```
Welcome to the Text Analyzer.

Please enter a sentence or paragraph:

Hello, hello! Java programming is fun.

Total Characters: 40
Total Words: 6
Total Vowels: 12
Total Spaces: 5

Word Frequency:

hello - 2
java - 1
programming - 1
is - 1
fun - 1
```

### Option 3: Advanced Statistics (+10%)

In Option 3, do all of the above options plus add more statistics about the text.

Add the following features:

  - Output the longest word
  - Output the shortest word
  - Output the average word length
  - Output the number of sentences
  - Output how many unique words there are

If there are multiple longest, or shortest you must output all of them.

Example Run:

```
Welcome to the Text Analyzer.

Please enter a sentence or paragraph:

Data structures and algorithms are important. Data is powerful.

Total Characters: 64
Total Words: 9
Total Vowels: 22
Total Spaces: 8

Word Frequency:

data - 2
structures - 1
and - 1
algorithms - 1
are - 1
important - 1
is - 1
powerful - 1

Longest Word: algorithms, structures
Shortest Word: is
Average Word Length: 6.00
Number of Sentences: 2
Unique Words: 8
```
