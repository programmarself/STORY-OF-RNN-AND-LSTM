# STORY OF RNN & LSTM 
<h2 style="font-family: 'poppins'; font-weight: bold; color: Green;">👨💻Author: Irfan Ullah Khan</h2>

[![GitHub](https://img.shields.io/badge/GitHub-Profile-blue?style=for-the-badge&logo=github)](https://github.com/programmarself) 
[![Kaggle](https://img.shields.io/badge/Kaggle-Profile-blue?style=for-the-badge&logo=kaggle)](https://www.kaggle.com/programmarself) 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/irfan-ullah-khan-4a2871208/)  

[![YouTube](https://img.shields.io/badge/YouTube-Profile-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/@irfanullahkhan7748) 
[![Email](https://img.shields.io/badge/Email-Contact%20Me-red?style=for-the-badge&logo=email)](mailto:programmarself@gmail.com)
[![Website](https://img.shields.io/badge/Website-Contact%20Me-red?style=for-the-badge&logo=website)](https://datasciencetoyou.odoo.com)
# RNN (Recurrent Neural Network) & LSTM (Long Short-Term Memory)
Imagine you have a magical weather-predicting friend named “Rehman”.
Rehman the Weather Predictor (RNN)
Rehman is pretty good at predicting the weather. He looks at today's weather, and based on what he sees, he can guess tomorrow's weather. For example, if it's sunny today, Rehman might say it will be sunny tomorrow too.
•	But there's a problem: Rehman sometimes forgets things. If it's sunny for a few days in a row, he might forget about the rainy days before that and predict sunny again.
The Smart Friend: LSTM
Now, imagine Rehman has a super smart friend named “ Luqman ”. Luqman helps Rehman remember things better. He's like Rehman's memory helper.
•	Luqman remembers everything: Luqman keeps track of not just today's weather, but also yesterdays, and the day before that.
•	Luqman helps Rehman predict better: Using Luqman's memory, Rehman can make better guesses about the weather. For example, if it was sunny for a few days, but it rained a lot last week, Luqman will remind Rehman about the rain, and Rehman can predict rain more accurately.
What are RNN and LSTM?
•	RNN is Rehman: It's a computer that tries to predict things based on what it sees right now.
•	LSTM is Luqman: It's a special kind of computer that helps RNN remember things better.
Together, Rehman and Luqman (RNN and LSTM) can make really good predictions!
Real-life examples:
•	Predicting the weather: Just like Rehman and Luqman, computers can predict the weather based on past weather data.
•	Understanding language: Computers can use RNN and LSTM to understand what you're saying. For example, when you talk to a smart speaker, it uses RNN and LSTM to figure out what you want.
•	Recognizing speech: When you talk to your phone, it uses RNN and LSTM to understand your words.

If the sequence is long enough he’ll have a hard time carrying information from earlier time steps to later ones. So if you are trying to process a paragraph of text to do predictions, RNNs may leave out important information from the beginning.

For example, RNNs is fine when dealing with short term dependencies. That is when used to sequence like:

The longest river on earth is ________.

This sequence has nothing to do with the context of the statement. The RNNs need not remember what was said before this or whats its meaning, all they need to know is that amongst all rivers, Nile is the longest.
The longest river on earth is Nile.

For instance, if we have a sentence like:


The man who ate my pizza has purple hair.

In this case, the description of purple hair is for the man and not the pizza. So this is a long dependency.



![image](https://github.com/user-attachments/assets/fd69a4c1-e6ac-4f50-8cd3-455d69b13742)
