

# 🃏 Playing Cards Image Classification

This project focuses on building a machine learning model to classify images of playing cards. The model is trained using a **Convolutional Neural Network (CNN)** to accurately identify the **rank (A, 2, 3... K)** and **suit (Hearts, Diamonds, Clubs, Spades)** of a card from an image.

This can be used in various applications such as:
- Automated card game scoring
- Virtual card recognition
- AI-assisted card analysis  

## 🚀 Features
- **Image Classification**: Predicts the rank and suit of a playing card.  
- **Deep Learning Model**: Built using **PyTorch**.  
- **Dataset Handling**: Loads and processes playing card images.  
- **Training & Evaluation**: Includes training scripts, model evaluation, and accuracy tracking.  

---

## 📂 Dataset Structure
Ensure that your dataset is structured as follows before training:

```
dataset/
├── hearts/
│   ├── 2_of_hearts.png
│   ├── 3_of_hearts.png
│   └── ...
├── diamonds/
│   ├── 2_of_diamonds.png
│   ├── 3_of_diamonds.png
│   └── ...
├── clubs/
│   ├── 2_of_clubs.png
│   ├── 3_of_clubs.png
│   └── ...
└── spades/
    ├── 2_of_spades.png
    ├── 3_of_spades.png
    └── ...
```

---

## ⚙️ Installation

To set up and run this project locally, follow these steps:

### 1️⃣ Clone the repository:
```bash
git clone https://github.com/Abhinav-gupta-123/playing-cards-image-classification.git
cd playing-cards-image-classification
```

### 2️⃣ Create and activate a virtual environment:  
- **Windows**:
  ```bash
  python -m venv env
  env\Scripts\activate
  ```
- **Mac/Linux**:
  ```bash
  python3 -m venv env
  source env/bin/activate
  ```

### 3️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 🏋️‍♂️ Training the Model

Run the Jupyter Notebook to train the model:

```bash
jupyter notebook
```

Then open `model.ipynb` and run all cells sequentially.

---

## 🏆 Model Architecture

The model is a **Convolutional Neural Network (CNN)** implemented in PyTorch.  
It consists of:
- **Convolutional Layers**: Extract spatial features from card images.
- **Max-Pooling Layers**: Reduce dimensionality.
- **Fully Connected Layers**: Perform final classification.  

---

## 📊 Results

| Metric               | Value |
|----------------------|-------|
| **Training Accuracy**  | 98%  |
| **Validation Accuracy**| 95%  |
| **Test Accuracy**      | 94%  |

For detailed performance analysis, refer to **`model.ipynb`**.

---

## 🤝 Contributing

Contributions are welcome! If you have ideas for improvements, follow these steps:

1. **Fork the repository**  
2. **Create a new branch**: `git checkout -b feature-name`  
3. **Make changes and commit**: `git commit -m "Added new feature"`  
4. **Push to your fork**: `git push origin feature-name`  
5. **Submit a Pull Request**  

---

---

## 📞 Contact
For any queries or collaborations, feel free to reach out:  
📧 **Email**: *abhinavg963@gmail.com*  
🔗 **GitHub**: [Abhinav Gupta](https://github.com/Abhinav-gupta-123)

---

This **README** provides clear guidance to users on how to set up, use, and contribute to your project. 🚀✨
