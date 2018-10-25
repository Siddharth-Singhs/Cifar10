# Cifar10
To improve the accuracy of the Cifar10 dataset

Version1:
Using PCA Decomposition to retain 99% data so that total features decreased.
Feature->3072 to Feature-->627
Now training the X_train dataset using RandomForestClassifier by taking n_estimators=100.
We get the accuracy of 46.74%


Version2:
Using a Neural Network to train the model.
Using the 3 Dense Hidden Layer.
A 1st layer has 512 units, having the activation function to 'relu'.
A 2nd layer has 256 units, having the activation function to 'relu'.
A 3rd layer has 128 units, having the activation function to 'relu'.
An Output Layer has 10 units, having the activation function to 'softmax'

Now using the optimizer 'adagrad' and loss function to 'categorical_crossentropy'
Taking epochs to 100 and batch size 64
Now training the X_train dataset using the neural network 
We get the accuracy of 50.46% 