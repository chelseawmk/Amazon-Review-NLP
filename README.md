# Amazon-Review-NLP

Use NLTK and classification method to predict amazon review ratings.

1. Data preprocessing for Text data. <br>
  * Unified cases and removal of stop words. <br>
  * Remove negations (split off 'n't' convert to not)<br>
  * Stem all words using Porter 1979 <br>
2. Review Data Vectorization. <br>
  * Create words frequency count table and use the top frequent words to define the word vector
  * Create a bag-of-word vector in representation for each review <br>
3. Build Ordinal Logistic Regression to predict review ratings (On a scale of 1 to 5). 
4. Model evaluation and Result Intpretation. 
