# backdoor-learning
Backdoor Learning about some well known or new backdoor attacks and defenses.

(experiments under Pytorch)

1.Train some benign and backdoored models based on datasets like MNIST, GTSRB, CIFAR10 and so on. Attacks include BadNet, Blend, Label Consistent and so on.

2.Analyse the activations of different layers(especially the last ones) to find different neuron activations or patterns between clean and poison inputs.

3.Since different feature patterns have been found, consider how to use it to filter poison samples or detect a backdoor model.
(how to represent features of input x: original outputs of network layers, converted outputs in other feature space...
how to filter poison samples online: similarity computation, outlier detection...)

(step 3 to be continued...)
