# Convolutional Neural Network

## overview
 * CNN is the one of the most powerful NN in the Area of Image Recognition 
 
#### how CNN works  : 
 Basicly CNN have three Major phase of procceccing  wich are : 
  * Convolution  : you can imagine it as you are passing a  torch through an image
  to see all the pixels
  * Pooling  : the purpose of  this step is basicly To reduce the size of our image
  because if we don't do that it is impossible to proccess it later (require a lot of computation power)  
  the most use pooling called the max pooling its like you have a matrix of 2*2 you will take the highest number in it
  So simple heh  ?
  
  * fully Connected Layer  : this is the main layer that is responsible for the learning(training) 
  it use of course the backPropagation Algorithm to achieve this purpose    
 
  ###### These three steps you can notice it in the conv_net() method wich stand for buiding the model
 
 ## Dependencies 
  * Tensorflow   ML framwork
  * MNIST        Data set
  
 
 ## Run 
   *  python3 demo(tensorflow).py 