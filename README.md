# NLP_final_project

Dataset file from: J. Wang, K. Fu, C.T. Lu, “SOSNet: A Graph Convolutional Network Approach to Fine-Grained Cyberbullying Detection,” Proceedings of the 2020 IEEE International Conference on Big Data (IEEE BigData 2020), December 10-13, 2020.

<img src = 'https://youthlegalserviceinc.com.au/wp-content/uploads/2021/11/1500x750-logos.gif'></img>

### PLAN:
__Preparing the datasets:__

We split the dataset into input features (X) and target variable (y) which stand for tweet texts and oh_label/type of cyberbullying. So, basically X will consist of the text column, and y will be the binary label indicating whether a tweet is potentially harmful or not in the first model and multiple labels for further classification. Also was performed necessary preprocessing steps on the text data, such as removing stopwords, changing emoticons, getting rid of unicodes, extra links, text went through tokenization, and normalization.

__Splitting the data into training and testing sets:__

Then we split the preprocessed data into training and testing subsets to evaluate the model's performance.

__Vectorizing the text data:__

We converted the preprocessed text data into a numerical representation that machine learning algorithms can work with. Firstly we used techniques like word embeddings, then TF-IDF to vectorize the text.

__Training a classification model:__

Chose a suitable machine learning algorithm for binary and multiple classification, such as logistic regression, random forest, k neighbours, decision tree, naive bayes, neural networks and so on. Fitted the model on the training data, using the vectorized text data (X) and the target labels (y).

__Evaluate the model:__

Predicted the labels for the test set using the trained model. Evaluated the model's performance using metrics like accuracy, precision, recall, and F1-score by scikit-learn library computation tools.
