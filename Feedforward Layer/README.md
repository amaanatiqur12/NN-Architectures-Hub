Video to refer to for a basic understanding of neural networks.

[But what is a neural network?](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=1)


[Gradient descent, how neural networks learn](https://www.youtube.com/watch?v=IHZwWFHWa-w&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=2)


[What is backpropagation really doing?](https://www.youtube.com/watch?v=Ilg3gGewQ5U&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=3)


[Backpropagation calculus](https://www.youtube.com/watch?v=tIeHLnjs5U8&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi&index=4)

[Book to refer for fundamental of neural network](http://neuralnetworksanddeeplearning.com/about.html)

- networks with two or more hidden layers are generally referred to as deep neural networks.

#### Basic Structure of Neural Networks

1)Perceptron:

Takes multiple binary inputs 𝑥1,𝑥2,… and gives a binary output (0 or 1).

Output is determined by: 

![image](https://github.com/user-attachments/assets/a277f2df-9786-40c3-9b8b-e1007d8fb33a)

Weights 𝑤𝑗 determine the importance of inputs, and bias replaces the threshold.

2)Sigmoid Neurons: Improve over perceptrons by producing outputs in the range [0,1] and enabling smoother learning through gradual changes.

![image](https://github.com/user-attachments/assets/530a67f9-bbc6-4dc2-b014-a1d37f2bd5e1)

When z=w⋅x+b is large and positive, the sigmoid neuron output approximates 1, and when z is very negative, it approximates 0, behaving like a perceptron except when z is of modest size, where it deviates.

---
In neural networks, the cost function C(w,b) is used to measure how well the network's predictions match the actual data. It essentially quantifies the error between the predicted outputs and the actual labels. The goal of training a neural network is to minimize this cost function by adjusting the network’s weights (w) and biases (b).

The specific cost function you provided is:

![image](https://github.com/user-attachments/assets/24c9e56e-d8b8-4a47-a9f9-13b585926302)

![image](https://github.com/user-attachments/assets/225f4853-a652-4acf-8324-7af32336f807)


![image](https://github.com/user-attachments/assets/47d483cf-35ec-413c-9a61-aaab69adce17)

![image](https://github.com/user-attachments/assets/613796d4-755c-4fa1-831b-4edd78f2394f)

![image](https://github.com/user-attachments/assets/47a89fd7-fb86-49e6-ba38-6556c3f90797)


