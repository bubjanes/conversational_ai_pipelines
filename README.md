# Text Mining
## NLU pipelines for dialogue systems

How to install [rasa](https://rasa.com/docs/rasa/user-guide/installation/).

You also will need to install the HuggingFace BERT dependencies for some models. 

```
pip install "rasa[transformers]"
```

Once that is done you can evaluate all of the configurations by running from the root directory of your project.

```
mkdir results
rasa test nlu --config configs/SklearnIntentClassifier.yml --cross-validation --runs 1 --folds 2 --out results/SklearnIntentClassifier
rasa test nlu --config configs/diet_BERT_only.yml --cross-validation --runs 1 --folds 2 --out results/diet_BERT_only
rasa test nlu --config configs/diet_BERT_combined.yml --cross-validation --runs 1 --folds 2 --out results/diet_BERT_combined
rasa test nlu --config configs/diet_without_BERT.yml --cross-validation --runs 1 --folds 2 --out results/diet_without_BERT
```

For an easy-to-read overview of the results execute this streamlit dashboard using the following code. 

```
pip install streamlit
streamlit run viewresults.py
```

Also, here is a great [YouTube tutorial](https://youtu.be/oj5oPGDlep4) by vincent d warmerdam, where I took the starter code for the streamlit.