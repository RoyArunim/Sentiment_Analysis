# Sentiment_Analysis
Just trying out BertTokenizer on random sample data
# Initial Setup
Install Pytorch: follow steps mentioned in this [link](https://pytorch.org/get-started/locally/)

# Transformers
Our main motive is to play around with HuggingFace transformers and see how they work on a random text. Firstly we choose a model from the huggingface website based
on Text Analysis. Thereafter we train our BertTokenizer on the model we have chosen. After tokenization and training the model on those tokens we normalize the output
to obtain probabilistic results for the output where there is maximum attention.
