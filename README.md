# Named Entity Recognition (NER) with spaCy  
*A hands-on tutorial on customizing and extending NER pipelines*


## Overview

This tutorial introduces how to **customize Named Entity Recognition (NER)** in [spaCy](https://spacy.io/).  
You’ll learn to identify, label, and extend entities in text using **rule-based customization** methods such as the **Matcher** and **EntityRuler**, and you’ll briefly explore how to train your own small NER model.

The main focus is on **understanding and customizing existing pipelines** rather than deep model training.



## Workshop Information

> This tutorial was developed for the  
> **AI for Research Workshop Series — Research Computing and Data Services**  
> **Northwestern University**  
> Held on **November 12, 2025**, led by [Miriam Schirmer](https://www.comm.northwestern.edu/faculty/miriam-schirmer).

<br>

## ⚙️ Getting Started

You can run this tutorial in two ways:

### Option 1: Google Colab (recommended)

Simply open the provided `.ipynb` notebook in Google Colab and run all cells sequentially.  
All required libraries are pre-installed in the Colab environment.


### Option 2: Run Locally

If you prefer to work locally, make sure to:

1. Install the required libraries in your Python environment:  
   `spaCy` and the small English model `en_core_web_sm`.

2. Clone this repository for easy access or download the required files manually.

<br>

## 🗂️ Data

As a real-world use case, we analyze onlinen posts from an **Incel (Involuntary Celibates)** dataset (see corresponding [paper](https://www.frontiersin.org/journals/social-psychology/articles/10.3389/frsps.2024.1383152/full)) that you can find in this file: `incel_comments.csv`.  
This dataset helps demonstrate how spaCy can be adapted to detect *nonstandard language*, i.e., emerging online language and community specific slang.   
Content warning: Incel terminology often contains misogynistic expressions and may reference sexual or gender-based violence.

