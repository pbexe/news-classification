# News Article Classifier
> Code release of CMT316 Coursework

## Installation

Requirements:

- Python 3.9
- Pipenv (Optional)
- Git

### Clone the repo

```bash
$ git clone https://github.com/pbexe/news-classification.git
$ cd news-classification
```

### Pipenv
```bash
$ pipenv install
$ pipenv shell
$ python -m spacy download en_core_web_sm
```

### Pip
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