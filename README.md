# Learning Deep-Leanrning with code-basics

I learned deep-learning and Mechine-learning with youtuber code-basics <br/>
He has a Tutorial courses about 49 videos and he explains the fundamental concepts about deep-learning and further applications.


Basically, in order to educate model to do something, it uses Neural-Network(NN).


Through this courses, I learned 3 important types of Neural-Network(NN), <br/>
which is Analog-Neural-Network(ANN), Convolutional-Neural-Network(CNN) and Recurrent Neural Network(RNN).

In using these 3 NN, I can analyze and make a prediction model of various kind of aspects.

Here is the main similarities and differiencies of these 3 NN.


<img width="1178" alt="3 NN" src="https://user-images.githubusercontent.com/72393144/230751672-ad911ce7-e65e-4edb-8590-b5f6ae00e252.png">

Now I am going to explain what I learned these 3 NN.

## 1. Analog-Neural-Network(ANN)
When I want to make a prediction of model, I have to make a regression model.


In order to do that, there are three types of descent model to make regression model.

Here is main difference between them.
<img width="1108" alt="Descent model" src="https://user-images.githubusercontent.com/72393144/230751832-d8f3383d-6405-450f-9fe1-0e31e0267f14.png">

When I trained a model using these 3 descent model, there are also 3 types of fittings exist.
<img width="511" alt="under   over fittings" src="https://user-images.githubusercontent.com/72393144/230751899-7248c8be-2fdf-47ae-adc3-73839cd318c5.png">

Using the preprocessed data, the descent model tries to predict the best fittings.

In the model building process, the learning model uses the concept of epochs, iteration, and batch size.

<img width="1577" alt="epochs, iteration, batch_size when Batch Gradient Descent" src="https://user-images.githubusercontent.com/72393144/230751975-40fd4969-6dc5-43e0-b99c-ce420b0c3022.png">

Overfitting is the worst case, and appropriate fitting is ideal.
## 2. Convolutional-Neural-Network(CNN)
CNN is very useful when I want to predict Image.<br/>
So it uses a lot when it comes to do Computer-Vision area.

When I want to make a prediction model fo what types of object in the picture,<br/>
there is a process to analyze each pixels of the picture.

To analyze the picture using CNN, it first use Convolution + ReLU to identify the key components of the picture. For example, Eyes, nose, ears.
Then the Pooling process proceeded. 

This set of process continueously happen to analyze the feature of the wanted object.

<img width="1800" alt="Feature extration to classification" src="https://user-images.githubusercontent.com/72393144/230752366-2c1f45c4-8e0f-417d-8c0d-f026389a9f2c.png">

And here is the main concept of Convolution, Pooling and ReLU.
<img width="1794" alt="Rules about convolution, Relu , Pooling" src="https://user-images.githubusercontent.com/72393144/230752447-8e9dc327-f9fc-4cc7-bc00-892a67202a62.png">


<img width="1327" alt="yolo4" src="https://user-images.githubusercontent.com/72393144/230752606-602ce166-314f-4fe9-a8a9-29c5b2a09fa4.png">

## 3. Recurrent Neural Network(RNN)
