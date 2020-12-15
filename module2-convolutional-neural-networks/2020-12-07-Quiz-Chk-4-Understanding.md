# Deep Learning

---

## Convolutional Neural Networks - Check for Understanding

---

### Question 1

Which of the following choices is the best description of convolution at it relates to an image?

(--) Convolution is a different way to describe the process of edge detection in an image.

(--) The process of compressing an image so it is easier to use as input to a convolutional neural network (CNN).
  
(--) The process of convolution is taking the output from a hidden layer and feeding it back in as input.
  
(X) Convolution is the process of sliding a filter across an image to produce a new image that is the convolution of the original and the filter.

---

### Question 2

What is the purpose of the convolutional layer in a CNN?

(X) It performs the filtering or convolution process.

(--) It reduces the dimensions of the convolved images to reduce the training time.

(--) It accepts the filtered or convolved initial input and passes it to an additional filtering layer. 

(--) It uses filters to prevent the vanishing or exploding gradient problem associated with CNNs.

---

### Question 3

How does the pooling layer work in a CNN?

(--) It combines pixels in the input image into one pixel, with either the average or maximum value. 

(--) It combines or pools the results from numerous filters in the convolutional layers into the final model parameters.

(X) It combines the output from a cluster of neurons in one layer into a single neuron in the next layer. 

(--) It combines separate convolutional filters into one "pooled" filter to speed up processing.

---

### Question 4

Consider the following convolutional layer (added with the Keras sequential API):

```
model.add(Conv2D(32, (3, 3), activation='relu', 
                 kernel_initializer='he_uniform',
                 input_shape=(28, 28, 1)))
```

What is the shape of the *kernel filter* and how many filters are in this layer?

(--) kernel = 9, filters = 28x28x1

(--) kernel = 28x28, filters = 32 

(X) kernel = 3x3, filters = 32

(--) kernel = 32, filters = 9 (or 3x3) 

---

### Question 5

What type of process are we taking advantage of when we use a pre-trained neural network to classify images?

(--) activation

(--) categorical cross-entropy

(--) convolution

(X) transfer learning