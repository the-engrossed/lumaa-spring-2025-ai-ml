# Movie Recommentation System
---

## Overview

A **content-based recommendation system** that, given a **short text description** of a user’s preferences, suggests **similar items** (e.g., movies) from the dataset. The model processes the input description and compares it to keywords and genres of the dataset and then returns **Top 5  closest matches** to the user.

---

## Detailed Description

1. **Dataset**  
   -  link: https://www.kaggle.com/code/faryalzafarbhatti/movie-recommendation-system-python/input
   - 

2. **Approach**  
   - **Content-Based**: Using cosine similarity to measure the similarity between the input description and the dataset. The values are between 0 and 1, the output is the closest match to the user input.

3. **SETUP**  

Clone the repository

```bash
https://github.com/entbappy/Movie-Recommender-System-Using-Machine-Learning.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n movie python=3.10 -y
```

```bash
conda activate movie
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
#run this file to generate the models

Movie Recommender System Data Analysis.ipynb
```


5. **Results**  
   - You'll be seeing either top 3 or top 5 suggestions for the given input description and the cosine similarity values.

---

## Salary Expectations

1. **$2500-$3500 per month**  



