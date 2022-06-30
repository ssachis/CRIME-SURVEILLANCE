# carma

### Problem we are trying to solve

In video surveillance, to critically assure public safety, hundreds and thousands of surveillance cameras are deployed within cities, but it is almost impossible to manually monitor all cameras to keep an eye on violent activities. Rather, there is a significant requirement for developing automated video surveillance systems to automatically track and monitor such activities.

### Models used
1. LRCN (CNN + LSTM) [Long-term Recurrent Convolutional Network]
2. ConvLSTM [Convolutional Long short term memory]

<br>
ConvLSTM is a variant of LSTM (Long Short-Term Memory) containing a convolution operation inside the LSTM cell. Both the models are a special kind of RNN, capable of learning long-term dependencies.

ConvLSTM replaces matrix multiplication with convolution operation at each gate in the LSTM cell. By doing so, it captures underlying spatial features by convolution operations in multiple-dimensional data.

The main difference between ConvLSTM and LSTM is the number of input dimensions. As LSTM input data is one-dimensional, it is not suitable for spatial sequence data such as video, satellite, radar image data set. ConvLSTM is designed for 3-D data as its input.

A CNN-LSTM is an integration of a CNN (Convolutional layers) with an LSTM. First, the CNN part of the model process the data and one-dimensional result feed an LSTM model. 


<br>
Demo Video of Carma 

---

References

Ş. Aktı, G.A. Tataroğlu, H.K. Ekenel, “Vision-based Fight Detection from Surveillance Cameras”, IEEE/EURASIP 9th International Conference on Image Processing Theory, Tools and Applications, Istanbul, Turkey, November 2019.
