# QNN-for-MNIST-Dataset-Classification

A Parameterization approach of QNN is implemented for MNIST Dataset classification with accuracy of 80 percent using 1860 parameters i.e. 186 params per digit and 8 qubits for MNIST image dataset of digit pixel size of  16x16 grey scale . THe accuracy can be increased by increasing the depth of the Quantum Circuit i.e. the number of params , tweaking with the loss function (here cosine similarity is used) , adding a nonlinear classical activation function for increasing the accuracy, also better ways of clustering can be explored. 
This forms a general design of Quantum circuit designed by me that can be paramerized as per the application dataset.
Also due to larger computational time on my laptop only test dataset of 10 samples is tested,, so that can be increased to get the statistical mean accuracy for this QNN model. 
Note - Here we are in QiML domain and hence Quantum Measurement is not used and statevector simulator is used to avoid the statiscal ensemble creation to recreate the whole state vector and avoid the computational time as it increases the query calls to circuit. So a question can be raised on how can quantum measurement be used as nonlinear activation function on actual quantum computer, also can Quantum measurement itself act as a classifier in basis state ? More hybrid architectures can also be looked at like intermitent partial quantum measurement.


