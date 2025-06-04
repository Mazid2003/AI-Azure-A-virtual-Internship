**🗓 Day - 11 :Deep Learning & Neural Networks🚀**

Date: 3/06/2025

**📌 What is Deep Learning?**

![WhatsApp Image 2025-06-04 at 7 08 01 AM (2)](https://github.com/user-attachments/assets/99e3dd76-82ef-40df-99c5-64607c2a321d)

Deep Learning is a subset of Machine Learning that uses neural networks with multiple layers (deep neural networks) to model complex patterns in large datasets. It is especially useful for tasks such as image recognition, speech processing, and natural language understanding.

**🤔 Why Deep Learning?**

![WhatsApp Image 2025-06-04 at 7 08 01 AM (1)](https://github.com/user-attachments/assets/7c1c1c1c-84d8-4ccb-b970-6ce958054721)

Capable of automatically learning features from raw data.

Performs well on unstructured data (images, audio, text).

Outperforms traditional ML in complex problem domains.

Enables end-to-end learning without manual feature engineering.

**🆚 Machine Learning vs Deep Learning**

| Aspect              | Machine Learning       | Deep Learning                         |
| ------------------- | ---------------------- | ------------------------------------- |
| Feature Engineering | Manual                 | Automatic                             |
| Data Requirement    | Less                   | Large volumes required                |
| Interpretability    | Easier to interpret    | More complex, harder to interpret     |
| Performance         | Good for simpler tasks | Better for complex, large-scale tasks |


**🧩 Deep Neural Networks (DNN)**

DNNs consist of multiple layers of artificial neurons, with each layer transforming its input data to a slightly more abstract representation.

**🧱 Representation of DNN**

A DNN has:

Input layer: Accepts the features.

Hidden layers: One or more layers that transform data.

Output layer: Produces final prediction/classification.

**🧠 Neurons & Artificial Neural Networks (ANN)**

🧬 Components of an Artificial Neuron

Inputs (x₁, x₂, ..., xₙ)

Weights (w₁, w₂, ..., wₙ)

Bias (b)

Activation function (σ)

Output: y = σ(w₁x₁ + w₂x₂ + ... + wₙxₙ + b)

**🔹 Single Neuron**

Acts as a basic unit of computation, similar to a perceptron. It applies weights and bias to input features, then passes it through an activation function.

**⚙️ Activation Functions**

Introduce non-linearity to the model:

ReLU (Rectified Linear Unit)

Sigmoid

Tanh

Softmax (for multiclass classification)

**🔁 Training a Neural Network**

**▶️ Forward Propagation**

Input is passed through each layer

Weighted sum is computed and passed through activation functions

Output is generated

**⏮️ Backward Propagation**

Loss is calculated by comparing prediction to actual output

Gradients are computed using chain rule

Weights are updated using gradient descent

**⌛ Epochs & Batch Size**

Epoch: One complete pass through the entire dataset.

Batch Size: Number of training examples processed before the model updates weights.

**⚙️ Hyperparameters in Neural Networks**

**🔧 Network Structure**

Number of Hidden Layers and Neurons: Controls model capacity.

Dropout: Prevents overfitting by randomly disabling neurons during training.

Activation Functions: Adds non-linearity and affects learning behavior.

**🧪 Training Algorithm**

Learning Rate: Controls how much weights are adjusted.

Loss Functions:

MSE (Mean Squared Error) – Regression tasks

Cross-Entropy – Classification tasks

**🔄 Multilayer Perceptron (MLP)**

A fully connected feedforward neural network:

Contains multiple layers of neurons.

Each neuron in one layer is connected to every neuron in the next.

Ideal for structured data tasks.

