# STORY OF RNN & LSTM 
# RNN (Recurrent Neural Network) & LSTM (Long Short-Term Memory)







If the sequence is long enough he’ll have a hard time carrying information from earlier time steps to later ones. So if you are trying to process a paragraph of text to do predictions, RNNs may leave out important information from the beginning.

For example, RNNs is fine when dealing with short term dependencies. That is when used to sequence like:

The longest river on earth is ________.

This sequence has nothing to do with the context of the statement. The RNNs need not remember what was said before this or whats its meaning, all they need to know is that amongst all rivers, Nile is the longest.
The longest river on earth is Nile.

For instance, if we have a sentence like:


The man who ate my pizza has purple hair.

In this case, the description of purple hair is for the man and not the pizza. So this is a long dependency.



![image](https://github.com/user-attachments/assets/fd69a4c1-e6ac-4f50-8cd3-455d69b13742)
