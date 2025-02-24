# Movie Recommendation System

This project implements a movie recommendation system using TF-IDF and cosine similarity. It recommends movies based on a user's input query by comparing it with movie overviews from the IMDb dataset.

## Dataset

The dataset used is **IMDb Movies**, which contains movie titles, overviews, and other metadata. The dataset is loaded from a CSV file (`IMDb_Movies.csv`).

### Steps to Load the Dataset:
1. The dataset file (`IMDb_Movies.csv`) is in the project directory.
2. The dataset is loaded using `pandas`:
   ```python
   import pandas as pd
   df = pd.read_csv('IMDb_Movies.csv')
   df = df[df['overview'].notna()].reset_index(drop=True)
## Setup
Python 3.8 or higher is required.

## Install Dependencies
Install the required dependencies using the below command `'pip install -r requirements.txt'` in terminal

## Running the code
1. Open the notebook in Jupyter using command  `jupyter notebook`
2. Start the kernel
3. Run the cells to load the dataset, compute recommendations, and display results.

## Example Results
For the user preference **"I like action movies"**, the output would be:

| Index | Title               | Similarity Score |
|-------|---------------------|------------------|
| 394   | Last Action Hero    | 1.000000         |
| 471   | Nine                | 0.698250         |
| 265   | The Island          | 0.570009         |
| 24    | King Kong           | 0.543391         |
| 203   | The Bourne Legacy   | 0.521596         |


## Demo Link
[https://drive.google.com/file/d/1PLeMhnfdy_iWIqI-J6QkR7pHAY9moJgG/view?usp=drive_link
](https://drive.google.com/file/d/1PLeMhnfdy_iWIqI-J6QkR7pHAY9moJgG/view?usp=sharing)

## Salary Expectations
$5000-$6000 per month - working full-time 40 hours a week

