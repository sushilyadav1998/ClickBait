# ClickBait
Clickbait Spoiler Type Classification and Spoiler Generation

This paper presents our approach to address the SemEval 2023 clickbait spoiling task, which comprises two distinct sub-tasks: spoiler classification and spoiler generation. For the classification task, involving the identification of different spoiler types, such as phrase, multi-sentence, and passage spoilers, we explore a diverse array of machine learning, deep learning, and transformer models. To assess the performance of our approach, we adopt the F1 score, a widely used metric for classification tasks.

Regarding the spoiler generation task, our primary objective is to generate spoilers from article texts using clickbait titles. To accomplish this, we leverage pretrained models, including BART, T5, and Pegasus, fine-tuned specifically for the spoiler generation task. It is noteworthy that these pretrained models were primarily trained for summarization tasks. The efficacy of our approach is evaluated using rogue and meteor evaluation metrics, commonly used to assess the quality of generated text.
