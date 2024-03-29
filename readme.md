# SMS/Email Spam Classifier

This project aims to classify SMS or email messages as either spam or not spam using machine learning techniques. The classifier is built using a dataset sourced from Kaggle and implemented in a Jupyter Notebook. Additionally, the model is integrated into a Streamlit web application for ease of use.

## Requirements

Ensure you have the following libraries installed:

- Python 3.x
- Jupyter Notebook
- Streamlit
- Pandas
- NumPy
- Scikit-learn

You can install these dependencies using pip:

```bash
pip install jupyter streamlit pandas numpy scikit-learn
```

## Dataset

The dataset used for training the model is obtained from Kaggle. It contains labeled examples of SMS or email messages, indicating whether they are spam or not spam. Ensure the dataset file (`spam.csv`) is placed in the `data` directory before running the Jupyter Notebook.

## Jupyter Notebook

The `main.ipynb` Jupyter Notebook contains the code for data preprocessing, model training, evaluation, and saving the trained model. Open the notebook in a Jupyter environment and follow the instructions to execute each cell step by step.

## Streamlit Web Application

The Streamlit web application `app.py` provides an interface for users to input a text message and get the prediction of whether it's spam or not. To run the application, execute the following command in your terminal:

```bash
streamlit run app.py
```

This will launch a local server hosting the web application. Open the provided URL in your web browser to access the application interface.

## Usage

1. After launching the Streamlit application, you'll see an input box where you can enter a text message.
2. Type or paste the message you want to classify into the input box.
3. Click the "Predict" button.
4. The application will display whether the message is predicted to be spam or not spam.

## Acknowledgments

- The dataset used in this project is sourced from Kaggle: [SMS Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset)
- This project is for educational purposes and was inspired by various tutorials and resources available online.

