# CS3244 Group 17 - Project DeSpoiler

## Brief Project Summary
This project builds an end-to-end spoiler classification pipeline on IMDb movie reviews.
It starts from raw Kaggle data, performs preprocessing and feature generation, then trains and evaluates multiple binary classifiers.

Main stages:
1. Data loading and EDA
2. Preprocessing and split generation
3. Artifact generation (including `artifacts_1` and `artifacts_2`)
4. Model training, tuning, and evaluation

## Dataset
Download both required datasets/files from:
https://www.kaggle.com/datasets/rmisra/imdb-spoiler-dataset

Place these files in the same working directory you plan to use for notebook execution:
1. IMDB_reviews.json
2. IMDB_movie_details.json

## Minimum Recommended Resources
This is a computationally expensive project.

Recommended minimum:
1. 16 GB RAM
2. 256 GB free storage

## Run Flow

1. Clone the repository:
   https://github.com/lzrcode-816/3244-Group-17-IMDB-Spoiler-Detection.git

2. Move [Group17_ProjectDeSpoiler_Preprocessing.ipynb](Group17_ProjectDeSpoiler_Preprocessing.ipynb) out of the repo folder into your desired working directory (the same directory where both Kaggle dataset files are located).

3. Run all cells in [Group17_ProjectDeSpoiler_Preprocessing.ipynb](Group17_ProjectDeSpoiler_Preprocessing.ipynb), and review notebook outputs/results.

4. Move [Group17_ProjectDeSpoiler_Model.ipynb](Group17_ProjectDeSpoiler_Model.ipynb) out of the repo folder into that same desired working directory (where artifacts from Step 3 now exist, including artifacts_1 and artifacts_2).

5. Run all cells in [Group17_ProjectDeSpoiler_Model.ipynb](Group17_ProjectDeSpoiler_Model.ipynb), and review notebook outputs/results.

## Notes
1. Keep notebook files, dataset files, and generated artifacts in paths consistent with notebook expectations.
2. The preprocessing notebook must be run before the model notebook because model training depends on generated artifacts.
