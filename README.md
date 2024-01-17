AMAZON FINE FOOD REVIEWS: TEXT CLASSIFICATION AND TOPIC MODELING 
Francesco Paolo Luigi Caruso 906416, Samir Doghmi 897358, Davide Prati 845926


In the folder the following files are present:

-	Reviews.csv : "The original dataset 'Amazon Fine Food Reviews' downloaded from Kaggle. 

-	Report.pdf : The report describing the work done, i.e., the project, the implemented solutions, and the evaluations.

-	The following three Google Colab notebooks, which constitute the source code:
●	Preparing_data.ipynb : It contains sections for data cleaning and preprocessing, text preprocessing, data exploration, and balancing/sampling.
●	Classification.ipynb : It includes sections for text representation and dataset splitting for classification, multiclass classification, and binary classification (with the various implemented models)
●	Topic_modelling.ipynb : It includes sections for text representation for LDA and LSA, and the models used are: LDA, LSA, and BERTopic.

-	In a subfolder named “files_csv” you can find the datasets.: 
○	preprocessed.csv : Dataset resulting from the Preparing_data.ipynb
○	Having performed two different samplings, we obtained two datasets that were used in the subsequent sections.
■	binaria.csv : Used in the classification section
■	multiclasse.csv : Used in both classification and topic modeling.

All packages and libraries are loaded at the beginning of the code files. In case they are not already installed, they can be installed using the standard procedure.
