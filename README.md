# News Article Classifier
> Code release of CMT316 Coursework

A Jupyter notebook showing classification of news articles using an SVM, feature selection, and various feature extraction techniques. 

## Installation

Requirements:

- Python 3.9
- Pipenv (Optional)
- git
- tar

### Clone the repo

```bash
$ git clone https://github.com/pbexe/news-classification.git
$ cd news-classification
```

### Unpack data
```bash
$ tar -xf src/bbc.tar.gz --directory src
```
### Install Python packages

Install using either Pipenv **OR** Pip

#### Pipenv
```bash
$ pipenv install
$ pipenv shell
$ python -m spacy download en_core_web_sm
```

#### Pip
```bash
$ pip install -r requirements.txt
$ python -m spacy download en_core_web_sm
```

## Running
```bash
$ jupyter notebook
```

Navigate to `src/news-classifier.ipynb` in the new browser window.

To re-run the cells, click `Cell/Run All`

## References
*D. Greene and P. Cunningham. "Practical Solutions to the Problem of Diagonal Dominance in Kernel Document Clustering", Proc. ICML 2006.*