# Quantum_computing
A repo for quantum computing and quantum machine learning concepts and model implementations.

Implementations:\
   The first model "QSVM_implemetation" is a Quantum support vector classifier modified version reproduced from     qiskit tutorial "quantum kernel machine learning" and the paper " supervised learning with quantum enhanced       feature spaces".
   It is implemented in three versions: 
      1. Using the Qiskit QSVC function with the ZZ-feature map.
      2. Using the classical SVC function and with an input Precomputed kernel matrix.
      3. Using the classical SVC function with the kernel as a callable function.
      All of them get a 92% accuracy on the moons dataset. (new implementation)

   The second model will be an implementation of a quantum convolutional neural network model inspired and          reproduced from the paper: "quanvolutional neural networks".
