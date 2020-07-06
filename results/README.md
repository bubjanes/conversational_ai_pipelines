## readme 

This readme contains the code for the DIET benchmarking. The training data was not because it is owned by the company Kunan S.A. and is not public 🔥🔥🔥🔥

If you want to train using your own Spanish language training data first, if you don't already have it, install [rasa](https://rasa.com/docs/rasa/user-guide/installation/).

You will need to ensure that you've installed the BERT dependencies if you want to run the heavy models. 

```
pip install "rasa[transformers]"
```

After downloading this repo, move the directory **configs** and the file **viewresults.py** to the root directory of your rasa project.

Models were evaluated using the following code; 

```
rasa test nlu --config configs/diet_BERT_combined.yml --cross-validation --runs 1 --folds 2 --out results/diet_BERT_combined
rasa test nlu --config configs/diet_without_BERT.yml --cross-validation --runs 1 --folds 2 --out results/diet_without_BERT
rasa test nlu --config configs/diet_BERT_only.yml --cross-validation --runs 1 --folds 2 --out results/diet_BERT_only
rasa test nlu --config configs/SklearnIntentClassifier.yml --cross-validation --runs 1 --folds 2 --out results/SklearnIntentClassifier

# TODAY
rasa test nlu --config configs/diet_bytepair.yml --cross-validation --runs 1 --folds 2 --out results/diet_bytepair

rasa test nlu --config configs/diet_BERT_combined.yml --cross-validation --runs 1 --folds 2 --out results/diet_BERT_combined
rasa test nlu --config configs/diet_BERT_es_combined.yml --cross-validation --runs 1 --folds 2 --out results/diet_BERT_es_combined

rasa test nlu --config configs/diet_BERT_es_bytepair.yml --cross-validation --runs 1 --folds 2 --out results/diet_BERT_es_bytepair



```

To see a dashboard of your results just execute the following code.

```
pip install streamlit
streamlit run viewresults.py
```
