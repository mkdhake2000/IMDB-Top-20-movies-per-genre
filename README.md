# IMDB-Top-20-movies-per-genre
Script to extract the top 20 movies data from imdb per genre

## Task:

The task involves developing a website data extracting script to extract information about the top 20 movies listed under each genre on IMDb, as well as their latest 10 user reviews. The goal is to gather comprehensive data for a broad analysis of movie trends and reception across various genres.

## Working:

The selenium based script uses browser automation to emulate clicks and scrolls and uses the elements to extract the data from the IMDB website. FIREFOX browser is used for automation and the required web driver tool is attached in the directory. The script is tested and running on FIREFOX V121.0. The code creates two drivers, one extracting the movie data and other extracting the user reviews data. The data of each genre top 20 movies is stored under the 'genre_name.csv' file in the 'genre_dump_csv/' directory where genre_name is the name of the genre and the user reviews per movie is stored in the 'movie_reviews.csv' file. The structure/schema of the dataframes exported into csv is explained by the 'imdb_genre_dataframes.drawio' file.

## Environment Setup:

<details><summary><b>Requirements:</b></summary>

  - MOZILLA FIREFOX BROWSER
  - GECKODRIVER
  - SELENIUM
  - PANDAS
  - JUPYTER NOTEBOOK
  
</details>

<details><summary><b>Conda Environment:</b></summary>

```shell
# Creating a conda environment from the given environment.yml file
conda env create -f environment.yml

# Activating the environment
conda activate webscrape
```

</details>

## Running the CODE:

The webscraping can be done by running the script imdbfinalscript.py or running the jupyter notebook imdbfinal.ipynb with intermediate results
```shell
# Running the python script
python imdbfinalscript.py
```
Running the imdbfinal.ipynb:
Select the conda environment as the python environment to run the notebook

## Result and Export:

The resulting csv files will be stored in the 'genre_dump_csv/' directory in the main directory.
