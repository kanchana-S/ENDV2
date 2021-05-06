# ENDV2
Assignments related to the course ENDV2 will be saved here


# What is a neural network neuron?
    Neuron is the smallest unit of computation in a nueral network. It has small storage capacity. 
    Each neuron has a weight and activation function. And also has a input or output connection.
     
# What is the use of the learning rate?
    Learning rate is required to control the decrease in weight to reduce the error. 
    Learning rates are important since they control how fast or slow the neural network trains itseelf. 
    These cannot be too big or too small values.
    
# How are weights initialized?
    Weights are initialized randomly. There are some reasons for this. 
    If it is initalized as 0 directly, the final result is no better than the one given by a linear model. 
    Too high and too small weights also do not perform any better, since the gradients are changing not 
    at the right pace and therefore the learning also takes a lot of time. 
    There are also newer methods of weight initialization like Xaviers method. 
    But this method also involves using random numbers from a normal distribution
    
# What is "loss" in a neural network?
    Loss is the error in prediction. It is the difference of preficted value and expected value.
    
    
# What is the "chain rule" in gradient flow?
    Chain rule is the same rule used to find partial derivetives, just that it is applied to the 
    output nodes w.r.t. input node. 
    This is needed to update weights in later iterations since we want the NN to learn and predict with less loss.
    
