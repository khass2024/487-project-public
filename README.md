# Guess the Semantically Similar Word!
Final Project of EECS 487 (Natural Language Processing) @ University of Michigan-Ann Arbor<br/>
Contributors: Kevin Hass, Arnav Mittal, Hyungu Yoon

## How to play 

Download the repository and run all the cells in the final_project.ipynb file. <br/><br/>
If you want to play with GPT embedding, enter your OpenAI API key into the final_project.ipynb file.

## Introduction

Our project's goal was to create a word game that leverages the semantic meaning of words, allowing players to guess a secret word. The motivation behind this project was to explore the potential of word embeddings in NLP and to create a fun, educational game that appeals to a wide audience.<br/>

## Game Mechanics

Gameplay: Players attempt to guess a secret word. Each guess is turned into a vector embedding.<br/>
Scoring: The game calculates the cosine similarity between the guessed word and the secret word.<br/>
Progress Tracking: Each guess and its similarity score are recorded.<br/>
Winning Condition: The game continues until the secret word is guessed or the player gives up.<br/>

## Reference and Inspiration

Our inspiration was Semantle, a word game focused on semantic meanings rather than spellings.<br/>

## Methodology

Enhancements: Integration of different word embeddings, game mechanic refinements, and user-friendly features.<br/>
Category Selection: Players choose a category at the start to narrow down the target word scope.<br/>
Hint Mechanisms: Two types of hints - hypernym hints and halfway words.<br/>
Word Embeddings: GloVe and GPT models were used, with GPT showing better performance.<br/>
