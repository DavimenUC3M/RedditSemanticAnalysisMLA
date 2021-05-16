FinalProject
==============================

Repository for the final project of the Machine Learning Applications course.

### Authors:

- Enrique Botía Barbera
- Andres Ruíz Calvo
- David Méndez Encina
- Simón E. Sánchez Viloria 

### Usage:

This project contains the following notebooks that explain our exploratory and scientific analysis in each task of the project:

1. `reddit_data_extraction.ipynb`: Notebook used to extract and export the dataset used in this project. We relied on Reddit's python API `praw` to build this dataset.

    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/simonsanvil/FinalProjectMLA/blob/master/notebooks/reddit_data_extraction.ipynb)
 
 2. `reddit_topic_modeling_and_graph.ipynb`: Notebook used to process the textual information obtained from the dataset acquired , vectorize it and do topic modeling with it.

    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/simonsanvil/FinalProjectMLA/blob/master/notebooks/reddit_topic_modeling_and_graph.ipynb)
    
 3. `subreddit_classification.ipynb`: Notebook used to train, evaluate, and compare models used to predict the subreddit of a post given only its semantic representation. Performance with both LDA and TFIDF representations are compared among each other.

    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/simonsanvil/FinalProjectMLA/blob/master/notebooks/subreddit_classification.ipynb)
 


Project Organization
------------

    ├── LICENSE
    │
    ├── README.md          <- The top-level README for developers using this project.
    │
    ├── data
    │    
    ├── models             <- Trained and serialized models, model predictions, and/or model summaries
    │
    ├── notebooks          <- Jupyter notebooks containing the analysis made for this project. 
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    │
    └── src                <- Source code for use in this project.
        └── __init__.py    <- Makes src a Python module
       


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
