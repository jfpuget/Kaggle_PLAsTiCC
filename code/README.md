Notebooks should be executed in that order:

* `test_chunks.ipynb`  Splits test data into chunks and stores them.
* `base_features_006_filter_error_6_std.ipynb`  Base features used for lightgbm models.
* `bazin_003.ipynb` Fits Bazin curves for all extra galactic sources.
* `newling_003.ipynb` Fits Newling curves for all extra galactic sources.
* `lgb_best.ipynb` Computes a submisison file using the above features.  It is derived from the best model we had that scored 0.752 on the public leaderboard.  The difference with this one is that our best model used out of fold predictions from other models, mostly RNN and MLP mdoels produced by my team mates.  I removed that part to make the code self contained.

These notebooks aren't used for the competition solutions, but they contain pretty graphics:
* `eda_031_celerite.ipynb` Fits gaussian process, generates curves from it, and display them.
* `eda_024_bazin.ipynb`  Fits and displays Bazin curves.
* `eda_026_newling.ipynb` Fits and displays Newling curves.
