# QNN-for-MNIST-Dataset-Classification

A Parameterization approach of QNN is implemented for MNIST Dataset classification with accuracy of 80 percent using 1860 parameters i.e. 186 params per digit and 8 qubits . THe accuacy can be increased by increasing the depth of the Quantum Circuit i.e. the number of params , tweaking with the loss function (here cosine similarity is used) , adding a nonlinear classical activation function for increasing the accuracy, also better ways of clustering can be explored. This forms a general design of Quantum circuit that can be paramerized as per the application dataset.

Note - Here we are in QiML domain and hence Quantum Measurement is not used and statevector simulator is used to avoid the statiscal ensemble creation to recreate the whole state vector and avoid the computational time as it increases the query calls to circuit.
