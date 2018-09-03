# BBB

Tensorflow implementation of Bayes by Backprop form the following paper "Weight Uncertainty in Neural Networks" at https://arxiv.org/pdf/1505.05424.pdf.

The implementation is inspired from:-
1. https://gluon.mxnet.io/chapter18_variational-methods-and-uncertainty/bayes-by-backprop.html, and
2. https://github.com/christegho/bnn-mnist.git
(@christegho : I request you to please have a look and point out any mistakes.
I felt your implementation used log_likelihood of a gaussian pdf instead of a categorical pdf for labels, which seems inappropriate.)

Implementation does not use OOP principles as the objective here is to have a basic understandable and functional code for the algorithm.
The MNIST dataset is used as in the paper. Although implementation 1. (above) suggests that n_samples parameter=1 works, 
it didn't work for me. I had to use n_samples=5 for decent results.
Please let me know if you have any feedback for the implementation at my email: agarwal.270@osu.edu.
Thanks!
