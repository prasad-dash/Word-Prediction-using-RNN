# Word-Prediction-using-RNN

RNNs are unusually effective for time-series/sequential data.RNNs suffer from two major problems i.e. 
- Lack of long term memory
- Vanishing gradients | Exploding Gradients

LSTMs have been designed to solve these problems with a clever arrangements of gates and a memory pipeline. But still it suffers is sentences and predictions are longer than the recurrence length.

Transformers in recent times have shown that with self-attention even these problems can be tacke=led given you have large datasets and training power. 
In this notebook I compare the performance between LSTMs and Transofrmer based models. 
