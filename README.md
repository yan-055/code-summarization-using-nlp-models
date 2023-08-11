# Code Summarization Using NLP Models
In this project, we study the generalizability and robustness of pre-trained models such as CodeT5 and
CodeBERT with C++ to check their generalizability and robustness for code summarization task. We collect C++ source
codes with ground truth for the Code Summarization task using CodeBERT and CodeT5 models. We collect our data
from popular online websites including Github and geeksforgeeks to test our hypothesis. We seek to find if both pretrained CodeT5 and CodeBERT are well-generalized models to summarize the given C++ source codes. Additionally, we
fine-tune both models with C++ codes for Code Summarization as a model robustness check. Our results show that
both CodeBERT and CodeT5 attain improved performance in C++ function summarization after fine-tuning. Generally, the
CodeBERT model has better performance in summarizing C++ contexts.
