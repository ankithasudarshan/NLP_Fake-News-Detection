# NLP_Fake-News-Detection

This project is an implementation of fake news detection. It focuses on three different approaches to the problem - The BERT appraoch, CNN approach and an Ensemble technique. The BERT model has been fine tuned on this downstream task with the addition of three layers on top of the pre-trained model.
The CNN model is a custom model which consists of 3 convolutional layers and 2 dense layers, meant for this task. Finally, the ensemble technique involves the combination of 3 traditional ML classification models namely - Passive Aggressive Classifier, Multinomial Naive Bayes Model and Random Forest Classifier. A comparison has been drawn amongst the models and they have been evaluated on a dataset of fake and real news.
