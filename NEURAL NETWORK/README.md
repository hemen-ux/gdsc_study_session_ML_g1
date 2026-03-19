# 🧠 Fake News Detection Neural Network

## 📌 Project Overview

This project focuses on building a **Neural Network model** that classifies news headlines as either **Fake News** or **Real News**.
The model learns patterns from labeled text data and predicts the authenticity of new headlines.



## 🎯 Objective

* Convert text data into numerical form using **TF-IDF**
* Train a neural network to classify news
* Evaluate model performance using accuracy
* Test the model with custom inputs



## 📊 Dataset

The dataset consists of:

* `text` → news content
* `label` → classification

  * `0` → Real News
  * `1` → Fake News



## ⚙️ Methodology

### 🔹 1. Data Preprocessing

* Combined text fields (if necessary)
* Converted text into numerical vectors using **TF-IDF Vectorization**



### 🔹 2. Train-Test Split

* 80% Training Data
* 20% Testing Data



## 🧠 Neural Network Architecture

I used a **feedforward neural network** with:

* Input layer (TF-IDF features)
* Two hidden layers (128 and 64 neurons)
* One output layer with 1 neuron



## 🔁 Training Details

### ✅ Epochs

The model was trained for **10 epochs**.



### ✅ Activation Functions

* **ReLU** for hidden layers
* **Sigmoid** for output layer



### ✅ Loss Function

* Binary Crossentropy



### ✅ Optimizer

* Adam optimizer


## 📈 Model Performance

* The model achieved high accuracy on the test dataset (typically around 85%–95% depending on data quality).



## 🧪 Example Predictions

| Input Headline                         | Prediction |
| -------------------------------------- | ---------- |
| Scientists confirm water on Mars       | Real News  |
| Aliens secretly control the government | Fake News  |



## 🚀 How to Run

1. Upload dataset (`Fake.csv` and `True.csv`)
2. Run the notebook step-by-step
3. Train the model
4. Evaluate performance
5. Test with custom headlines



## 📦 Output

* Trained neural network model
* Accuracy results
* Predictions on new data



## 💡 Future Improvements

* Increase dataset size
* Try more hidden layers
* Experiment with more epochs
* Compare with other ML models




