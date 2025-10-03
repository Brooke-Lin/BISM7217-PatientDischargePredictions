**Clinical Notes Text Mining**
-

**Overview**
-
This project focuses on text mining and machine learning analysis of clinician notes. It was completed as part of my university coursework.


**Features**
-
The analysis applies natural language processing (NLP) techniques to clean, process, and extract insights from unstructured clinical text. Key tasks include:

* Text preprocessing (tokenization, stopword removal, lemmatization, stemming)

* Feature generation (n-grams, TF-IDF, sentiment analysis, dimensionality reduction with SVD)

* Topic modeling using Latent Dirichlet Allocation (LDA)

* Visualization (word clouds, n-gram frequency distribution, topic profiling)

**Tecnologies and Libraries Used**
-
* Python (Pandas, NumPy, Matplotlib, Scikit-learn)
* NLTK (tokenization, stopwords, lemmatization, stemming, n-grams)
* Gensim (LDA topic modeling, coherence score)
* VADER Sentiment Analysis
* WordCloud for visualization
* PyLDAvis for interactive topic visualization

**Dataset**
-
The dataset (A2_Data.csv) contains clinical notes and related attributes, such as Patient_ID, Clinician_Note, AHRQ Elixhauser Score, Van Walraven Elixhauser Score, and Discharge_Decision.

**Methodology**
-
1. Data Cleaning: Remove null values, punctuation, and noise
2. Text Preprocessing: Tokenization, stopword removal (with custom stopwords), lemmatization, and stemming
3. Feature Engineering: N-grams (frequent word pairs), TF-IDF for term importance, Sentiment scores (compound polarity), and Dimensionality reduction (SVD)
4. Topic Modeling: LDA with 3 topics extracted, Coherence score evaluation, and Topic profiling with WordClouds

**Results and Insights**
-
* N-grams: "continue home" and "transit issue" were the most frequent phrases.
* Sentiment: Most clinician notes had an overall positive sentiment (compound score ~0.97).
* Topic Modeling: 
  * Topic 0: Pain, home care, and medical stability.
  * Topic 1: Continuity of care, follow-up, outpatient concerns.
  * Topic 2: Pain management, family context, symptom improvement.




