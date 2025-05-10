# 🩺 Chest X-Ray Detection

This project implements a Convolutional Neural Network (CNN) to classify chest X-ray images as either 'Normal' or 'Pneumonia'. It utilizes Python, TensorFlow/Keras, and essential data science libraries to process the dataset, train the model, and evaluate its performance.

## 📁 Project Structure

```
Chest-X-Ray-Detection/
├── chest-x-ray-classification-cnn.ipynb  # Jupyter notebook with the complete workflow
├── README.md                             # Project documentation
```

## 🔧 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hassanw65/Chest-X-Ray-Detection.git
   cd Chest-X-Ray-Detection
   ```

2. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

   *If `requirements.txt` is not provided:*
   ```bash
   pip install tensorflow keras matplotlib seaborn pandas numpy
   ```

## 🚀 Usage

1. **Prepare the dataset:**
   - Download the Chest X-Ray Images (Pneumonia) dataset from [Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia).
   - Extract the dataset and place it in a directory named `chest_xray` within the project folder.

2. **Open the Jupyter notebook:**
   ```bash
   jupyter notebook chest-x-ray-classification-cnn.ipynb
   ```

3. **Follow the steps in the notebook:**
   - Load and preprocess the dataset (resize images, normalize pixel values).
   - Build and compile the CNN model.
   - Train the model on the training dataset.
   - Evaluate the model's performance on the validation and test datasets.
   - Visualize training history and performance metrics.

## 📊 Results

The notebook provides visualizations of the model's accuracy and loss over epochs, as well as evaluation metrics such as precision, recall, and F1-score on the test dataset.

## 🤝 Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

## 📄 License

This project is licensed under the MIT License.
