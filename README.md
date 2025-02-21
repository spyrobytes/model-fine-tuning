# Fine Tuning LLM Foundation Models
Workflow for fine tuning LLM foundation models.

The goal of this project is to demonstrate workflow for fine-tuning LLM models. We'll start with fine tuning BERT for a binary classification task to illustrate the basic workflow. We use the Hugging Face's transformer's framework and datasets library. The workflow consists of the following:

1. Load the dataset and split it into training, validation, testing sets
2. Tokenize the data: Use the BertTokenizer to preprocess the text.
3. Fine-tune the model: Use the Trainer API to fine-tune BERT for binary classification.
4. Evaluate the model: Test the model on the testing set to measure its performance.
5. Save the fine-tuned model for future use.
6. Deploy and infer: Use the fine-tuned model to make predictions on new data.
