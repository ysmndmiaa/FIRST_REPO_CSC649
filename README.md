# CSC649 Setup - Word and Character Counter

## What program does
Asks the user to enter a sentence, then displays the word count and
character count (including spaces). If the input is empty, it shows a
message instead.

## How to run it
1. Open the project in PyCharm (Python 3.12, .venv).
2. Open main.py and click Run 'main'.
3. Type a sentence in the Run window and press Enter.

## Test results
| Test | Input | Output |
|---|---|---|
| Normal sentence | "Hello World" | Word count: 2, Character count: 11 |
| Empty input | (just Enter) | You did not enter a sentence. |
| Extra spaces | "  hello  world  " | Word count: 2, Character count: 16 |

## Limitation
The program counts words by splitting on spaces only, so punctuation
attached to a word is counted as part of that word (e.g. "hello,world"
counts as 1 word, and a standalone "!" counts as 1 word)."# FIRST_REPO_CSC649" 
