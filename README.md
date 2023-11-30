# NLP_onlab
A Transformers Model Fine-Tuning Algorithm for Market Topic Text Generation
This repository contains the implementation of a transformer model fine-tuning algorithm tailored for generating market-related text. The algorithm initially utilizes the Hungarian NYTK/PULI-GPT-2 model and employs the accelerate package, transformers, and pytorch libraries. This repository is connected to Google Colab and should be tested there!

Algorithm Overview
The algorithm follows a three-step process:

Fine-tuning: The algorithm is fine-tuned on a training dataset called Articles_3.txt, which comprises real news articles and AI-generated text related to market topics.

Text Generation: After fine-tuning, the algorithm can generate new text using a hybrid approach combining the top_k and top_p methods.

Sensitive Data Detection and Masking: The generated text is passed through a sensitive data detection module that identifies and replaces sensitive information with asterisks.

Dependencies
The algorithm requires the following dependencies:

accelerate
transformers
pytorch

Creator and Purpose
This algorithm was developed by Szladek Máté from the Budapesti Műszaki és Gazdaságtudományi Egyetem (Budapest University of Technology and Economics) as a university task. The purpose of the program is to explore the potential of transformer models for generating market-related text.
