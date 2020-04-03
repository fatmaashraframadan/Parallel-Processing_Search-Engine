# Parallel-Processing_Search-Engine

Search Engine Helper:   Write a parallel program to search a given corpus and return the most relevant search results. You are given a corpus called Aristo Mini Corpus (https://www.kaggle.com/allenai/aristo-mini-corpus). 
 
Aristo Mini Corpus: 
 
The Aristo Mini corpus contains 1,197,377 science-relevant sentences drawn from public data. It provides simple science-relevant text that may be useful to help answer elementary science questions. You will work on 1500 sentence only divided across 50 File, each file is 30 lines. 
 
Input: a given query in form of a sentence or a question. Output: search results that contain all the words of the query. 
 
Example: 
 
Search query: Capital of Egypt 
 
If the corpus has the following sentences: 
 
File1: There is a capital for each country. Capital of Egypt is Cairo. 
 
File2: The Capital of Egypt is Cairo. You can visit the country you want. 
 
Output should be: 
 
Capital of Egypt is Cairo. 
 

 
The Capital of Egypt is Cairo. 
 
 
Pseudo code of search steps applied for each file: 
 
For each Sentence in File:  Match = true; For each word in the query: IF word not in CurrentSentence: MatchScore = false;   IF MatchingScore is true:    Store Sentence;              ResultsFound += 1; 
 
