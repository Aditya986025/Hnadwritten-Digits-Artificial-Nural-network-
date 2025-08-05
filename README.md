# Hnadwritten-Digits-Artificial-Nural-network-
The Handwritten Digit Recognition project uses an Artificial Neural Network trained on the MNIST dataset to classify digits from 0 to 9. It processes 28x28 pixel images through input, hidden, and output layers using activation functions and backpropagation to achieve high accuracy in digit prediction and as awll as in the handwritting predection.

One Part called "Text", with this you can write text in different font and converts the text into G-Code


![Screenshot 2025-04-19 152244](https://github.com/user-attachments/assets/109b8080-0f8a-465a-ba59-2c3d1dc9727e)

![Screenshot 2025-04-19 152256](https://github.com/user-attachments/assets/eba821fb-1b8d-4642-bb45-a5af7b8c92c8)



![Screenshot 2025-04-19 152326](https://github.com/user-attachments/assets/dd5c5634-300d-438a-83ef-d74ff24b8bb0)



The image shows the summary of a neural network model (specifically `sequential_3`) generated using Keras or TensorFlow.

🔍 Model Summary Explanation in Short layers and concept :

- *Model Type : Sequential — Layers are stacked in order from input to output.
- *Total Parameters : 1,033,100 — All are trainable, with no non-trainable params.
- *Number of Layers : 8 dense (fully automated connected) layers.

---

 📊 Layer-by-Layer Breakdown:

| Layer Name | Layer Type | Output Shape | Parameters | Description |
|------------|------------|--------------|------------|-------------|
| `dense_20` | Dense | (None, 700) | 549,500 | First hidden layer, likely taking 784 inputs (28x28 image), so: 784×700 + 700 (biases) |
| `dense_21` | Dense | (None, 200) | 140,200 | Connects 700 to 200 neurons |
| `dense_22` | Dense | (None, 100) | 20,100 | 200×100 + 100 biases |
| `dense_23` | Dense | (None, 400) | 40,400 | 100×400 + 400 biases |
| `dense_24` | Dense | (None, 500) | 200,500 | 400×500 + 500 biases |
| `dense_25` | Dense | (None, 120) | 60,120 | 500×120 + 120 biases |
| `dense_26` | Dense | (None, 170) | 20,570 | 120×170 + 170 biases |
| `dense_27` | Dense | (None, 10) | 1,710 | Output layer for digit classification (0–9) |

---

🧠 Model Characteristics:

- * Input : Presumably an image flattened to 784 units (28×28 pixels).
- * Output: 10 units for digit classification using Softmax (not shown, but typical).
- * Activation Functions: Likely ReLU for hidden layers and Softmax for the output.
- * Architecture: Deep feedforward neural network with multiple fully connected layers..

