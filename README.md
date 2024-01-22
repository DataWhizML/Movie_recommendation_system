# Movie Recommender System

## Overview

This project implements a Movie Recommender System using Streamlit, a web app framework for Python. Users can select a movie from a dropdown list, click the "Recommend" button, and get a list of recommended movies along with their posters.

## Files and Directory Structure

- `app.py`: Main application file containing the Streamlit code for the recommender system.
- `setup.sh`: Configuration script for Streamlit.
- `movie_dict.pkl`: Pickled file containing movie data.
- `similarity.pkl`: Pickled file containing similarity data for movie recommendations.

## Installation

To run the app locally, make sure you have Python and the required dependencies installed. You can install dependencies using:

```bash
pip install -r requirements.txt
```

## How to Run
Execute the following command to run the app:

```bash
sh setup.sh && streamlit run app.py
```
The app will be accessible in your browser at http://localhost:8501.

## Dependencies
- Streamlit
- Pandas
- Requests

## Data Source
- The movie data is sourced from The Movie Database (TMDb).
  



