# Question Answering System
Overview:

This project is a question-answering system that uses the DistilBERT model for extracting answers from a given context. The model is fine-tuned on a custom dataset with questions and answers to improve its performance on specific tasks.

Project Structure:

•	data/: Contains the CSV file with the dataset (qna_output.csv).

•	src/: Contains the main Python code for loading data, training the model, and generating answers.

•	requirements.txt: Lists the dependencies required for the project.

Dependencies:

•	Ensure you have the required libraries installed. You can do this by running:

pip install -r requirements.txt

Dataset:

The dataset should be a CSV file with the following columns:
•	Text
•	question
•	answer

Usage:

1.	Prepare the Dataset: Ensure your dataset is in a CSV file with columns text and answer.
2.	Training the Model: The code will load and preprocess the dataset.	It will then fine-tune the DistilBERT model with the provided dataset.
3.	Generating Answers:	You can use the trained model to answer questions based on any input text.
  
Training Parameters:

•	Epochs: 50

•	Batch Size: 8

•	Learning Rate: 2e-5

Acknowledgements:

•	Hugging Face Transformers library for providing the DistilBERT model and utilities.

•	PyTorch for the deep learning framework.
