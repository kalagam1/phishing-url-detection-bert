# Phishing URL Detection using BERT Transformers

## 📌 Project Overview
An end-to-end Machine Learning pipeline designed to identify and classify malicious phishing URLs. By fine-tuning the BERT (Bidirectional Encoder Representations from Transformers) model, this project achieves high-precision detection, outperforming traditional heuristic-based methods.

## 🚀 Key Features
* **Transformer-Based Architecture:** Fine-tuned `bert-base-uncased` for sequence classification.
* **Data Pipeline:** Automated preprocessing, tokenization, and sanitization of a 5,000+ URL dataset.
* **Performance:** Achieved **92.2% accuracy** with a specific focus on high recall to minimize false negatives in security threats.
* **Comparative Analysis:** Benchmarked against RoBERTa to validate model selection.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** PyTorch, Hugging Face Transformers, Scikit-learn, Pandas
* **Tools:** Jupyter Notebook, Matplotlib (for confusion matrices)

## 📊 Results
The model demonstrated superior ability in recognizing complex URL patterns that traditional filters miss, making it a viable tool for real-time browser security extensions.
