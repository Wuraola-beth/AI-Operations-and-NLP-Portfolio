# AI Operations and NLP Portfolio

Welcome to my AI Operations and Natural Language Processing (NLP) portfolio. This repository documents my practical learning journey through NLP tasks, text preprocessing, transformer models, sentiment analysis, text summarisation, machine translation, and text-to-speech.

The projects and assignments in this repository were completed as part of my learning journey, including exercises from the Data Science Nigeria (DSN) NLP programme. They demonstrate my exploration of NLP tools, model architectures, and evaluation techniques.

## Skills and Tools

* **Programming:** Python
* **Data Processing:** pandas, text cleaning, tokenisation, padding, and preprocessing
* **NLP Libraries:** spaCy, Hugging Face Transformers, NLTK
* **Deep Learning:** TensorFlow/Keras, LSTM, CNN, and transformer-based models
* **NLP Tasks:** Named-entity recognition, sentiment classification, summarisation, machine translation, and text-to-speech
* **Model Evaluation:** Accuracy, F1-score, confusion matrix, and ROUGE

## Projects and Assignments

### 1. Named-Entity Recognition with spaCy

**Notebook:** [`spaCy_Named_Entity_Recognition.ipynb`](spaCy_Named_Entity_Recognition.ipynb)

This exercise explores named-entity recognition using spaCy's `en_core_web_sm` English language model. It processes sample Twitter text, extracts named entities, and organises the extracted information in a pandas DataFrame.

**Key concepts:** Pre-trained NLP pipelines, entity extraction, and structured text output.

### 2. Exploring English-to-Multilingual Translation

**Notebook:** [`Exploring_Multilingual_Machine_Translation.ipynb`](Exploring_Multilingual_Machine_Translation.ipynb)

This exercise loads the Hugging Face `Helsinki-NLP/opus-mt-en-mul` tokenizer and sequence-to-sequence model for multilingual translation. It also explores an English-to-Yoruba translation example.

**Note:** The displayed translation example is hard-coded rather than generated through a completed fine-tuning process. This exercise demonstrates model-loading and translation concepts, not a verified fine-tuned translation system.

**Key concepts:** Pre-trained translation models, tokenisation, and multilingual NLP.

### 3. Sentiment Classification with DistilBERT

**Notebook:** [`DistilBERT_Sentiment_Classification.ipynb`](DistilBERT_Sentiment_Classification.ipynb)

This assignment explores binary sentiment classification using DistilBERT. It includes text tokenisation, model fine-tuning with the Hugging Face Trainer API, and evaluation using accuracy and F1-score.

**Recorded results:** 48% accuracy and an F1-score of 0.4270 in the saved notebook output.

These results reflect the recorded evaluation and should not be interpreted as evidence of strong generalisation without further testing.

**Key concepts:** Transformer fine-tuning, binary sentiment classification, and model evaluation.

### 4. Sentiment Classification with BERT

**Notebook:** [`BERT_Sentiment_Classification.ipynb`](BERT_Sentiment_Classification.ipynb)

This assignment uses `bert-base-uncased` for binary sentiment classification. It covers tokenisation, model training with the Hugging Face Trainer API, and evaluation using accuracy, weighted F1-score, and a confusion matrix.

**Recorded results:** 66% accuracy and a weighted F1-score of 0.6610.

The saved confusion matrix records 20 true positives, 13 true negatives, 8 false positives, and 9 false negatives.

**Key concepts:** BERT, transformer-based text classification, and classification metrics.

### 5. Sentiment Classification with GPT-2

**Notebook:** [`GPT2_Sentiment_Classification.ipynb`](GPT2_Sentiment_Classification.ipynb)

This assignment explores GPT-2 for binary sentiment classification using the Hugging Face Transformers framework. It configures the padding token using the end-of-sequence token and evaluates the classifier.

**Recorded results:** 64% accuracy and an F1-score of 0.6195.

