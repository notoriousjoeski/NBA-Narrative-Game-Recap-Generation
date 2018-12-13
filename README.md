#NBA-Narrative-Game-Recap-Generation

In this project we propose a model that generates NBA sports recaps after games.  
My implementation uses a character level sequence-to sequence model. Processing the input character by character and 
generating the output character by character.
My model is consistent of a multilayered Long Short Term Memory (LSTM). 
These LSTMs map the input sequence to a vector of a fixed depth, 
and afterwards, an additional LSTM decodes the target sequence from the vector. 





























