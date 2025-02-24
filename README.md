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
   - **Content-Based**: At a minimum, use text similarity to recommend items.  
     - For instance, you can transform both the user’s text input and each item’s description into TF-IDF vectors and compute **cosine similarity**.  
   - **Approach 2** Using SBERT.

3. **SETUP**  
   - You may use a **Jupyter Notebook** or **Python scripts**.  
   - Keep it **readable** and **modular** (e.g., one section for loading data, one for building vectors, one for computing similarity, etc.).  
   - Briefly comment or docstring your key functions/sections.

4. **Running**  
   - When given an input description (e.g., `"I like action movies set in space"`), your system should print or return a list of recommended items (e.g., 3–5 titles).  
   - Include the similarity score or rank if you’d like.

5. **Results**  
   - A short `README.md` that includes:
     - **Dataset**: Where it’s from, any steps to load it.  
     - **Setup**: Python version, virtual environment instructions, and how to install dependencies (`pip install -r requirements.txt`).  
     - **Running**: How to run your code (e.g., `python recommend.py "Some user description"` or open your notebook in Jupyter).  
     - **Results**: A brief example of your system’s output for a sample query.

---

## Salary Expectations

1. **$2500-$3500 per month**  


3. **Short Video Demo**  
   - In a `.md` file (e.g., `demo.md`) within your fork, paste a link to a **brief screen recording** (video link).  
   - Demonstrate:
     - How you run the recommendation code.  
     - A sample query and the results.

