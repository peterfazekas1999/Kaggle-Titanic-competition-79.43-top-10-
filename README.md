# Kaggle-Titanic-competition-79.43%
The h5 file of the trained network is called model_super_79.4.h, which achieves the above stated accuracy for this competition. Please note that running the Jupyter Notebook and re-training the model might not lead to the same exact accuracy, because I have used early stopping, it will almost always be slightly different. The best accuracy I have been able to achieve with this model architecture is 79.43%.

This is my first competition in Kaggle, I have managed to achieve an accuracy of 79.43% which is in the top 10% of the competition. I have used early stopping for the model and tried a variety of values for the train_test split random_state so every time the model is trained it will lead to a slightly different submission accuracy. I have included the Gridsearch function in the final code but I found that tweaking hyperparameters by hand worked better and furthermore hyperparameter search takes a long time.
![alt_text](https://github.com/peterfazekas1999/Kaggle-Titanic-competition-79.43-top-10-/blob/master/prediction79.43.png)
and below is the model architecture built in Keras.
![alt_text](https://github.com/peterfazekas1999/Kaggle-Titanic-competition-79.43-top-10-/blob/master/model%20structure.png)
