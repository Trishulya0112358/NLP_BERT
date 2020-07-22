# NLP_BERT
Using BERT (Bidirectional Encoder Representations from Transformers) for Sentiment Analysis

BERT is based on Transformer Architecture
It has been trained by Masked LM method

This notebook uses BertTokenizer and BertForSequenceClassification (for padding, special tokens and attention masks)

Adam Optimizer is used during back propagation.

Learning rate policy : get_linear_schedule_with_warmup

tqdm library is used for a visual feedback of loops
