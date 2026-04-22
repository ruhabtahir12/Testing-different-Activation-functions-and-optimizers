Comparative analysis of different activation functions (ReLU, Sigmoid, Tanh) and optimizers (SGD, SGD with Momentum, RMSprop, Adam) on neural networks using synthetic datasets. The study evaluates their impact on convergence speed, training stability, and generalization performance.
## 📈 Key Observations

- ReLU performed best in deep networks due to stable gradients and faster convergence.
- Sigmoid worked well in shallow networks but suffered from vanishing gradient in deeper architectures.
- Tanh performed better than Sigmoid but still showed limitations in deep networks.
- SGD required careful tuning and showed unstable convergence.
- RMSprop converged faster but tended to overfit on small datasets.
- Adam provided the best balance between speed and generalization.
- 
⚠️ Challenges Identified

- Overfitting observed in small datasets with complex models
- Large gap between training and validation accuracy when using certain optimizers
- Sensitivity of SGD to learning rate
