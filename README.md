😃 GoEmotions Multi-Label Emotion Classification

Advanced NLP project for fine-grained multi-emotion detection using DistilBERT

📖 Overview

This project implements a multi-label emotion classification system capable of detecting 27 nuanced emotions + neutral in text. Unlike traditional sentiment analysis, this model allows multiple emotions simultaneously, providing a deeper understanding of emotional tone.

Example:
Input: "I'm so excited about this project but also a bit nervous!"
Output:
excitement (0.89)
nervousness (0.76)
optimism (0.62)

✨ Key Features
🎯 Multi-label Emotion Classification (28 labels)
⚡ Powered by DistilBERT (fast & lightweight)
🌈 Fine-grained Emotion Categories from the GoEmotions dataset
🔍 Word Importance Attribution through token masking
📊 Interactive Streamlit Dashboard
📄 PDF report generation
📦 Batch processing via CSV uploads

| Metric               | Score  |
| -------------------- | ------ |
| **Micro F1**         | 0.5508 |
| **Macro F1**         | 0.4104 |
| **Subset Accuracy**  | 0.4314 |
| **Hamming Accuracy** | 0.9692 |
| **Jaccard Score**    | 0.4741 |