**Key concepts:** Causal language models, sequence classification, and evaluation metrics.

### 6. Text Summarisation Preprocessing with T5

**Notebook:** [`T5_Text_Summarisation_Preprocessing.ipynb`](T5_Text_Summarisation_Preprocessing.ipynb)

This exercise prepares a small article-and-summary dataset for a text summarisation task using the `t5-small` tokenizer. It covers preparing input text and target summaries for a sequence-to-sequence model.

**Scope:** The notebook focuses on preprocessing and preparing the data. It does not complete model training or provide a trained-model evaluation.

**Key concepts:** Text summarisation, sequence-to-sequence learning, and target preparation.

### 7. Exploring Multilingual Translation with mT5

**Notebook:** [`mT5_Multilingual_Translation_Exploration.ipynb`](mT5_Multilingual_Translation_Exploration.ipynb)

This exercise loads `google/mt5-small` and explores English-to-Yoruba translation examples. It also includes ROUGE-based comparisons of example outputs.

**Note:** The baseline and fine-tuned translation examples are hard-coded. The notebook does not demonstrate a completed fine-tuning run, so the comparisons should be treated as illustrative rather than verified model results.

**Key concepts:** Multilingual language models, translation evaluation, and ROUGE metrics.

### 8. Text-to-Speech with Google Text-to-Speech

**Notebook:** [`Google_Text_to_Speech.ipynb`](Google_Text_to_Speech.ipynb)

This exercise uses Google Text-to-Speech (gTTS) to convert a sample English passage into spoken audio and produce an MP3 file for playback.

**Key concepts:** Text-to-speech, speech generation, and audio output.

### 9. Three-Class Sentiment Classification with an LSTM

**Notebook:** [`LSTM_Three_Class_Sentiment_Classification.ipynb`](LSTM_Three_Class_Sentiment_Classification.ipynb)

Despite its original filename, this notebook implements a sentiment classification workflow using a Keras LSTM neural network rather than fine-tuning BERT. The workflow includes text cleaning, stopword removal, tokenisation, padding, and classification into three sentiment classes.

**Key concepts:** Text preprocessing, embeddings, recurrent neural networks, and multi-class sentiment classification.

### 10. Three-Class Sentiment Classification with a CNN

**Notebook:** [`CNN_Three_Class_Sentiment_Classification.ipynb`](CNN_Three_Class_Sentiment_Classification.ipynb)

Despite its original filename, this notebook implements a Keras CNN-based sentiment classifier rather than a GPT-2 causal decoder. The model architecture includes an embedding layer, a one-dimensional convolutional layer, global max pooling, and a softmax classification layer.

The saved model output should be checked by rerunning the notebook before reporting performance figures.

**Key concepts:** CNNs for text classification, embeddings, feature extraction, and multi-class sentiment classification.

## Learning Outcomes

Through these exercises, I have gained practical exposure to:

* Processing and preparing text for NLP tasks.
* Using pre-trained language models and tokenisers.
* Exploring transformer-based sentiment classification.
* Building neural-network text classifiers with LSTM and CNN architectures.
* Preparing data for sequence-to-sequence summarisation and translation tasks.
* Exploring named-entity recognition and text-to-speech tools.
* Evaluating classification outputs with accuracy, F1-score, and confusion matrices.
* Exploring ROUGE as a text-generation evaluation metric.

## Next Steps

My ongoing learning goals include:

* Strengthening my Python and NLP fundamentals.
* Improving model evaluation and error analysis.
* Comparing models against appropriate baselines.
* Practising fine-tuning and inference with reproducible experiments.
* Building more complete NLP applications and documenting their limitations clearly.

## About Me

I am an aspiring NLP practitioner developing my skills through practical projects and continuous learning. I am particularly interested in applying NLP to language technology, including low-resource languages such as Yorùbá.

This portfolio is a record of my learning process, experiments, and progress toward building more robust and useful NLP systems.
