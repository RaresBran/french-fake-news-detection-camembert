# French Fake News Detection using CamemBERT

This project uses the **CamemBERT** language model to detect fake news in French. It fine-tunes a transformer-based model on labeled news data and evaluates its performance in identifying misinformation.

## Features

- Binary classification: Real vs. Fake news
- Pretrained CamemBERT transformer model
- Fine-tuning using Hugging Face Transformers
- Performance evaluation with confusion matrix and metrics

## Technologies Used

- Python
- Hugging Face Transformers
- CamemBERT
- Pandas, NumPy, Scikit-learn
- Jupyter Notebook

## Project Structure

```
french-fake-news-detection-camembert/
└── french-fake-news-detection-camembert-main/
    ├── french-fake-news.ipynb   # Main implementation notebook
    ├── train-ffn.csv            # Training dataset
    ├── test-ffn.csv             # Test dataset
    └── README.md                # Project documentation (this file)
```

## How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/french-fake-news-detection-camembert.git
   cd french-fake-news-detection-camembert/french-fake-news-detection-camembert-main
   ```

2. **Set up the environment**
   Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the Jupyter Notebook**
   ```bash
   jupyter notebook french-fake-news.ipynb
   ```

## Dataset

- Includes `train-ffn.csv` and `test-ffn.csv` with French news samples.
- Columns include: `text`, `label` (1 for fake, 0 for real).
