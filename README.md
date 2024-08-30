# Poetry Generation with n-gram Language Modeling

## Overview
- This project involves generating poetry using n-gram language modeling techniques.

## Task Description
- The task is to print three stanzas of poetry with an empty line in between.
- The generation model is trained on a provided Poetry Corpus containing poems from renowned Urdu poets like Faiz, Ghalib, and Iqbal, along with other Urdu poetry scraped from the internet.

## Assignment Task
- Load the Poetry Corpus and tokenize it to split it into a list of words.
- Generate n-gram models, including unigram and bigram models.
- For each stanza:
  - For each verse:
    - Generate a random number of words in the range [7...10].
    - Select the first word randomly.
    - Select subsequent words until the verse is complete.
    - Attempt to rhyme the last word with the last word of the previous verse.
    - Print the verse.
  - Print an empty line after each stanza.

## Implementation Challenges
- Challenges include selecting subsequent words based on the first word chosen for the verse.
- Conditional Frequency Distribution (CFD) is used to predict the most probable next word.
- Rhyming the generated verses adds complexity, requiring the building of a rhyming dictionary.
- Considering the Urdu sentence structure from right to left, n-gram models are adapted accordingly.

## Standard n-gram Models
- Develop unigram, bigram, and trigram models using the Conditional Frequency Distribution method.
- Start by selecting the first word randomly and use the bigram model to generate subsequent words until the verse is complete.
- Compare the results of the two n-gram models.

This project showcases proficiency in natural language processing (NLP), specifically in generating poetry using n-gram language modeling techniques applied to Urdu language data.
