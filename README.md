# Speech_to_ISL
Converts the given English Speech/Text to Indian Sign Language (ISL)

# Abstract

This project aims at creating a translation system that consists of a parsing module which parses the input English sentence to phrase structure grammar representation on which Indian sign language grammar rules are applied. This is done by eliminating stopwords from the reordered sentence. Stemming is applied to convert the words to their root form as Indian sign language does not support for inflections of the word. All words of the sentence are then checked against the words in the dictionary containing videos representing each of the words. If the words are not found in the dictionary, its corresponding synonym is used to replace it.

# Methodology

1. Input Speech / Text
2. Removal of Unwanted Symbols
3. Parsing
4. Stemming
5. Lemmatization
6. Stop Word Removal
7. ISL gloss to Video matching

# Future Works

Future aspects of the system could be improved by incorporating reverse functionality, such as an audio/text translation system for Indian Sign Language, which could pave the way for a two-way communication system. In order to improve the system's literacy and scope, the database could also be expanded.

# Useful Links

Standford Parser Link: https://nlp.stanford.edu/software/lex-parser.shtml

Indian Sign Language Videos Link: https://indiansignlanguage.org/


