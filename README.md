
Assignment 1: Text classification using Generative and Discriminative models
A project on natural language processing condicting the following tasks:
    1. Implementing the naive bayes classifier for sentiment analysis of IMDB review
    2. Making a wordembeddingops class to perform vector algebra using word embeddings created using word2vec pre trained word embedding
    3. Implemented logistic regression to train the bag of words text classifier, word2vec classifier and conducted the same exercise of sentiment analysis

Assignment 2:Language Modelling and Next Token Prediction by implementing N-gram, FFNN and RNN

    Built an N-gram model and trained on a dataset having the name of cities as training corpora. 

Implemented n gram model to generate the next word in the sequence by taking previous n-1 tokens as context words to generate next possible words.

Implemented a feed forward neural network and RNN to process the sequence of tokens and output next possible words. Use of RNNs enhance the performance of the language models and capture the coherence between the generated words in a better manner.

Calculated perplexity to evaluate the accuracy of the generated next words.


Assignment 3:Transliteration of Indian Names Using RNN based Sequence to Sequence Models


As part of NLP project on low-resource language processing, I built a character-level sequence-to-sequence (Seq2Seq) model to transliterate Indian names from English script to Hindi. The project involved developing both a vanilla RNN-based encoder-decoder and an attention-enhanced version using PyTorch. Attention mechanisms such as Bahdanau-style soft attention were crucial in improving the model’s ability to handle variable-length input and align source-target character sequences accurately.

The attention-based model significantly outperformed the baseline in terms of accuracy and quality. The final evaluation showed a BLEU score improvement from 0.53 to 0.63, with accuracy increasing from 17.5% to 32%, and error rates dropping notably (CER: 28.9% → 20.1%, TER: 45.6% → 33.9%). This demonstrated how neural attention mechanisms can play a pivotal role in enhancing transliteration tasks where aligned parallel corpora are limited.
As part of a deep learning project on low-resource language processing, I built a character-level sequence-to-sequence (Seq2Seq) model to transliterate Indian names from English script to Hindi. The project involved developing both a vanilla RNN-based encoder-decoder and an attention-enhanced version using PyTorch. Attention mechanisms such as Bahdanau-style soft attention were crucial in improving the model’s ability to handle variable-length input and align source-target character sequences accurately. The attention-based model significantly outperformed the baseline in terms of accuracy and quality. The final evaluation showed a BLEU score improvement from 0.53 to 0.63, with accuracy increasing from 17.5% to 32%, and error rates dropping notably (CER: 28.9% → 20.1%, TER: 45.6% → 33.9%). This demonstrated how neural attention mechanisms can play a pivotal role in enhancing transliteration tasks where aligned parallel corpora are limited.



Assignment 4:Attention Head Pruning and Interpretability in T5 Transformers

I implemented a gradient-based attention head importance framework for the T5 transformer model to analyze and prune less critical attention heads across encoder, decoder, and cross-attention blocks. Using Michel et al.’s head masking technique, I computed head-wise gradient saliencies and selectively pruned attention heads while measuring the impact on downstream performance across tasks like summarization (CNN/DailyMail) and translation (WMT16).

The framework enabled structured sparsity with fine-grained control. Key findings included that up to 40% of encoder/decoder heads could be pruned with <15% BLEU score drop, showcasing the potential for significant model compression without major loss in task performance. Interestingly, cross-attention layers were most sensitive to pruning, with BLEU scores dropping sharply beyond 40% sparsity. These insights were visualized using per-layer head importance heatmaps and pruning-vs-performance plots.


