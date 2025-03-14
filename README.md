# 🐺 Wolf vs. Husky Classification using Neural Networks 🐶

This project implements a neural network to classify images of **wolves** and **huskies** using deep learning. The dataset consists of images stored in `train/` and `test/` directories. The model is trained from scratch using **NumPy** without relying on deep learning frameworks like TensorFlow or PyTorch.

---

## 📂 Project Structure

```
├── WolfVsHusky.ipynb  # Jupyter Notebook for model training & testing
├── train/             # Training dataset (contains wolf & husky images)
│   ├── wolf/         # Images of wolves
│   ├── husky/        # Images of huskies
├── test/              # Test dataset
│   ├── wolf/         # Images of wolves
│   ├── husky/        # Images of huskies
├── README.md          # Project documentation
```

---

## 📌 Dataset

- **Train Folder (********`train/`********\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*)**
  - Contains images of **wolves** and **huskies** for training the model.
- **Test Folder (********`test/`********\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*)**
  - Contains images for evaluating model performance.

---

## 🚀 Installation

Ensure you have Python installed and the required libraries:

```bash
pip install numpy matplotlib opencv-python
```

---

## 🏉 Training the Model

Run the Jupyter Notebook **WolfVsHusky.ipynb** to train the neural network:

```bash
jupyter notebook WolfVsHusky.ipynb
```

---

## 🧪 Testing the Model

To test the model on unseen images, run the notebook and evaluate performance using the images in `test/`.

---

## 📊 Model Architecture

- **Input Layer:** Image pixels as input
- **Hidden Layers:** Fully connected layers with **ReLU activation**
- **Output Layer:** Sigmoid activation for **binary classification (wolf vs. husky)**

---

## 🔥 Results

After training, the model achieves **high accuracy** in distinguishing between wolves and huskies.

---
## 🤖 Future Improvements

- Implement CNN (Convolutional Neural Networks) for better accuracy.
- Use pre-trained models like **ResNet or VGG16** for feature extraction.

---

## 🐜 License

This project is open-source and free to use.

---

### 🎯 **Contributors**

👤 **[Mohamed Sobhy Mohamed]**\
📧 Contact: [mohamedsaker162002\@gmail.com]

---

Happy coding! 🚀🐺🐶

