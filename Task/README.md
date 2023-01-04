# Notebook links:- 📑 https://www.kaggle.com/code/vitb19mim10100/covid19-cord-ner 

# https://www.kaggle.com/code/vitb19mim10100/covid-19-cord-ner-information-extraction-q-a

# i. WORKFLOW OF THE NOTEBOOK 1: (Covid19-CORD-NER)
1.	Text Cleaning and Preprocessing
2.	Article matching and Deep Cleaning
3.	Topic Extraction (Latent Dirichlet Allocation)
4.	T-SNE
5.  Semantic-Based Search

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
-	Built LDA model to extract topics and coherence model to check the c_v coherence score to select appropriate topic number.
-	Checked perplexity of my LDA Model.
-	Extracted meaning full words for topics.
-	LDA visualization.
-	Checked topic per document with bar graph.

# T-SNE:
-	Generated document topic matrix.
-	T-SNE clustering of LDA topics.

# Semantic-Based Search:
-	Duplicates and Null values.
-	Dropping non-English articles.
-	Spacy Parser and Tokenizer
-	Sentence Tokenization
-	Word2vec Training
-	Ranking documents
-	Saving the model and the dataframe

# ii. WORKFLOW OF MY NOTEBOOK 2: (COVID-19-CORD-NER-information-extraction-Q&A)
1.	NER Extraction from Text
2.	Dependency parses
3.	Question-Answering

# NER Extraction from Text:
-	spaCy based imports
-	NER extraction using Spacy library
-	Closer look at what spaCy is doing when it performs named entity recognition
-	Finding same entity texts

# Dependency parses:
-	Encoding grammatical information by using spaCy's dependency visualizer.
-	Identifying verbs + direct objects that are grammatically linked to a location.
-	Identifying all the actions related to a single city, Wuhan.

# Question-Answering:
-	Downloaded a transformer model that's already been trained on SQuAD from the Huggingface model repository.
-	Performed queries


# Results are available in 'Results' folder and in 'Report' folder ->.pdf.


