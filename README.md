# Musical Control Data Prediction

A comparison of multiple models for predicting musical control data.

It is useful to predict future values of control data - either continuing user interaction, or predicting their movement. RNNs are a popular method for modelling this data. This study compares multiple designs for a DL models of musical control data to establish some baselines for comparison in terms of training effectiveness and results on publicly available training sets.

1. Base model - predict that each event is same as previous
2. Deterministic RNN
3. Gaussian RNN
4. Mixture Density RNN

Datasets:

1. MicroJam set (x, y, t)
2. EMPI (x, t)
3. ROLI Block (x, y, z, t)
