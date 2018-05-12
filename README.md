# Spell-Checker

Goal :
Create a spell checker: correct spelling of a corrupted word

Steps:
1. Train a language model on training data.
2. Use the model to predict the outputs (correct spelling) for the test data (corrupted words).
3. Upload your prediction as a file to the in class Kaggle competition for evaluation and ranking .


Model: 
Generate all the words from misspelled word x with an edit distance of 0, 1 & 2 including insertions, deletions, and substitutions. 
Also, use transpositions for generating the words (called as Damerau-Levenshtein edit distance). 
After generating all the candidate words, select the word w which has the maximum number of occurrences (probability) in your original dataset, as the correct word.


Kaggle Link:
https://www.kaggle.com/t/224c05a5c9924eaaaa5c826e76e65c44 

Score:0.22946
Rank:8 out of 37 teams
