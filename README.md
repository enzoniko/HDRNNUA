# Handwritten Digit Recognition Neural Network Using APL

### This are my efforts to learn a little bit of this incredible language while applying the things I learned in the "Hello World!" of Artificial Inteligence and Machine Learning.

### But what is APL?
#### APL is an array oriented programming language developed in the 1960s by Kenneth E. Iverson. Its central datatype is the multidimensional array. It uses a large range of special graphic symbols to represent most functions and operators, leading to very concise code. It has been an important influence on the development of concept modeling, spreadsheets, functional programming, and computer math packages. It has also inspired several other programming languages.

### Objectives
#### Cure my curiosity on this language, get a better understanding of the array oriented paradigm and remember the key concepts of Machine Learning.

### What is this project?
#### This is the classic Handwritten Digit Recognition Neural Network, given a big training sample of Handwritten digits this configurable neural network can learn how to classify a given testing sample with an accuracy of up to 90% (This was the most I got using a training MNIST sample of about 60k lines, it is possible to be more accurate!).

### How to run
#### - Download / Clone this Repository;
#### - Unzip the training and testing MNIST samples in this repo or create your own 28x28 handritten digits samples (Copy the MNIST format: CSV file, One digit per row, first number of every row is the target digit (0 to 9), every other 768 (28x28) elements are the pixels (0 to 255));
#### - You need to have apl downloaded and installed in your machine;
#### - Copy the path to the downloaded repo folder;
#### - Link the apl session with the folder by doing `]create path-to-link`;
#### - Replace every occurance of this path in the MNIST apl file;
#### - That's it, to train and test the Neural Network write `MNIST ⍬`;
#### - After a couple of seconds spent training the NN, it should test it and return the accuracy! Feel free to tweak the hidden layers in the MNIST function or change the Activation and/or Loss functions (Using LeakyReLU and MSELoss respectively).

### Enjoy!
