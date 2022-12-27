# WORKFLOW OF THE NOTEBOOK:
1.	Text Cleaning and Preprocessing
2.	Article matching and Deep Cleaning
3.	Topic Extraction (Latent Dirichlet Allocation)
4.	T-SNE

# Text Cleaning and Preprocessing:
-	First, imported 10000 rows from the json file (“CORD-NER-full.json”). 
-	Converted the json data to csv and imported it.
-	Searched for articles published in the year 2020.
-	Dropped articles with missing abstract.
-	Dropped articles with duplicate abstract.
-	In abstract column:

    •	Converted text to lowercase.

    •	Removed non-English words.

    •	Removed Stopwords.

    •	Removed words with single characters.
  
-	Inverted index

# Article Matching and Deep Cleaning:
-	Created keyword list to filter out required articled only.
-	Filtered required articles and saved the index location in new dataframe. 
-	Used lemmatization and POS tagging technique to reduce ambiguity.
-	Created word cloud to check frequently used words or phrases in the corpus.

# Topic Extraction (Latent Dirichlet Allocation):

