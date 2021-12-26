# Multilingual-Abusive-Comment-Detection
This code was a part of submission to IndoML datathon https://indoml.in/
* The training dataset contains a csv file with abusive and non-abusive comments from various apps like Moj and Sharechat
* Link to trainning dataset is https://www.kaggle.com/c/multilingualabusivecomment/data . Test dataset needed to be cleansed and then model could test it. Required cleansed test dataset is uploaded. You may find original test dataset at the above link itself. [To know about cleansing procedure of respective test data, refer here](#https://www.kaggle.com/thanatoz/input-and-output-processing)
* Approach of the solution was using indic-nlp library for tokenization. We applied Tf-IDF vectorization and Binary Logistic Regression to finally predict our test dataset.
