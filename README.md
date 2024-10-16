---

# Movie Recommendation System

This project implements a simple movie recommendation system using Python and Pandas. It recommends movies based on the genres and ratings of a given movie title. You can input a movie title and the system will return 5 similar movies that match the genres and have a rating equal to or higher than a specified score.

## Features

- **Input**: A movie title and a minimum rating score.
- **Output**: A list of up to 5 recommended movies based on genre similarity and rating threshold.
- **Data**: Movie information such as title, genres, rating, and number of votes.
  
## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Function Details](#function-details)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/srishrachamalla7/Movie_Recommend.git
   ```
   
2. Navigate to the project directory:
   ```bash
   cd Movie_Recommend
   ```

3. Install required dependencies:
   ```bash
   pip install pandas scikit-learn
   ```

## Usage

1. Ensure your dataset is in the form of a Pandas DataFrame, with columns such as `title`, `genres`, and `averageRating`.

2. Use the `recommend ` function by passing in a movie title:

3. The function will return a DataFrame containing up to 5 similar movies that match the genres of the input title and have a rating greater than or equal to the specified minimum score.

## Function Details

### `recommend_movies(title)`

- **Arguments**:
  - `df` (DataFrame): The dataset containing movie information (e.g., `title`, `genres`, `averageRating`).
  - `title` (str): The movie title to base the recommendations on.
  
- **Returns**:
  - A DataFrame with up to 5 recommended movies that match the genre(s) of the input movie
