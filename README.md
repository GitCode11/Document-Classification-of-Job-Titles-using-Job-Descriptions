# Document-Classification-of-Job-Titles-using-Job-Descriptions

In this task, a data-set is used that comprise of different jobs posted on a job portal. The data-set was downloaded from Kaggle. It had the following basic properties:
1. It was provided in .csv format.
2. The data-set simulated the real life scenario of jobs posted on a job portal and comprised of Job's title, Job's description along with its category
As the data was labeled so in the context of machine learning, it was a Supervised Machine learning problem i.e. I had access to the data that was already correctly labeled and I had to train a model using this historical data. The main goal was to build a model that could accurately classify new and unseen data when it was input to it i.e. to assign proper label to a job posting when its input to the model.
As the nature of the data was "text" so this project also involved extensive usage of text mining techniques as well. Text in its basic form is unstructured and to develop predictive models, the data needs to be thoroughly pre-processed. So the pipeline of developing models that I followed was:
1. Data Profiling
2. Data Cleansing
3. Exploratory Analysis
4. Data Preprocessing
5. Feature Extraction and Selection
6. Model Development
7. Model Evaluation 

When text data is pre-processed, the issue of curse of dimensionality usually appears i.e. data becomes highly multi-dimensional with lots of features ranging in thousands. Not all of those features are helpful and also it adversely affects the peformance of classifiers as well so following the best practices, I opted for best-in-class feature extraction methods and also applied feature selection techniques so as to compile only those features that will contribute in this prediction problem. 
For model development, I used and compared the following set of machine learning algorithms:
1. Bernoulli Naive Bayes
2. Multinomial Naive Bayes
3. Random Forests
4. Linear SVM

and compared these algorithms on different metrics like accuracy, training and testing time. As per my analysis, SVM outshines all of the other models when it comes to accuracy. Random Forests accuracy score was also quite good but took considerable time during training phase.
For implementation, I used Python. Specifically, I used the following libraries/modules of Python for different set of tasks:
pandas,
numpy
sklearn
nltk
matplotlib

To run the code, please make sure that the latest version of Python, Jupyter and aforementioned libraries are installed in your system.
