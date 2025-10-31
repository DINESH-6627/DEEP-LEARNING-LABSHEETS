## 📘 Contents

### 1. **Data Loading and Visualization**
- Using **PyTorch Datasets** and **DataLoaders**
- Loading custom datasets and applying transformations
- Visualizing sample images, labels, and class distributions
- Understanding input normalization ranges (e.g., [0, 1] vs. [-1, 1])

### 2. **Neural Network Architecture**
- Designing deeper models using multiple hidden layers
- Implementing with `torch.nn.Sequential` and custom `nn.Module`
- Role of activation functions (ReLU, Tanh, Softmax)
- Understanding overfitting and underfitting in complex architectures

### 3. **Training the Network**
- Forward pass and backward propagation
- Loss functions (Cross-Entropy, MSE)
- Optimizers (SGD, Adam)
- Tracking accuracy and loss during training
- Implementing early stopping

### 4. **Testing and Evaluation**
- Evaluating performance on test data
- Plotting loss and accuracy curves
- Confusion matrix and classification report
- Visualizing predictions vs. ground truth

### 5. **Advanced Concepts**
#### 🔹 Dropout
- Concept and motivation behind dropout regularization  
- Implementing dropout in PyTorch (`nn.Dropout`)  
- Effect of dropout rates on training performance  

#### 🔹 Normalization
- Importance of feature scaling  
- Batch Normalization (`nn.BatchNorm1d`, `nn.BatchNorm2d`)  
- Layer Normalization (`nn.LayerNorm`)  
- Impact on convergence and stability  

#### 🔹 Numerical Stability
- Avoiding overflow/underflow in computations  
- Log-sum-exp trick for stable loss calculations  
- Gradient clipping to prevent exploding gradients  
- Best practices for stable training  
