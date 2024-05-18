# Super GLUE LLM Benchmark Classification

We selected the SuperGLUE LLM benchmark dataset, focusing on the BoolQ dataset, which involves yes/no questions and corresponding passages. Here's a concise summary of our project:

## Project Summary

1. **Initial Exploration and Random Classifier**
   - Conducted exploratory data analysis.
   - Implemented a random classifier achieving ~50% accuracy.

2. **Rules-Based Classifier**
   - Developed a classifier based on negation terms (e.g., "NOT").
   - Attempted passage completeness matching (word overlap between question and passage).
   - Achieved better accuracy but still below optimal.

3. **Subset Rule Logic**
   - Focused on specific question types (comparisons like "is this the same as that").
   - Achieved greater than 50% accuracy.

4. **BERT Classifier**
   - Implemented a BERT model with 32 labels.
   - Outperformed rules-based classifiers.

5. **Advanced Techniques**
   - Employed zero-shot learning, data augmentation, and LLM data (GPT-3 and GPT-4).
   - Data augmentation improved performance slightly.
   - GPT-4 trained model performed better than GPT-3.

6. **RNN and Data Masking**
   - Implemented RNN, achieving close to 70% accuracy.
   - Incremental data training with BERT showed performance improvements but plateaued.

7. **Model Distillation**
   - Increased training speed with slight accuracy trade-off (62.25%).
   - Considered attention-based distillation for future refinement.

## Summary

We explored the SuperGLUE benchmark and BoolQ dataset, implemented various training techniques, and leveraged LLMs for data augmentation. Despite challenges, we achieved significant insights and performance improvements. Future work will focus on deeper question-level analysis for better accuracy.

