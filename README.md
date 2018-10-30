# Cifar10
To improve the accuracy of the Cifar10 dataset

-  **Version1:** <br>
Using PCA Decomposition to retain 99% data so that total features decreased. <br>
Feature->3072 to Feature-->627 <br>
Now training the X_train dataset using RandomForestClassifier by taking n_estimators=100. <br>
We get the accuracy of 46.74% <br>


-  **Version2:** <br>
Using a Neural Network to train the model. <br>
Using the 3 Dense Hidden Layer. <br>
A 1st layer has 512 units, having the activation function to 'relu'. <br>
A 2nd layer has 256 units, having the activation function to 'relu'. <br>
A 3rd layer has 128 units, having the activation function to 'relu'. <br>
An Output Layer has 10 units, having the activation function to 'softmax' <br>
Now using the optimizer 'adagrad' and loss function to 'categorical_crossentropy' <br>
Taking epochs to 100 and batch size 64 <br>
Now training the X_train dataset using the neural network <br>
We get the accuracy of 50.46% <br>

-  **Version 3:** <br>
Uses VGG16 based model's pre-trained weights to train on the cifar-10 dataset. <br>
No fine tuning has been performed.
