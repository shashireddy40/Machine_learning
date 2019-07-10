# Machine_learning
Machine learning with python


Training data and Test Data


Training data, also called AI training data, training set, training dataset, or learning set — is the information used to train an algorithm. The training data includes both input data and the corresponding expected output. Based on this “ground truth” data, the algorithm can learn how to apply technologies such as neural networks, to learn and produce complex results, so that it can make accurate decisions when later presented with new data. Training data can be used for various machine learning algorithms, such as sentiment analysis, natural language processing, and chatbot training.

Testing data, on the other hand, includes only input data, not the corresponding expected output. The testing data is used to assess how well your algorithm was trained, and to estimate model properties.


Validation Set: 

This is crucial to choose the right parameters for your estimator. We can divide the training set into train set and validation set. Based on the validation test results, the model can be trained(for instance, changing parameters, classifiers). This will help us get the most optimized model.


Feature and label


riefly, feature is input; label is output. This applies to both classification and regression problems.

A feature is one column of the data in your input set. For instance, if you're trying to predict the type of pet someone will choose, your input features might include age, home region, family income, etc. The label is the final choice, such as dog, fish, iguana, rock, etc.

Once you've trained your model, you will give it sets of new input containing those features; it will return the predicted "label" (pet type) for that person.




Feature:

In Machine Learning feature means a property of your training data. Or you can say a column name in your training dataset.

Suppose this is your training dataset

Height   Sex   Age
 61.5     M     20
 55.5     F     30
 64.5     M     41
 55.5     F     51
 .     .     .
 .     .     .
 .     .     .
 .     .     .

Then here Height , Sex and Age are the features.

label :

The output you get from your model after training it, is called label.

Suppose you fed above dataset to some algorithm and generates a model to predict gender as Male or Female, In the above model you pass features like age, height etc.

So after computing it will return the gender as Male or Female. Thats called a Label
