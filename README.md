Semantic and Predictive Analysis of Reddit Posts
==============================

Repository with the source code used on our final project of the Machine Learning Applications course where we implemented an extensive exploratory, semantic, and predictive analysis with Python of a textual dataset compiled of several thousand reddit posts from a ser of multiple selected subreddits. 

Universidad Carlos III de Madrid. May, 2021

### Authors:

- Simón E. Sánchez Viloria 
- Enrique Botía Barbera
- Andres Ruíz Calvo
- David Méndez Encinas

### Usage:

This project contains the following notebooks that explain the exploratory and scientific analysis made on this project:

1. `reddit_data_acquisition.ipynb`: Notebook used to scrap and export several thousand posts from Reddit in order to build the dataset used in this project. We relied on Python's Reddit API Wrapper `PRAW` to build the dataset.

    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/simonsanvil/FinalProjectMLA/blob/master/notebooks/reddit_data_acquisition.ipynb)
 
 2. `task_1_reddit_topic_modeling_and_graph.ipynb`: Where we used exploratory and NLP techniques to to process the textual information obtained from the dataset acquired, vectorize it and do topic modeling with it.

    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/simonsanvil/FinalProjectMLA/blob/master/notebooks/task_1_reddit_topic_modeling_and_graph.ipynb)
    
 3. `task_2_subreddit_classification.ipynb`: Notebook used to train, evaluate, and compare the models used to predict the subreddit where a post comes from given only its semantic representation. Performance with both LDA and TFIDF representations are compared among each other.

    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/simonsanvil/FinalProjectMLA/blob/master/notebooks/task_2_subreddit_classification.ipynb)
 


Project Organization
------------

    ├── LICENSE
    │
    ├── README.md          <- The top-level README for developers using this project.
    │
    ├── notebooks          <- Jupyter notebooks that can be used to reproduce the analysis made in this project. 
    │
    ├── references         <- Project statement and explanatory materials.
    │
    ├── reports            <- Contains a report summarizing and documenting our analysis and conclusions.
    │   └── figures        <- Generated graphics and figures used in the analysis.
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment.
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    │
    └── src                <- Source code for use in this project.
        └── __init__.py    <- Makes src a Python module
       


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
