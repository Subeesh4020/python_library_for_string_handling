README.txt

Introduction:- Python package to manage sentence / paragraph

Usage:- use pip to install wordslistpack pip install wordslistpack after installation you are ready to use the functions in this package.

e.g.,

to extract the words list from a sentence / paragraph, use the function 'get_words_list()'

from wordslistpack import wordslist

paragraph = """package to manage sentence or paragraph package to manage sentence or paragraph package to manage sentence or paragraph""" words = []

words = wordslist.get_words_list(paragraph)

Output:- ['package', 'to', 'manage', 'sentence', 'or', 'paragraph', 'package', 'to', 'manage', 'sentence', 'or', 'paragraph', 'package', 'to', 'manage', 'sentence', 'or', 'paragraph']