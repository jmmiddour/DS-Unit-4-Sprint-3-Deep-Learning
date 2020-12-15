# Deep Learning

---

## AutoEncoders and Recommendation Systems - Check for Understanding

---

### Question 1

What type of neural network is an autoencoder?

(--) recurrent

(X) feedforward
  
(--) perceptron
  
(--) LSTM

---

### Question 2

What is the process by which noise is reduced when using an autoencoder?

(--) The output from an autoencoder is filtered to reduce the noise.

(--) In order to use an autoencoder, the dimensions of the input data need to be reduced before feeding it to the input layer of the autoencoder.

(--) An autoencoder uses a recurrent layer to filter the data, reducing the noise. It works in a similar way to a recurrent neural network.

(X) An autoencoder learns a compressed representation of the input by implementing dimension reduction, which reduces noise.

---

### Question 3

What type of process does an autoencoder use to learn the encodings?

(--) logistic regression

(--) supervised learning

(--) clustering

(X) unsupervised learning

---

### Question 4

If the input dimension is 784, what is the output dimension from an autoencoder?

(--) 28

(--) 32

(X) 784

(--) 2

---

### Question 5

If an autoencoder is trained on images of digits, will it be able to encode others types of images, such as landscape or animals?

(X) No. It learns how to encode a specific type of image and isn't useful for images that are of a very different type.

(--) No but this is because autoencoders don't work well for modeling images.

(--) Yes but only if we train the autoencoder specifically on images of digits, as this specific type generalizes well to other images.

(--) Yes. As long as the autoencoder was trained on images, it will work well for all image types.

---

### Question 6

What is the process of information retrieval when using an autoencoder?
(--) Set-up the autoencoder architecture, select images that are similar to what you want to retrieve, train on those images, return the retrieved image 

(--) You can't retrieve anything from an autoencoder because it doesn't produce output that is much different from the input.

(X) Train an autoencoder, select an image to retrieve (query); use k nearest-neighbors to retrieve an image similar to the query 

(--) Train an encoder, return all the images that were encoded, find an image that best matches the one you want to retrieve