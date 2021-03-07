# NER_Covid19

The code is developed to do Named-entity recognition (NER) based on BERT through huggingface.
The codes are under developed.
### Structure:
* NER_with_BERT.ipynb: Setup code, do sentences tokenization and fine-tune the pretrain from bert
* NER_BERT_evaluation.ipynb: Read model from local file, do evaluations.
* NER_bert_bilstm_crf.ipynb: Based on Tensorflow framework, add a CRF layer for calculating the loss function. But in the end, the performance is worse than finetune the Bert.
