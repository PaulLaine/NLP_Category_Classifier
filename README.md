# NLP_Category_Classifier

The goal of this project is to be able to classify a project into its main category given its name and basic information such as launch date, deadline and goal amount.

Based on the information in the dataset, here are the different features that we can find in our dataset :
- name  : the name of the project
- goal : the amount of money claimed for the project
-	sub_category : the sub_category of the project. 
-	launched : date launched
-	deadline : deadline for crowdfunding
-	main_category : the main category of the project (this is the target).

This project is divided into two parts notebook where we use two differents method to solve this problem, classic Machine Learning and BERT method.

The proccess of the **Machine Learning** notebook is the following one :
- Cleaning : handling missing values, removing inconsistent features and deals with imbalanced target
- NLP Pre-processing : NLP cleaning, tokenize, remove stop words and stemming (or lemmatization).
- Training and Validation : Target Labelization, data evaluation, data splitting and training.

The proccess of the **BERT** notebook is the following one :
- Cleaning : same as Machine Learning method.
- NLP Pre-processing and training : The processing and training methods is unique to the BERT algorithm, you can check this [link](https://blog.tensorflow.org/2020/12/making-bert-easier-with-preprocessing-models-from-tensorflow-hub.html) to better understand how BERT works.

RESULTS : 

- Machine Learning : 52,6% accuracy
- BERT : 55,8% accuracy

After working on this project we realize that the problem is due to the dataset and the works needs to be on this part. Will probably come in further times !
