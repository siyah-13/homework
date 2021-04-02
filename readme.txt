Problem Description : - 

This assignment requires the putting together of a simple image classification pipeline to classify the digits 0 and 1 based on the logistic regression or the SMV Classifier. Futhermore, the goals are as follows: 

• understand image classification pipelines/data-driven approach (train/predict stages)

• understand how to use pytorch to build binary classifiers.

• understand how to exploit pytorch’s autograd mechanics to do optimization.

• implement and apply a logistic regression classifier.

• implement and apply a binary Support Vector Machine (SVM) classifier.


Data : - 

In these tests, we incorporate MNIST digit classification datasets. Pytorch is used to load the data into batches. 

Classifiers techniques used :-

1) SVN :- We have used SVN supervised learning model to classify the images. SVN works best with this classification because it basically a linear classification.
2) Logistic Regression :- We used this model to classify the images. Since the data was categorical, i.e. , classify between 0 and 1, hence this model outputs pretty accurate 
results. 

How to Run : -

The respective logistics regressions and support vector machine is implemented using PyTorch

1. Skeleton Python code has been provided for updating 
2. Edit respective code in a text editor (Sublime Text was used to edit python code)
3. Using Google Colab, all associated libraries and packages were imported
4. Run the code listed in the edited python file sequentially 
5. Change the learning_rate and momentum hyper parameters in the respective Google Colab code line 


Results/Conclusions :- 
1) The model has been trained and tested using different epochs too.
2) We were able to complete the classification and achieve an accuracy of ~ + 99%.
3) Based on the result, we conclude this as a good classification
4) For both Logistic Regression and SVM, the addition of momentum produced more accurate results. 