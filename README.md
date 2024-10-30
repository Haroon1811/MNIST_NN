The Neural network is created using torch.nn and torch.nn.functional. 
The Neural Network architecture consists of four nn.Linear() layers and 1 nn.ReLU() ,Non-linear activation, layer. 
Loss function used is nn.functional.nll_loss().
Optimizer is nn.optim.Adam() with learning rate, lr=1e-3 The training accuracy is 94.1%
