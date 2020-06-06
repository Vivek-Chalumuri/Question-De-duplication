# General Instructions


	1. To run infersent notebbok, you have to first clone the infersent repo by facebbok research:
			- git clone https://github.com/facebookresearch/InferSent.git

	2. You would also need fastText word embeddings
			- can be downloaded from here https://fasttext.cc/docs/en/english-vectors.html

	3. To generate string features, we use libraries like fuzzywuzzy and python-Levenshtein
			- pip install fuzzywuzzy
			- pip install python-Levenshtein
		They help in very efficient calculations of Levenshtein distance, when compared to other libraries

	4. Nlp features are generated using the library: 
			- Spacy
	5. Deeplearning part is explored with the library:
			- Keras (Tensorflow backend)
	6. XGBoost is another algorithm we used but for efficient working of the algorithm, multiple parameters in the system environment are needed to be tuned:
			- We recommend using Randomforest or Simple DNN for InferSent experiments which are also included in the same notebook.
    7. Lastly, simple install and import any other required relevant libaries if prompted
    
	A typical python 3.x installation (with Anaconda could be much easier) along with Scikit-learn library should be enough for any other requirement.