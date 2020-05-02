# Answer to question 17

**Question 17**

Build a system to predict the language a text is written in.

**Answer**

NLI is not easy task..

Steps
1) Create tf-idf vectorizor for each n gram.
TfidfVectorizer(analyzer='char', ngram_range=(1,3)). Character level ngram. ngram is independant of the word boundary. 


2) Apply Naives bays or other advanced methods. 
