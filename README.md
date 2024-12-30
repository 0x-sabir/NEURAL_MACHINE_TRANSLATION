# Neural Machine Translation: Translating Nagamese to English

This project focuses on developing a Neural Machine Translation (NMT) system to translate Nagamese, a language spoken in Nagaland, India, into English. Due to the limited availability of Nagamese resources, the project employs the Holy Bible as a parallel corpus for training the translation model.

## Project Workflow:
Data Collection: Scraping the Bible to obtain parallel texts in Nagamese and English.

Data Preprocessing: Cleaning and preparing the data, including tokenization and vocabulary building, using tools like OpenNMT.

Model Selection: Choosing OpenNMT for its flexibility in configuring sequence-to-sequence models suitable for NMT tasks.

Model Training: Configuring and training the model with parameters tailored for small datasets, such as adjusting training steps and batch sizes.

Model Evaluation and Testing: Assessing the model's performance to ensure accurate translations.

Fine-Tuning: Refining the model to enhance translation quality, potentially by adjusting hyperparameters or incorporating additional data.

## Key Considerations
Limited Data: The scarcity of Nagamese-English parallel texts necessitates careful configuration of training parameters to prevent overfitting and ensure meaningful learning.

OpenNMT: Utilized for its robust features in NMT, including support for tokenization, vocabulary management, and model training.

Configuration Parameters: Parameters such as train_steps, valid_steps, batch_size, and learning_rate are adjusted to accommodate the limited dataset size, ensuring efficient training and validation processes.

## Conclusion
This project demonstrates a practical approach to building an NMT system for low-resource languages like Nagamese by leveraging available parallel corpora and configuring training processes to suit the data constraints.

For a detailed walkthrough and code implementation, refer to the original article: https://medium.com/@sabirasdev/neural-machine-translation-b537c87a8e2f
