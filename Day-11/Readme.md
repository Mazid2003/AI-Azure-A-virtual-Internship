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

![WhatsApp Image 2025-06-04 at 7 08 01 AM](https://github.com/user-attachments/assets/99fcc218-b697-4eb9-9d64-89f359c194f0)

| Aspect              | Machine Learning       | Deep Learning                         |
| ------------------- | ---------------------- | ------------------------------------- |
| Feature Engineering | Manual                 | Automatic                             |
| Data Requirement    | Less                   | Large volumes required                |
| Interpretability    | Easier to interpret    | More complex, harder to interpret     |
| Performance         | Good for simpler tasks | Better for complex, large-scale tasks |


**🧩 Deep Neural Networks (DNN)**

![WhatsApp Image 2025-06-04 at 7 08 00 AM](https://github.com/user-attachments/assets/d73a49f4-4a85-4d9d-aa4b-9b6dc3a16030)

DNNs consist of multiple layers of artificial neurons, with each layer transforming its input data to a slightly more abstract representation.

**🧱 Representation of DNN**

![WhatsApp Image 2025-06-04 at 7 08 03 AM (2)](https://github.com/user-attachments/assets/0284aec7-e3af-4d45-9d1b-466c09d75928)

A DNN has:

Input layer: Accepts the features.

Hidden layers: One or more layers that transform data.

Output layer: Produces final prediction/classification.

**🧠 Neurons & Artificial Neural Networks (ANN)**

![WhatsApp Image 2025-06-04 at 7 08 02 AM](https://github.com/user-attachments/assets/91380fef-9e2a-4afa-bd6b-4ffe321ad687)

**🧬 Components of an Artificial Neuron**

![WhatsApp Image 2025-06-04 at 7 08 03 AM (1)](https://github.com/user-attachments/assets/1f65b1bb-b9eb-44f4-889a-4d2c3086da6b)

Inputs (x₁, x₂, ..., xₙ)

Weights (w₁, w₂, ..., wₙ)

Bias (b)

Activation function (σ)

Output: y = σ(w₁x₁ + w₂x₂ + ... + wₙxₙ + b)

**Working of ANN:**

![WhatsApp Image 2025-06-04 at 7 08 04 AM](https://github.com/user-attachments/assets/1560cff9-7f9b-4339-853d-3ff07e7905e4)

**🔹 Single Neuron**

![WhatsApp Image 2025-06-04 at 7 08 02 AM (2)](https://github.com/user-attachments/assets/c72d7200-b279-49e5-abc7-a28c3f1a8dc4)

Acts as a basic unit of computation, similar to a perceptron. It applies weights and bias to input features, then passes it through an activation function.

**⚙️ Activation Functions**

![WhatsApp Image 2025-06-04 at 7 08 02 AM (1)](https://github.com/user-attachments/assets/41d8eda7-701a-430c-8633-86c59fae3e0f)

Introduce non-linearity to the model:

ReLU (Rectified Linear Unit)

Sigmoid

Tanh

Softmax (for multiclass classification)

**🔁 Training a Neural Network**

**▶️ Forward Propagation**

![WhatsApp Image 2025-06-04 at 7 08 04 AM (2)](https://github.com/user-attachments/assets/8d8af988-846d-4070-a443-c1be7f10378d)

Input is passed through each layer

Weighted sum is computed and passed through activation functions

Output is generated

**⏮️ Backward Propagation**

![WhatsApp Image 2025-06-04 at 7 08 04 AM (1)](https://github.com/user-attachments/assets/4c2361ba-5d11-40d0-8e24-48505e0bf015)

Loss is calculated by comparing prediction to actual output

Gradients are computed using chain rule

Weights are updated using gradient descent

**⌛ Epochs & Batch Size**

![WhatsApp Image 2025-06-04 at 7 08 03 AM (3)](https://github.com/user-attachments/assets/1fc030ab-d555-49a7-9e03-3e79a0445365)

Epoch: One complete pass through the entire dataset.

Batch Size: Number of training examples processed before the model updates weights.

**⚙️ Hyperparameters in Neural Networks**

![WhatsApp Image 2025-06-04 at 7 08 06 AM](https://github.com/user-attachments/assets/2b19b846-fa5d-479d-853b-3ad497c7b329)

**🔧 Network Structure**

![WhatsApp Image 2025-06-04 at 7 08 05 AM (2)](https://github.com/user-attachments/assets/0db50509-be00-4821-a37b-8a60eebd0bb7)

Number of Hidden Layers and Neurons: Controls model capacity.

![WhatsApp Image 2025-06-04 at 7 08 05 AM (1)](https://github.com/user-attachments/assets/c2f9a2f4-fada-4160-9106-8c4aaa730242)

Dropout: Prevents overfitting by randomly disabling neurons during training.

![WhatsApp Image 2025-06-04 at 7 08 05 AM](https://github.com/user-attachments/assets/bbf06c53-9291-4425-805c-492c058131eb)

Activation Functions: Adds non-linearity and affects learning behavior.

**🧪 Training Algorithm**

![WhatsApp Image 2025-06-04 at 7 08 07 AM](https://github.com/user-attachments/assets/bea3e903-3e9d-4cce-91d2-5cc41f157449)

Learning Rate: Controls how much weights are adjusted.

Loss Functions:

![WhatsApp Image 2025-06-04 at 7 08 06 AM (3)](https://github.com/user-attachments/assets/33aa6435-4a30-4c95-b44c-86cfefa688a5)

MSE (Mean Squared Error) – Regression tasks

Cross-Entropy – Classification tasks

**🔄 Multilayer Perceptron (MLP)**

![WhatsApp Image 2025-06-04 at 7 08 06 AM (2)](https://github.com/user-attachments/assets/254d3552-7226-414a-9538-0840a3f922ac)

A fully connected feedforward neural network:

Contains multiple layers of neurons.

Each neuron in one layer is connected to every neuron in the next.

Ideal for structured data tasks.

