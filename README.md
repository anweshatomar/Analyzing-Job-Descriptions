# Analyzing Job Descriptions from different fields:

### Method used:
- Extracted the content from each job description. Then elimnate noise by lower casing all the letter and elimnating the punctuations.
- Then tokenize the content and get rid of all the stop words.
- Lemmatize the tokens.
- Performed the same operation for reuters also.

### Comparing the lists of tokens:
- After generating two lists, each containing tokens for the documents, compared the two.
- Comparision using for and if loops.
- And generat a final list of jargon words.
- The method was successful in identifying most of the jargon words, but there are still a few words in the list that would not be considered jargon.


### Imprving the method:
- There are 268 words in the list of jargon.
- Despite elimnating punctuations, the list contains a few punctuations.
- Certain words like "answered", "calculator" and "georgetown" are also a part of the jargon list.
- Use a larger set of files or possibly a file that has a wider variety of information for comparision, in order to elimnate such words.
- In this method I have not used bigrams for analysis, my next step would probably involve exploring bigrams.
- Furthermore, I may look into some cross validation process, since there may be certain jargon words that the algorithm did not pick up on.
