# NLPlay with Transformers (Summer of Code Project)
### Mentor: Tezan Sahu
This is a Learning Project and has been divided into 3 phases:

**Phase 1:**
* Introduction to NLP
* Introduction to `PyTorch`
* Creating a Sentiment Classifier using Neural Network
* Learning about `RNNs`, `LSTMs` and `GRUs`
* Implementing LSTM for Sentiment Analysis

The Sentiment Analysis has been carried out on the IMDB Movie Review dataset which consists of 50,000 reviews,
and is divided equally into positive and negative reviews.
The models have been made by utilizing the PyTorch framework.

**Phase 2:**
* Introduction to Attention in Deep Learning
* Introduction to Transformers and their working
* Learning about Transformers like `BERT`, `RoBERTa`, `XLNet` & `DistilBERT`
* Creating a Sentiment Classifier with BERT architecture
* With the BERT architecture in place, replaced the Model and Tokenizer with:
  * `distilbert-base-uncased` (DistilBERT)
  * `roberta-base` (RoBERTa)
  * `xlnet-base-cased` (XLNet)

The ` HuggingFace` Transformers Documentation proved to be really useful while coding the models, it is easy to understand
and highly user-friendly.


**Phase 3:**
* Introduction to Text Generation using Transformers
* Introduction to `GPT-2` and `T5`
* Learning about methods to evaluate Text Generation Models
* Implemented GPT-2 and T5 model for Text Generation on a custom made dataset
and evaluated their preformance using `BLEU` scores

The `DATA_SOC` file contains the data used as input for the models. The models were tested on 3 different domains namely, 
Scientific Literature, Finance and Music/Entertainment, with 10 articles in each domain. The respective BLEU scores were
calculated for each article in each domain as well as an overall BLEU score for each domain.\

Based on the results, we conclude that the GPT-2 model works best in the "Finance" domain whereas the T5 model preforms the
best in the "Music/Entertainment" domain.


**Concluding Remarks**

I'd like to thank my mentor for guiding me throughout the project and my co-mentees for the intelectually stimulating 
discussions on various topics. I really enjoyed the project and got to learn lots!\
Thank you guys!






