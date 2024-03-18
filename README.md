# Artificial-Neural-Network-Grocery-Robot

This project is a university assignment for the course of Computational Intelligence.
We created a fully functioning artificial neural network that can classify an input of 10 features into one of 7 classes.  
The data we used to train and test our network can be found in the <ins>***data***</ins> folder. There are three
files in a comma-separated value format:  
• **features.txt**: 7854 samples of 10 features  
• **targets.txt**: 7854 target classes of the samples mentioned above  
• **unknown.txt**: 784 samples of 10 features, with no labels available  
We load the data, prepare it and use it to train the neural network, which in turn is used to recognize the classes of the unknown samples. The network is a feed-forward one and it's able to learn using the back-propagation algorithm.  
The final network we implemented managed to get an accuracy of about 94% on the **unknown.txt** data file.