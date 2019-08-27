# DeepLearning_FaultLocator
Deep neural network for locating faults in electric distribution systems.
This is a deep neural network modeled in python using tensorflow. The model uses voltage magnitude (voltage sag) measured at buses to predict the location of three-phase-to-ground faults. IEEE34 test system is used here. The training data includes voltage measurements of all phases of buses in the system. However, you can decide how many phase measurements (features) is used for training the neural network. Training data is generated using OpenDSS software based on powerflow simulation under fault condition sand includes 500 samples for each fault location. Labels are bus names. The deep model has three layers (2 hidden layers) with Relu activation functions for hidden hayers and Sigmoid for the output layer. You are going to need Tensorflow (version 1) and Jupyter notebook to run the code.
