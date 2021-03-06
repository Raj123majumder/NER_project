# Named-entity recognition (NER) </br>

NER is a subtask of information extraction that seeks to locate and classify named entities mentioned in unstructured text into pre-defined categories such as person names, organizations, locations, medical codes, time expressions, quantities, monetary values, percentages,etc.



# CRF MODEL<br>

Conditional random fields (CRFs) are a class of statistical modeling methods often applied in pattern recognition and machine learning and used for structured prediction. Whereas a classifier predicts a label for a single sample without considering "neighboring" samples, a CRF can take context into account. To do so, the prediction is modeled as a graphical model, which implements dependencies between the predictions. For example, in natural language processing, linear chain CRFs are popular, which implement sequential dependencies in the predictions.

# Character Embeddings<br>

As deep learning in NLP exploded, larger and larger vocabulary sizes where needed. Character and subword embeddings were an attempt to limit the size of embedding matrices. However, these types of embeddings do not encode the same deep sematics that word embeddings encode.Character embeddings are constructed in similar fashion to the way that word embeddings are constructed. However, instead of embedding at the word level, the vectors represent each character in a language. For example, instead a vector for "king", there would be a separate vector for each of the letters: "k", "i", "n", and "g". As mentioned these types of embeddings do not encode the same type of information that word embeddings contain. Instead, character level embedding can be thought of encoded lexical information and may be used to enhance or enrich word level emebddings.
* Able to handle new words and misspellings.
* The required embedding matrix is much smaller than what is required for word level embeddings.


<p align="center">
  <img width="390" height="400" src="PSvdx.png">
</p>

# Accuracy Report<br>
<p align="center">
  <img width="390" height="390" src="Screenshot 2021-11-02 at 10.09.50 PM.png">
</p>
<p align="center">
  <img width="390" height="390" src="Screenshot 2021-11-03 at 12.10.46 AM.png">
</p>
<p align="center">
  <img width="390" height="390" src="Screenshot 2021-11-03 at 12.11.58 AM.png">
</p>

# References<br>
* Towards Data Science - [here](https://towardsdatascience.com/besides-word-embedding-why-you-need-to-know-character-embedding-6096a34a3b10)
* Idea Based on - [Paper Link](https://aclanthology.org/N16-1030/)
* Dataset - [here](https://www.kaggle.com/namanj27/ner-dataset)
