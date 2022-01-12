My project notebook is called project.ipynb. It follows a combination of Lab 2 and Lab 3 flow. It starts on the standard imports and mglearn project flow diagram. 

The CSV was imported and split into X and y after being cleaned. The data is visualized in piecharts, boxplots, and a heatmap.
The data is cross-validated using LogisticRegression(), SVC(random_state=54), BernoulliNB(), RandomForestClassifier(random_state=55), and GradientBoostingClassifier(random_state=56).

The hyperparameters are then tuned for the top 3 performing models. The best model is then chosen and retrained on the test data. 

Conclusion and Reflection follow at the end.

Code should run in order. No additional packages required.

Results, interpretation, and reflection are at the end of the notebook.
