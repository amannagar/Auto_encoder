# Auto_encoder
###Neural Network Auto encoder with multiple layers

####exec_task1()

Fully connected auto encoder network with 100 nodes in the hidden layer is implemented in which ‘Relu’ is used as the activation function of the hidden layer and output layer activation function is linear. Number of neurons in the output layer is same as the number of input that is 784 because that is why it is called as the autoencoder. MSE is used as the performance function to measure the loss. Training is done for 50 epochs only and a graph is plotted for two MSEs vs epoch number, as instructed the first MSE is calculated first data set and second MSE is calculated using second data set. MSE is calculated after each epoch.


 




####exec_task2()

Task 2 is similar to task 1, the only difference is that the we have to plot the graph for MSEs of two data sets vs the number neurons in their hidden layer which are changed from 20 to 40 to 60 to 80 to 100 and corresponding MSE mean over 50  epochs is calculated for data set 1 and 2 and at last the graph is plotted.
 
 




####exec_task3()
Same process is repeated as in task 1 the difference is that network is trained for 100 epochs this time and the learned weights as a grid of 10X10 images is displayed.

 


 



####exec_task4()
100 images of data set 3 are passed through the trained network of task 3 and we have to display the input images as well as reconstructed images in a grid of 10X10 


 

 

####exec_task5()
Again we used trained network of task 3 but this time we have passed the images of data set 2 and performing PCA on input images and also on output reconstructed images. Display only first 100 Eigen vectors for input and output images on a grid of 10X10.

 

 
