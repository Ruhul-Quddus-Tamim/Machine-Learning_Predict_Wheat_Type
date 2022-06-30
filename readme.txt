Computation Intelligence 

Inputs to the Problem is 3 types of wheat seeds data (as listed in UCI machine learning repository). The machine learning algorithm is used for classification is Supervised Learning. The algorithm is defined by its use of labeled datasets to train algorithms that to classify data or predict outcomes accurately. As input data is fed into the sequential model, it adjusts its weights until the model has been fitted appropriately, which occurs as part of the cross validation process.It learns task of learning a function that maps an input to an output based on example input-output pairs. The training and testing seeds data is splitted into 70% and 30%. The model is written in Python. 

To construct the data, seven geometric parameters of wheat kernels were measured:
1. Area A
2. Perimeter P 
3. Compactness C = 4*pi*A/P^2 
4. Length of kernel 
5. Width of kernel 
6. Asymmetry coefficient 
7. Length of kernel groove

All of these parameters are real-valued continuous.

In the dataset we have 7 attributes of 3 types of wheat samples. Objective of the analysis is to find a distinct relation between the physical attributes of wheat seeds and the type of wheat.

The proposed architecture is to apply the supervisied machine learning algorithms using neural network with one input layer where all the seeds data will be feed into the first hidden layer. There are 3 hidden layers where each layer containing 10 neurons and one output layer with 3 neurons to identify or predict the variety of wheat from its geometric properties. The 3 neurons will predict 3 different outputs. As there are more than one output, that is why the softmax classifier which can predict multiple outputs.  
The data was downloaded from the UCI machine learning repository and loaded into Google Colab for analysis.

