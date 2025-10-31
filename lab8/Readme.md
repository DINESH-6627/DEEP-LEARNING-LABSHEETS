## 📘 Topics Covered

### 1. **Introduction to Sequential Modeling**
- Why traditional feedforward networks fail on sequence data
- The concept of temporal dependencies
- Applications: speech recognition, sentiment analysis, language modeling, time-series prediction

### 2. **Recurrent Neural Networks (RNNs)**
- RNN architecture and working mechanism
- Hidden states and recurrence relations
- Vanishing and exploding gradient problems
- Truncated Backpropagation Through Time (BPTT)

### 3. **Implementing RNNs in PyTorch**
- Using `torch.nn.RNN`, `torch.nn.RNNCell`
- Handling input sequences and hidden states
- Building custom RNNs using `nn.Module`
- Visualizing hidden state activations and predictions

### 4. **Advanced RNN Variants**
- **LSTM (Long Short-Term Memory):**
  - Cell state, input gate, forget gate, and output gate
  - Overcoming vanishing gradient problems
- **GRU (Gated Recurrent Unit):**
  - Simplified gating mechanism
  - Computational efficiency

### 5. **Applications**
- Character-level text generation
- Next-word prediction
- Simple time-series forecasting using RNN/LSTM
