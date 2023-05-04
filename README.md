Download Link: https://assignmentchef.com/product/solved-cs534-assignment-2-cifar%e2%80%9110-image-classifica-on-using-fully-connected-neural-network
<br>
<h1></h1>

In this assignment, you are going to implement a one hidden layer fully connected neural network using Python from the given skeleton code <a href="https://oregonstate.instructure.com/courses/1706723/files/73690437/download?verifier=oYKLd66Wz8OvVe4tPlY3Ik8PRmv1JUFEBRGPa1bq&amp;wrap=1"><strong>mlp_skeleton.p</strong></a><a href="https://oregonstate.instructure.com/courses/1706723/files/73690437/download?verifier=oYKLd66Wz8OvVe4tPlY3Ik8PRmv1JUFEBRGPa1bq&amp;wrap=1"><strong>y</strong></a> <a href="https://oregonstate.instructure.com/courses/1706723/files/73690437/download?verifier=oYKLd66Wz8OvVe4tPlY3Ik8PRmv1JUFEBRGPa1bq&amp;wrap=1"> </a>on Canvas (find in the Files tab). This skeleton code forces you to write linear transformation, ReLU, sigmoid cross­entropy layers as separate classes. You can add to the skeleton code as long as you follow its class structure. Given N training examples in 2

categories                                                 , your code should implement backpropagation using the cross­

entropy loss (see Assignment 1 for the formula) on top of a sigmoid layer: (e.g.

), where you should train for an output

.                                   is the ReLU activation function (note Assignment #1

used a sigmoid activation but here it’s ReLU),        is a matrix with the number of rows equal to the number of hidden units, and the number of columns equal to the input dimensionality.

<strong>Finish the above project and write a report (in pdf) with following questions: </strong>

<strong>Please put the report(in pdf) and the source code into a same zip file, “firstname_lastname_hw2.zip”. Submit this zip file on Canvas. You have to make sure your code could run and produce reasonable results!</strong>

<ul>

 <li>Write a function that evaluates the trained network (5 points), as well as computes all the subgradients of and          using backpropagation (5 points).</li>

 <li>Write a function that performs stochastic mini­batch gradient descent training (5 points). You may use thedeterministic approach of permuting the sequence of the data. Use the momentum approach described in the course slides.</li>

 <li>Train the network on the attached 2­class dataset extracted from CIFAR­10: (data can be found in the<a href="https://oregonstate.instructure.com/courses/1706723/files/73330549/download?verifier=LSUl1aEpum22fqmUcSx3vOFMWqF5gFjL2vBOVW6t&amp;wrap=1"><strong>cifar­2class­p</strong></a><a href="https://oregonstate.instructure.com/courses/1706723/files/73330549/download?verifier=LSUl1aEpum22fqmUcSx3vOFMWqF5gFjL2vBOVW6t&amp;wrap=1"><strong>y</strong></a><a href="https://oregonstate.instructure.com/courses/1706723/files/73330549/download?verifier=LSUl1aEpum22fqmUcSx3vOFMWqF5gFjL2vBOVW6t&amp;wrap=1"><strong>zip</strong></a> file on Canvas.). The data has 10,000 training examples in 3072 dimensions and 2,000 testing examples. For this assignment, just treat each dimension as uncorrelated to each other. Train on all the training examples, tune your parameters (number of hidden units, learning rate, mini­batch size, momentum) until you reach a good performance on the testing set. What accuracy can you achieve? (20 points based on the report).</li>

 <li>Training Monitoring: For each epoch in training, your function should evaluate the training objective,testing objective, training misclassification error rate (error is 1 for each example if misclassifies, 0 if correct), testing misclassification error rate (5 points).</li>

</ul>

https://oregonstate.instructure.com/courses/1706723/assignments/7455714     1/2 2/15/2019         Image Classification using Fully Connected Neural Network

<ul>

 <li>Tuning Parameters: please create three figures with following requirements. Save them into jpg format: i) test accuracy with different number of batch size ii)test accuracy with different learning rate iii) test accuracy with different number of hidden units</li>

 <li>Discussion about the performance of your neural network.</li>

</ul>