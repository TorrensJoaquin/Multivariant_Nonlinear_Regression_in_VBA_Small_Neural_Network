# Multivariant-Nonlinear-Regression-in-VBA-Small-Neural-Network
#### Despite the big boom in Neural Networks, the common workers are still outside of its capabilities.
#### The idea of this proyect is to provide an easy tool for small neural networks (something around 6 layers and 200 neurons maybe).
#### It has to run without any other software than Microsoft Excel.
#### This work was inspired by Emanuele Bonura's Blog called "A Neural Network in 11 lines…of VBA!" and Carlos Ruiz, my former teacher from UTN FRRo.
#### You will need a sheet called "Data" were you can put the data. (x's [inputs] on the left, y's [outputs] on the right, and the first row will be the header), another called "Test" with the same format.
#### In addition, an Empty sheet called "Result" where the code of the formula will be generated.
#### A Learning Ratio Range Test is also included.
# Tuning of the following parameters in the modules is required:
#### n_hid_layer = 'Number of hidden layers
#### x_features = 'Number of x features
#### y_features = 'Number of y features
#### n_neurons_hid_layer(x) = 'Number of neurons in the hidden layer x (change the x for as many layers you have set)
#### SizeOfDataBase = 'The size of the database
#### UploadOldModel = 'Train more an existing model.
#### ChangeArquitecture = 'It's common, and recommended, start with a shallow neural network and start increasing/decreasing neurons/layers. If it's true, will recycle old weights and initialize new ones.
#### SamplesInBatch = 'Number of Samples on each Batch. Maximum of 1024
#### NumberOfIterations= Number of iterations
#### LearningRatio = 'You can perform a range test every time you want. This value will depend on the dataset and NN architecture.
# Comming Soon:
#### Code Optimization.
#### More activation functions to be chosen.
#### More loss functions to be chosen.
#### GUI.
## During this work Softplus, Sigmoid, Tanh, Relu and LeakyRelu activation functions were implemented. LeakyRelu is in the stable versión. (Yes, we all look at ReLu at first and say, No Way!, but today is the right choice)
#### Please. Have the inmediate window visible. Data will be shown
## Diagnosis tool:
#### If the sheet named "Result2" is added. A function of the raw output of each layer will be displayed.
#### This will be usefull for dimensionality reduction (autoencoders), and network health diagnosis.
