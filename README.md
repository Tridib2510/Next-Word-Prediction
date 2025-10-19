# Next-Word-Prediction

**Next-Word-Prediction** is a deep learning-based application designed to predict the next word in a given text sequence. Utilizing a trained LSTM (Long Short-Term Memory) model, this project demonstrates how neural networks can be applied to natural language processing tasks to enhance text input experiences.

---

## 🧠 Project Overview

This project leverages an LSTM model to predict the next word in a sequence, providing users with intelligent text completion suggestions. It's particularly useful for applications like chatbots, writing assistants, and any system requiring predictive text input.

---

## ⚙️ Features

- **LSTM-based Prediction**: Utilizes a trained LSTM model for accurate next-word prediction.
- **Tokenizer Integration**: Employs a tokenizer to process and convert text data into a format suitable for the LSTM model.
- **User-Friendly Interface**: Provides an intuitive interface for users to input text and receive predictions.
- **Pre-trained Model**: Includes a pre-trained model (`next_word_model.h5`) for immediate use.
---

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Tridib2510/Next-Word-Prediction.git
cd Next-Word-Prediction
2. Install Dependencies
Ensure you have Python 3.6+ installed. Then, run:

bash
Copy code
pip install -r requirements.txt
3. Run the Application
bash
Copy code
python app.py
This will launch the application, allowing you to input text and receive next-word predictions.

📘 Usage
Input a Text Sequence: Type a sequence of words into the input field.

Receive Prediction: The model predicts the next most likely word.

Iterate: Continue typing to get subsequent predictions.

🧪 Training the Model
To train the model from scratch:

Prepare the Data: Use hamlet.txt or any other text corpus.

Preprocess the Text: Tokenize and prepare sequences suitable for LSTM.

Train the Model: Use experiment.ipynb to train the LSTM model.

Save the Model: Save as next_word_model.h5 for future use.

📦 Dependencies
tensorflow

numpy

pandas

keras

nltk

flask

pickle

Install with:

bash
Copy code
pip install -r requirements.txt

