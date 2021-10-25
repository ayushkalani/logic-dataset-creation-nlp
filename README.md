# Propositional Logical Questions & Answers Dataset Creation

Dataset Creation: Creating logical premises, and questions and answering for the the premise according to a set of propositional logic rule. We have used the [Conceptnet](https://conceptnet.io/) database to understand the meanings of words in natural language and the derive relations between them. 

 1. Conjunction 
 2. Addition 
 3. Composition 
 4. De Morgan's Law 1

# Dataset Creation


1) [Google Collab Notebook](https://colab.research.google.com/drive/1mGnhMOsSVj8f3HdGj4te11xqDyfXF1v_?usp=sharing)
2) Currently list of words are hardcoded, but can be extended to get list of nouns from wordnets or any other corpus
3) Work in progress. Currenlty at 383,141 question answers pair
4) Results are in CSV format with the headers- ['UUID','Rules','Context','Questions','Answers'] in the file Dataset5_AyushKalani.csv

5) Working Code, and able to make multiple contexts and questions. Can be run straight from the collab, no need of any input except the words which are hardcoded