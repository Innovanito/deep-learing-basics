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
### Recurrent Neural Networks (RNNs) are a type of neural network that is specifically designed for processing sequential data. Unlike feedforward neural networks that take a fixed-sized input, RNNs can take an input sequence of any length and process it one element at a time.

#### 1. Natural Language Processing: RNNs are widely used in natural language processing tasks, such as language translation, text classification, and speech recognition. They can model the temporal dependencies in language sequences and generate more accurate and fluent output.

#### 2. Time Series Prediction: RNNs can predict future values in time series data, such as stock prices, weather patterns, or traffic flow. They can capture the underlying patterns and dependencies in the time series data and make accurate predictions.

#### 3. Music Generation: RNNs can generate new music by learning the patterns and structure of existing musical pieces. They can model the temporal dependencies in music and generate new pieces that follow the same structure and style.

## Models for design RNN 


LSTM and GRU are both types of recurrent neural networks (RNNs) that are designed to address the issue of vanishing gradients, which can occur when training deep neural networks. Both LSTM and GRU are capable of processing sequences of input data, but they differ in their architecture and the way they handle information over time.

### Long Short-Term Memory (LSTM):
LSTM is a type of RNN that was specifically designed to capture long-term dependencies in sequential data. The basic idea behind LSTM is to use a memory cell to store information over time, with various gates that control how the memory cell is updated and accessed.

LSTM has three gates:

- Forget Gate: Determines which information to forget from the memory cell.
- Input Gate: Determines which new information to add to the memory cell.
- Output Gate: Determines which information to output from the memory cell.


The forget gate and input gate allow LSTM to selectively update the memory cell with new information or forget outdated information, while the output gate allows LSTM to selectively output relevant information at each time step.

### Gated Recurrent Unit (GRU):
GRU is another type of RNN that is similar to LSTM in its ability to capture long-term dependencies. However, GRU has a simpler architecture than LSTM, with fewer gates and no separate memory cell.

GRU has two gates:

- Reset Gate: Determines how much of the past information to forget.
- Update Gate: Determines how much of the new information to add.


The reset gate and update gate allow GRU to selectively update the hidden state at each time step, similar to LSTM's memory cell. However, the simpler architecture of GRU makes it more computationally efficient and easier to train than LSTM.


In summary, LSTM and GRU are two types of RNNs that are designed to capture long-term dependencies in sequential data. While LSTM has a more complex architecture with separate memory cell and three gates, GRU has a simpler architecture with fewer gates and no separate memory cell. Both models have proven to be effective for various applications in natural language processing, speech recognition, and time series prediction.

### LSTM vs GRU 
<img width="1572" alt="LSTM vs GRU" src="https://user-images.githubusercontent.com/72393144/230799256-2d31f1ed-75b6-4b59-808f-5e1db290b854.png">

### The Diagram of LSTM and GRU

<img width="1772" alt="RNN vs LSTM" src="https://user-images.githubusercontent.com/72393144/230799513-eebcdd1d-5710-4384-b160-4a66a9687a51.png">


### Here is example of how to translate the languages

<img width="1353" alt="RNN- language translation" src="https://user-images.githubusercontent.com/72393144/230799326-70ebea8e-78e0-4249-9e15-8c2e89f59897.png">

### Here is example of how to make musical note

<img width="1346" alt="RNN to make melody" src="https://user-images.githubusercontent.com/72393144/230799344-03118085-bd5a-4fc3-a779-32ff1a046535.png">


### Word Embedding Techniques

<img width="1587" alt="Technique to compute word embedding" src="https://user-images.githubusercontent.com/72393144/230799396-6f113a8d-b5e4-41dc-8f5c-79dfa011bd5a.png">


