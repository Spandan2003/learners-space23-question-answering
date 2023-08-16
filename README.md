# learners-space23-question-answering
This is the final project to the Learner's Space 23: Neural Networks and LLM. My project involves using a pretrained LLM and finetune it to give us a model that could answer questions based on a contextual block of text.

### Aim
The aim of the project is to build a question answering model that would be able to search from a block of text and find the answer for a particular question

### Model
We have chosen the lightweight "distilbert", a smaller, distilled version of the famous BERT language model.

### Dataset
QUAD dataset (Stanford Question Answering Dataset)

### Problems faced:
1. Storing the model: There were a couple of issues where I could store the model but the same model was not able to be loaded into a new notebook. This was as I found later, because the model was defined using custom loss functions. Instead I had to just pass a dummy loss. 
