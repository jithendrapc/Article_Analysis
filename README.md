# Article_Analysis
Objective:
The objective  is to extract textual data articles from the given URL and perform text analysis to compute variables that are defined below using data analysis and NLP.

Variables:
POSITIVE SCORE
NEGATIVE SCORE
POLARITY SCORE
SUBJECTIVITY SCORE
AVG SENTENCE LENGTH
PERCENTAGE OF COMPLEX WORDS
FOG INDEX
AVG NUMBER OF WORDS PER SENTENCE
COMPLEX WORD COUNT
WORD COUNT
SYLLABLE PER WORD
PERSONAL PRONOUNS
AVG WORD LENGTH

Workflow:

Data Extraction:
For each of the articles, given in the input.xlsx file, extracted the article text and save the extracted article in a text file with URL_ID as its file name.
While extracting text,  program extracts only the article title and the article text and  skipped the website header, footer, or anything other than the article text which are not considerable.

Data Analysis:
For each of the extracted texts from the article, performed textual analysis and computed variables and saved the output in  “Output Data Structure.xlsx”.



