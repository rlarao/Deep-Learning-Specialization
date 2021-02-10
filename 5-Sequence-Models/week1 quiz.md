## Week 1 Quiz - Recurrent Neural Networks


1. Suppose your training examples are sentences (sequences of words). Which of the following refers to the jth word in the ith training example?


2. Consider this RNN: This specific type of architecture is appropriate when:



3. To which of these tasks would you apply a many-to-one RNN architecture? (Check all that apply).
	


4. At the t-th time step, what is the RNN doing? Choose the best answer.
	


5. You have finished training a language model RNN and are using it to sample random sentences, as follows: What are you doing at each time step t?
	


6. You are training an RNN, and find that your weights and activations are all taking on the value of NaN (“Not a Number”). Which of these is the most likely cause of this problem?
	


7. Suppose you are training a LSTM. You have a 10000 word vocabulary, and are using an LSTM with 100-dimensional activations a<t>. What is the dimension of Γu at each time step?



8. Here’re the update equations for the GRU. Alice proposes to simplify the GRU by always removing the Γu. I.e., setting Γu = 1. Betty proposes to simplify the GRU by removing the Γr. I. e., setting Γr = 1 always. Which of these models is more likely to work without vanishing gradient problems even when trained on very long input sequences?



9. Here are the equations for the GRU and the LSTM: From these, we can see that the Update Gate and Forget Gate in the LSTM play a role similar to _______ and ______ in the GRU. What should go in the the blanks?



10. You have a pet dog whose mood is heavily dependent on the current and past few days’ weather. You’ve collected data for the past 365 days on the weather, which you represent as a sequence as x<1>,…,x<365>. You’ve also collected data on your dog’s mood, which you represent as y<1>,…,y<365>. You’d like to build a model to map from x→y. Should you use a Unidirectional RNN or Bidirectional RNN for this problem?

