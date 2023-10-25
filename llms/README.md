# Study 1: Generative AI with Large Language Models
## 1. Week One: Generative AI use cases, project lifecycle, and model pre-training
* Learning Objectives
    * Discuss model pre-training and the value of continued pre-training vs fine-tuning
    * Define the terms Generative AI, large language models, prompt, and describe the transformer architecture that powers LLMs
    * Describe the steps in a typical LLM-based, generative AI model lifecycle and discuss the constraining factors that drive decisions at each step of model lifecycle
    * Discuss computational challenges during model pre-training and determine how to efficiently reduce memory footprint
    * Define the term scaling law and describe the laws that have been discovered for LLMs related to training dataset size, compute budget, inference requirements, and other factors.
### 1.1. Introduction to LLMs and the generative AI project lifecycle
#### 1.1.1. LLM use cases & tasks
* Essay Writer
* Summarize
* Translate (Sentence to sentence)
* Code generator
* Entity Extraction (NER)
* Information retrieval (with API queries)
#### 1.1.2. Text Generation before Transformers
* Before transformers (RNN, LSTM, GRU etc.), it was hard to solve such ambiguities:
    * ``Syntactic ambiguity``: "The teacher taught the students with the book."
        * Did the teacher teach using the book,
        * or did the student have the book, or was it both?
* Transformers
    * Scale efficiently
    * Parallel process
    * Attention to input meaning
