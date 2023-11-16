# Bollywood Movie Dataset (2023-1951)
This dataset contains comprehensive information on Bollywood movies sorted by popularity from 2023 to 1951. It includes essential details such as Movie ID, Name, Year, Genre, Overview, Director, and Cast. Unlike many existing datasets, this collection uniquely incorporates the 'Overview' column, offering succinct synopses for each movie, enhancing its utility for content-based recommendation systems and similarity matrix analysis.

## Dataset Details
<b>Number of Rows: 2200</b> <br>
Columns:
- Movie ID: Unique identifier for each movie
- Name: Title of the movie
- Year: Release year
- Genre: Categories or types of the movie
- Overview: Brief synopsis or plot summary
- Director: Name(s) of the director(s)
- Cast: Lead actors and actresses

## Scraping Methodology
The data was scraped from IMDb's website using Python libraries such as requests, BeautifulSoup, and Pandas. The Jupyter Notebook (Scraping-Bollywood-Movies-from-IMDB.ipynb) provides the step-by-step process of how the data was collected and organized.

## Usage
This dataset can be utilized for various purposes such as:
- Exploratory Data Analysis (EDA) of Indian movies released in the past few years.
- Analyzing trends in movie genres, directors, or cast members.
- Building recommendation systems or predictive models in the film industry.
## Notebook Usage
The Jupyter Notebook (Scraping-Bollywood-Movies-from-IMDB.ipynb) details the scraping process and demonstrates how the dataset was created. It includes code snippets using Python libraries to scrape and compile the dataset.

## Citation
If you use this dataset for your work or research, please consider citing this repository.
```bash
@misc{yourusername/movie-dataset-2023,
  author = {Deven Bhagtani},
  title = {IMDB Movie Dataset(2023-1951)},
  year = {2023},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/devensinghbhagtani/Bollywood-Movie-Dataset}},
}
```
