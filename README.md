# SGD_TensorFlow_California-Housing
Solving a regression problem using Neural Network by updating weights using RELU activation function iterating over 100-EPOCHS to reduce loss/cost value 

* Epoch 38/100
* 363/363 [==============================] - 1s 2ms/step - loss: 0.2774 - val_loss: 0.3012


### ReLU (Rectified Linear Unit) Activation Function

* The ReLU is the most used activation function in the world right now.Since, it is used in almost all the convolutional neural networks or deep learning.
https://miro.medium.com/max/875/1*XxxiA0jJvPrHEJHD4z893g.png
* As you can see, the ReLU is half rectified (from bottom). f(z) is zero when z is less than zero and f(z) is equal to z when z is above or equal to zero.
**Range: [ 0 to infinity)
* The function and its derivative both are monotonic.

**But the issue is that all the negative values become zero immediately which decreases the ability of the model to fit or train from the data properly. That means any negative input given to the ReLU activation function turns the value into zero immediately in the graph, which in turns affects the resulting graph by not mapping the negative values appropriately.**
