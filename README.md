# IMDB-dataset

****
## Requirements

- Python 3.x
- Jupyter Notebook
- Python Libraries : Numpy,Pandas,sklearn,nltk,gensim

**** 
## Installation 

1. Clone the repository

```bash
git clone https://github.com/Rishi-Jain2602/IMDB-dataset.git
```

2. Install the Project dependencies
```bash
pip install -r requirements.txt
```

3. Download Dataset

[IMDB Dataset of 50k movies](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

***


## Model Training

### Data Cleaning

 - Null and duplicate data were removed
 - HTML text , stopwords where removed from dataset.

### Text Vectorization

- Back of Words(BOW)
- Word2Vec

For both cases model was trained and were getting different results

### Modelling
Type of Machine Leaning Algorithm used - 
  - Gaussian Naive Bayes classifier
  - Random Foest Classifier
  - TdIdf (Term Frequency-Inverse Document Frequency)

Both algorithm were used and different results were there.

### Evaluation

Using different Text Vectorizer and different ML algorithms.

I found that Back of words with TdIdf algoithm was giving better result

![Capture](https://github.com/Rishi-Jain2602/IMDB-dataset/assets/118871883/57664986-d80a-4627-8d7f-0eb95cf7c46f)


***

## Note

1. Make sure you have Python 3.x installed
2. It is recommended to use a virtual environment to avoid conflict with other projects.
3. If you encounter any issue during installation or usage please contact rishijainai262003@gmail.com or rj1016743@gmail.com

