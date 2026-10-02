# CSC649 Setup - Word and Character Counter

## What it does
Asks the user to enter a sentence, then displays the word count and
character count (including spaces). If the input is empty, it shows a
message instead.

## How to run
1. Open the project in PyCharm (Python 3.12, .venv).
2. Open main.py and click Run 'main'.
3. Type a sentence in the Run window and press Enter.

## Test results
| Test | Input | Output |
|---|---|---|
| Normal sentence | I love Python | Word count: 3, Character count: 13 |
| Empty input | (just Enter) | You did not enter a sentence. |
| Extra spaces | "  hello   world  " | Word count: 2, Character count: 17 |

## Limitation
The character count includes leading and trailing spaces, and punctuation
is counted as part of words, so the counts may not match what a user expects.