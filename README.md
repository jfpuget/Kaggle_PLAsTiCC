# Kaggle_PLAsTiCC
Part of our solution to PLAsTiCC Kaggle challenge

I was part of a team that finished 5th in this very challlenging Kaglle competition: https://www.kaggle.com/c/PLAsTiCC-2018 . It was challenging because we had to clasisfy unevenly spaces time series.  All time series problems I worked on before were regularly samples time series. Sure, some value could be missing, but nothing like what we have here.  Moreover, it was an  open classification problem, with more classes in the test data than in the train data.

I describe my part of the solution here: https://www.kaggle.com/c/PLAsTiCC-2018/discussion/75050 mostly feature engineering and lightgbm models.

A team mate, Kun Hao Yeh, describes his here: https://www.kaggle.com/c/PLAsTiCC-2018/discussion/75040  mostly RNN.

What is missing is a description of how we stacked models, due to our third team member, SomethingIsWrong.

The code in the code directory assumes that the competition data is in the input directory.  The data directory is used to store additional data.

The submissions directory contains files ready for submission.
