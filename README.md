# mnist-tf-variables

A notebook that illustrates how to use TensorFlow Variables. 

TensorFlow Variables are often useful for building custom models that are 
not easy to implement using available TensorFlow layer APIs. MNIST is a 
popular, and clean, standard dataset for testing models. Hence, the 
notebook uses MNIST to train a network for classifying digits. It is clearly
not as accurate as using avaiable TensorFlow layers, but it is a good 
example that illustrates how to construct custom models that can perform
things like bypassing layers, combining different layer outputs, etc.
