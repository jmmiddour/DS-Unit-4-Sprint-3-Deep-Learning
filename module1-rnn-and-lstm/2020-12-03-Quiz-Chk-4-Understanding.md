# Deep Learning

---

## Recurrent Neural Networks and LSTM - Check for Understanding

---

### Question 1

What is recursive about a recurrent neural network (RNN)?

(--) The process of feeding the final output of the RNN back into the input layer.

(--) The weights applied to the input are recycled at the hidden layers and fed back in to prevent the vanishing gradient problem.
  
(--) The recurrent part of the neural network is how often each neuron is "recycled" or used again in the next hidden layer.
  
(X) There is a recurrent loop where the output from a hidden later is "recycled" and added back in as input into that layer.

---

### Question 2

Why are RNNs and their subsets (LSTM networks) suitable for modeling time or sequence-dependent data?

(X) An RNN maintains internal memory of earlier input, which is especially important when modeling sequences.

(--) A RNN trains faster because of the recurrent hidden layer so long input sequences are easier to remember.

(--) The input layer in a RNN accepts sequences and can then pass long sequences into the recurrent layer.

(--) RNNs use a large number of nodes so they can model long sequences of input. 

---

### Question 3

What problem does an LSTM solve, when compared to a RNN?

(--) decreasing cross entropy 

(--) increasing bias

(--) vanishing dropout

(X) vanishing gradient

---

### Question 4

What are the sequences we can use when predicting text using an LSTM RNN?

(--) Vectorized sentences.

(--) Sequences of tokens.

(--) Sequences of individual characters.

(X) Sequences of individual characters and tokens (words).