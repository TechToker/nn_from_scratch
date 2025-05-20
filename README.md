# NN from scratch
By using only stones and sticks (i.e python with numpy) implemenation of basic MLP architectures

Incude training and backpropagation from scratch!

- MLP regression on AutoMPG dataset
  - Linear layer
  - Tanh
  - MSE loss
- MLP classification on Titanic dataset
  - Linear layer
  - Tanh
  - Binary cross-entropy
- CNN MLP multiclass classification on MNIST dataset (trained on only 128 samples with batchsize=8 due to performance issues)
  - Conv layer 
  - MaxPool
  - ReLU
  - Linear layer
  - Cross-entropy loss

|Model|Train score|Val score|
|:-------------:|:-------------:|:-------------:|
|AutoMPG|MAE: 1.7997|MAE: 1.93|
|Titanic|acc 0.79|acc: 0.79|
|MNIST |acc: 0.9062|acc:0.7801|
