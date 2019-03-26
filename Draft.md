# Machine-Learning-101

Machine Learning has become the baseline for majority of the intelligent systems today. Whether the application is in the domain of Artificial Intelligence or Data Science, it is considered the building block for embryonic systems in these fields. Despite its prevalence in present-day systems, the basics of Machine Learning are often confused with those of AI or Data Science. This blog is an effort to clarify what Machine Learning is about, and what it entails.

Machine Learning is generally defined as enabling computers to learn on the basis of data being fed, without being explicitly programmed. The fact that there are almost 3.9 billion internet users all over the world indicates the data being generated is humungous. To deal with massive data, Machine Learning models are highly convenient given they have optimum resources. In today’s landscape, certain factors such as huge volume of data, various varieties of data like images and audios along with cheaper and greater availibility of computational resources has led to Machine Learning become a favorite for Data Analysis and Modeling.

## Machine Learning Terminolgies

When you start working on Machine Learning, one may come across various terms that would lead to confusion. This section will focus on elaborating those terms so as to give the readers an idea behind those terms.

1. Dataset
The dataset is defined as the collection of data. It can be comma separated values (csv), database or a matrix etc. Each dataset is divided into three subsets:

   a. Training set:
This subset is used for training the machine learning model. The parameters of the model are gauged using the training data.

   b. Test set:
This subset is used for assessing the machine learning model. It is independent of the training data but follows the same distribution as the training data.

   c. Cross Validation set:
This portion of dataset is used to compare the performances of the machine learning models that were created based on the training set. This enables us to tune the parameters of the model for better performance. The algorithm with the best performance is then chosen.

The most common approach towards separating the dataset into the above-mentioned subsets is dividing the dataset randomly into 80/20 ratio. The 80% training data is then again split into 80/20 ratio, with 20% allocated to cross validation set.

