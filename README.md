# Kaggle-Titanic-competition-79.6%
The h5 file of the trained network is called model_super79.6.h, which achieves the above stated accuracy for this competition. Please note that running the Jupyter Notebook and re-training the model might not lead to the same exact accuracy. The best accuracy I have been able to achieve with this model architecture is 79.6%. Furthermore the model sometimes gets stuck during training, restarting the training should fix the issue. The biggest part of this code is the data preprocessing and feature engineering, overall it was a really fun project to complete. I look forwards to doing more Machine Learning projects in the future.

This is my first competition in Kaggle, I have managed to achieve an accuracy of 79.6% which is in the top 7% of the competition. I have tried a variety of values for the train_test split random_state so every time the model is trained it will lead to a slightly different submission accuracy when re-training the model. I have included the Gridsearch function in the final code but I found that tweaking hyperparameters by hand worked better and furthermore hyperparameter search takes a long time.
![alt_text](https://github.com/peterfazekas1999/Kaggle-Titanic-competition79.43/blob/master/79.6%20kaggle%20submission.png)
and below is the model architecture built in Keras. I have built more complex architectures for this competition but they over-fit too much on the train/dev set so simplifying the model helps a lot. The uniform kernel initializer speeds up the learning a lot as well as using l2 regularization and dropout to further reduce over-fitting.
![alt_text](https://github.com/peterfazekas1999/Kaggle-Titanic-competition79.43/blob/master/model%20architecture.png)
