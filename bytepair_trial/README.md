## readme 

Models were evaluated using the following code; 

```
rasa test nlu --config configs/diet_simple.yml \              
          --cross-validation --runs 1 --folds 2 \
          --out results/diet_simple
rasa test nlu --config configs/diet_bytepair.yml \
          --cross-validation --runs 1 --folds 2 \
          --out results/bytepair
```

To see a dashboard of your results just execute the following code.

```
pip install streamlit
streamlit run viewresults.py
```
