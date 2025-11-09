<h1 align="center"> Deep Learning Model – Fake & Real News Detection</h1>
<p align="center"><em> TechNest Task 2 : Fake and Real news dataset </em></p>

---
 _Explore my more TechNest Tasks_ [Here](https://github.com/Kanakbaghel/TechNest-Internship)
   -----------


<img align="center" width="795" height="400" alt="image" src="https://github.com/user-attachments/assets/a44eee8f-11e5-40ff-984c-2fb05520e1fe" />

---
## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Installation & Usage](#installation--usage)
- [Project Structure](#project-structure)
- [Results & Insights](#results--insights)
- [Next Steps](#next-steps)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

***

## Dataset

**Source**: [`Fake and Real News Dataset – Kaggle`](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

*Download and place the CSV files (`Fake.csv` and `True.csv`) in your working directory before running the notebook.*

***

## Project Workflow

- **Data Loading & Preprocessing**
  - Merge real and fake news data
  - Clean text (removal of stopwords, punctuation, stemming/lemmatization)
  - Encode labels

- **EDA (Exploratory Data Analysis)**
  - Class distribution visualization
  - Word clouds and frequent terms analysis

- **Model Building**
  - Tokenization and padding sequences
  - Embedding Layer (Word2Vec/GloVe or custom)
  - LSTM/GRU/RNN/1D-CNN deep learning architectures

- **Training & Evaluation**
  - Train/val split
  - Metrics: Accuracy, Precision, Recall, F1-score

- **Visualizations**
  - Loss & accuracy curves
  - Confusion matrix

***

## Installation & Usage

**Requirements**

- Python 3.8+
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn, scikit-learn, tensorflow/keras, nltk

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow nltk
```

**Steps**

1. Clone the repository.
2. Download the dataset from Kaggle (see above).
3. Run the notebook: `jupyter_notebook.ipynb`.
4. Follow along for insights & visuals; tune model parameters as desired.

***

## Project Structure

```
├── Fake.csv                        # Fake news samples
├── True.csv                        # Real news samples
├── jupyter_notebook.ipynb          # Deep learning workflow
├── README.md                       # Project documentation
└── LICENSE                         # MIT license
```

***

## Results & Insights

- Achieved high accuracy in distinguishing fake vs. real news
- Clear EDA showcasing bias, feature importance, and class imbalance
- Detailed visualizations of training process
- Model ready for deployment or further enhancement

***

## Next Steps

- Experiment with transformer models (BERT, DistilBERT)
- Deploy with a web app (Streamlit, Flask)
- Fine-tune hyperparameters for performance boost
- Increase dataset diversity or multi-lingual support

***

## Contributing

Community feedback and contributions are encouraged!
- Fork the repo, open issues, or submit pull requests for improvements.

***

## Contact

For questions, open an issue or connect with [Kanakbaghel](https://github.com/Kanakbaghel).

---
> _“Data becomes meaningful when it tells a story that leads to better decisions.”_  
<p align="center"><em>Crafted with ♥ by <strong>Kanak Baghel</strong> |  <a href="https://www.linkedin.com/in/kanakbaghel">LinkedIn</a></em></p>
