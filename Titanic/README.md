# Titanic: Machine Learning from Disaster

*Applying Machine Learning models to the classification problem - predicting the survival of the passengers on Titanic*

### Submissions made to Kaggle

1. **1.py**
	* Using pclass, sex, age, Sibsp, parch, and fare features from the available dataset
	* Using 'most frequent' strategy to replace the missing data
	* Encoding the sex column using One Hot Encoders
	* Using Kernel SVM with default parameters
	* Accuracy is 64.59%
	
2. **2.py**
	* Using pclass, sex, age, Sibsp, parch, and fare features from the available dataset
	* Using 'most frequent' strategy to replace the missing data
	* Encoding the sex column without One Hot Encoders
	* Using Kernel SVM with default parameters
	* Accuracy is 63.64%	

3. **3.py**
	* Using pclass, sex, age, Sibsp, parch, and fare features from the available dataset
	* Using 'most frequent' strategy to replace the missing data
	* Encoding the sex column (not using HotEncoders)
	* Using Naive Bayes with default parameters
	* Accuracy is 75.12%
	
4. **4.py**
	* Using pclass, sex, age, Sibsp, parch, and fare features from the available dataset
	* Using 'most frequent' strategy to replace the missing data
	* Encoding the sex column (Using OneHotEncoders)
	* Using Naive Bayes with default parameters
	* Accuracy is 76.08%
	
5. **5.py**
	* Using pclass, sex, age, Sibsp, parch, and fare features from the available dataset
	* Using 'most frequent' strategy to replace the missing data
	* Encoding the sex column (Using OneHotEncoders)
	* Reducing the features using Backward Elimination Technique (adjusted R-squared intuition)
	* Using Naive Bayes with default parameters
	* Accuracy is 77.03%
	
6. **6.py**
	* Using the features as suggested by Backward Elimination Technique
	* Using the ANN Classifier
	* 5 hidden layers, 5 N's each layer.
	* Accuracy is 78.47%