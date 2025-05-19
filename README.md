# -DEEP-LEARNING-PROJECT
*COMPANY: CODTECH IT SOLUTIONS*

*NAME: TANISHA SAINI*

*INTERN ID: CT04DL712*

*DOMAIN: DATA SCIENCE*

*DURATION: 4 WEEKS*

*MENTOR: NEELA SANTHOSH*

*DESCRIPTION OF TASK*

# 🎯 CodTech Task 2 - Emotion Detection using LSTM (NLP Project)

This project is a submission for **Task 2** of the **CodTech Data Science Internship**, where I implemented a **deep learning model** for emotion detection in textual data using **Natural Language Processing (NLP)** techniques. The goal was to build a functional deep learning solution that can detect emotions from human-written sentences and provide meaningful suggestions or actions based on the detected mood.

---

## 🧠 Project Objective

The primary objective of this task was to implement a **deep learning model** for **Natural Language Processing (NLP)** using tools like **TensorFlow/Keras** or **PyTorch**. I chose the NLP path and focused on **emotion classification**, which involves predicting the emotional state (e.g., joy, sadness, anger, love, surprise, fear) from a sentence. This is commonly used in real-world applications such as chatbots, sentiment monitoring systems, mental health assessments, and content recommendation engines.

---

## ⚙️ Technical Approach

The project was implemented using the following steps:

1. **Data Preparation**
   - Used provided files: `train.txt`, `val.txt`, and `test.txt`
   - Each line in the dataset had a text and its corresponding emotion label, separated by a semicolon (`;`)
   - Loaded the data into Pandas DataFrames
   - Preprocessed the text using Keras's `Tokenizer` and padded sequences to a maximum length

2. **Label Encoding**
   - Emotion labels were encoded into numerical format using `LabelEncoder`
   - Labels were converted to one-hot encoding using `to_categorical` for multi-class classification

3. **Model Building**
   - Created an LSTM-based model using Keras:
     - `Embedding` layer to convert text to word vectors
     - `LSTM` layer to capture sequential patterns
     - `Dropout` layer to reduce overfitting
     - `Dense` output layer with `softmax` activation

4. **Training and Evaluation**
   - Trained the model on `train.txt`, validated on `val.txt`, and evaluated on `test.txt`
   - Achieved strong accuracy on unseen test data
   - Plotted **accuracy and loss graphs** for both training and validation

5. **Prediction Function**
   - Built a function to accept user input text and return:
     - Detected emotion
     - Personalized content suggestion (like a Netflix genre or self-help resource)

6. **Model Saving**
   - Saved the trained model (`emotion_model.h5`) and supporting files (`tokenizer.pickle`, `label_encoder.pickle`) for future use

---

## 🌍 Societal Impact

This project can have a significant impact in various fields:

- **Mental Health Support**: By analyzing what people write on social media or mental health forums, this tool can help detect emotional distress early and trigger alerts for professionals.
- **Education**: Online learning platforms can tailor content based on students' emotional states, improving engagement.
- **Customer Support**: Businesses can use this to assess user sentiment in real-time and route chats to appropriate human agents or bots.
- **Entertainment**: Apps like Netflix or YouTube can recommend content based on user mood, enhancing user experience.
- **Human-Computer Interaction**: Makes digital systems more empathetic and responsive to human emotions.

This model demonstrates how **data science** and **deep learning** can be applied to create emotionally intelligent systems that benefit individuals and society.

---

## 🧰 Tools and Technologies Used

- Python
- TensorFlow/Keras
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab


---

## 🚀 How to Use

1. Clone this repository or open the notebook in Google Colab
2. Make sure `train.txt`, `val.txt`, and `test.txt` are in your working directory
3. Run the cells to train the model (or load the saved model)
4. Use the prediction function to test emotions from any text input

---

## 🙌 Acknowledgements

This project was completed as part of my **Data Science Internship at CodTech**. Special thanks to the mentors, guides, and the CodTech team for providing the opportunity and resources to complete this work.

---

## 📌 Contact

For any queries or feedback, feel free to reach out via GitHub or email.

## Sample Output![t2](https://github.com/user-attachments/assets/9b43f2eb-ef4e-4994-b8c6-7b497a71b3ba)

