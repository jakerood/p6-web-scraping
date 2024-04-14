# Project 6: Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

**Name: Jake Rood**

**Date: 04-14-2024**

This repository is used to practice web scraping and processing content from a web page.

## Step 1: Getting Started

1. Copy the base repository into your GitHub account

2. Clone your new repository down to your machine

## Step 2: Set Up Virtual Environment

Create and activate a virtual environment specifically for this project. We will also install packages required for this project.

### Create a Virtual Environment

1. Open the terminal in VS Code.
2. Run the following command to create a virtual environment for this project.

```shell
python -m venv .venv
```

### Activate the Virtual Environment

Once the virtual environment has been created, activate the virtual environment by running the following command:

```shell
source .venv/bin/activate
```

### Install Dependencies to the Active Virtual Environment

The following dependencies are required to complete the exercises in this project:

* beautifulsoup4
* html5lib
* ipykernel
* jupyterlab
* matplotlib
* requests
* spacy
* spacytextblob

Use the following command to install dependencies into the active virtual environment:

```shell
python -m pip install [dependency]
```

### Create a Python Kernel

In the active virtual environment, create a Python kernel to run our notebook.

```shell
python -m ipykernel install --user --name .venv --display-name "Python (.venv)"
```

## Step 3: Open Notebook and Complete Tasks

### Open Jupyter Notebook

On your machine, open the Jupyter Notebook for editing.

### Markdown Introduction

In the Markdown introduction, add a viewable, clickable link to your GitHub repository after your name.


### Import the Necessary Packages into the Notebook

```shell
from collections import Counter
import pickle
import requests
import spacy
from bs4 import BeautifulSoup
import matplotlib.pyplot as plt

!pip list

print('All prereqs installed.')
```

### Markdown Headings

Use Markdown headings to clearly show your content by each question number.

### Complete Tasks

Complete the following tasks:

* (Question 1) Article html stored in separate file that is committed and pushed
* (Question 2) Article text is read in and printed
* (Question 3) Use a spaCy pipeline to determine and print the 5 most common tokens (converted to lowercase) along with their frequencies
* (Question 4) Use a spaCy pipeline to determine and print the 5 most common lemmas (converted to lowercase) along with their frequencies
* (Question 5) Define methods that score sentences by token and lemma. The score should take the number of times any interesting words appear in a sentence divided by the number of words in the sentence
* (Question 6) Plot a histogram showing sentence scores (using tokens) for every sentence in the article. What seems to be the most common range of scores?
* (Question 7) Plot a histogram showing sentence scores (using lemmas) for every sentence in the article. What seems to be the most common range of scores?
* (Question 8) Provide a thoughtful answer to the following question: Which tokens and lemmas would be omitted from the lists generated in questions 3 and 4 if we only wanted to consider nouns as interesting words? How might we change the code to only consider nouns?

### Commit and Push Changes to GitHub

After completing EACH task, execute the notebook. Commit and push your changes to GitHub with an appropriate commit message.

## Step 4: Export to HTML

1. After you have completed each task and executed the notebook, export the notebook to a HTML file.
2. Commit and push your HTML file to your GitHub repository.

## Step 5: Finalize Repository

Verify you have a professional README.md that properly introduces your GitHub repository and provides useful information about the project.
