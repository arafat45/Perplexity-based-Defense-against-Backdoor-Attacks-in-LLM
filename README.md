# Perplexity-based-Defense-against-Backdoor-Attacks-in-LLM

*To install the libraries on which the codes are heavily dependable

 pip install -r requirements.txt

*Run 'datasets_prep.ipynb' for downloading the emotion dataset and saving the clean and poisoned training and testing set in 'data' folder.

*Run 'perplexity_filtering.ipynb' to filter out the trigger words from poisoned test set and save them in 'data' folder.

*Run 'bert_training_testing.ipynb' to train bert and produce all the results.

*Codes in 'perplexity_filtering.ipynb' are mostly taken from https://github.com/thunlp/ONION 

