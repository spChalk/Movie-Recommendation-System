# Movie-Recommendation-System

## Description
**Movie Recommendation System** is a simple thus fully functional *Data Mining* project, that showcases the process from which all of the raw data pass through before they are being finally used and manipluated, in order to provide some handy information considering the suggestion of movies, based on some given preferences. The aforementioned preferences can be either some movie / TV show titles themselves or some descriptions that best describe a viewer's taste.

This project was developed in order to help in a study done on the movies of the well-known platform
[**Netflix**](https://en.wikipedia.org/wiki/Netflix).

## Project's Structure
The project is seperated into four (4) main parts:
1. Data Preprocessing ([missing data handling](https://en.wikipedia.org/wiki/Missing_data), [lemmatization](https://en.wikipedia.org/wiki/Lemmatisation)).
2. Studying the data and extracting statistical data, in order to completely comprehend the provided datasets.
3. Implementation of the recommendation system (used [Bow](https://en.wikipedia.org/wiki/Bag-of-words_model) and [TF-IDF](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) models combined with [Jaccard-Tanimoto coefficient](https://en.wikipedia.org/wiki/Jaccard_index) and [cosine similarity](https://en.wikipedia.org/wiki/Cosine_similarity)).
4. Running the program and displaying the final results.

## Data
The project's data consist of three (3) **.csv** files (`netflix_titles.csv`, `IMDb movies.csv`, `IMDb ratings.csv`) that can be found under `Movie-Recommendation-System/data/` directory in the project's repository and contain:
1. **Movie** and **TV Show** titles from Netflix.
2. Movie information from [**IMDb**](https://en.wikipedia.org/wiki/IMDb).
3. Movie ratings from **IMDb**.

## Collaborators
* [Maraziaris Harry](https://github.com/cmaraziaris)
* [Chalkias Spiros](https://github.com/spChalk)

## License
[MIT](https://choosealicense.com/licenses/mit/)
