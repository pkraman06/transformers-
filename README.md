
# transformers

Transformers have transformed the field of natural language processing and are now being applied to a wide range of tasks, including image processing and time series prediction. Transformers were introduced by ==Vaswani Adal in the landmark paper, "Attention is All You Need"==. Unlike traditional sequence models such as RNNs, transformers leverage self attention mechanisms to process and put data in parallel, making them highly efficient and powerful. 

Transformers are now the backbone of state of the art models like BERT, GPT, and many others. The transformer model consists of two main parts, the encoder and the decoder. Both the encoder and the decoder are composed of layers that include self attention mechanisms and feed forward neural networks. Self-attention allows the model to weigh the importance of different words in a sentence when encoding a particular word. This is crucial for capturing dependencies that are far apart in the input sequence. 


<img width="1120" height="1520" alt="1_ZhndWDctDkxICALtMMJ8ew" src="https://github.com/user-attachments/assets/213c89bf-a6b4-435f-a783-b76b5c882be0" />



The feed forward neural network layers help in transforming the input data after the self attention mechanism. Each layer in the encoder and decoder stacks multiple such sub layers enabling the model to learn complex representations. 

Self-attention is the core component of the transformer architecture. It allows each word and the input to attend to every other word, making it possible to capture contexts and relationships more effectively. In self-attention, each word is represented by three vectors. Query, key and value. The attention score is computed as a dot product of the query and key vectors, which is then used to weigh the value vectors. This process allows the model to focus on different parts of the input sequence when making predictions.
