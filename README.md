# Book Data Analysis
## This project involves fetching and analyzing book data from two different APIs: Open Library and Google Books. The primary goal is to gather information about books, including details such as titles, authors, publishers, ratings, and more. The project is implemented in Python and utilizes various libraries for data manipulation and analysis.

## Table of Contents
1. Introduction
2. Code Overview
3. Getting Started
4. Prerequisites
5. Installation
6. Data Collection
7. Open Library API
8. Google Books API
9. Data Processing
10. Open Library Data
11. Google Books Data
12. Data Analysis
13. Results
14. License

### Introduction
##### This project focuses on fetching book data from Open Library and Google Books APIs, performing data processing and analysis, and deriving insights from the collected datasets.

### Code Overview
##### The code is organized into several sections, each serving a specific purpose:

##### Data Collection: Fetching book data from both Open Library and Google Books APIs.
##### Data Processing: Cleaning and preprocessing the obtained datasets for analysis.
##### Data Analysis: Exploring and analyzing the book data to gain insights.
##### Results: Displaying visualizations and summaries of the analysis results.

#### Getting Started
##### Prerequisites
- Ensure you have the following dependencies installed:
- pip install pandas,matplotlib,seaborn
- mkdir content -> dsci_project (code exists)
- Make sure to check if the folder exists as content/dsci_project
## Example for installing prerequisites
### Data Collection
#### Open Library API
- Considering the Open library API we have fetched all the books and took the isbn number for further preprocessing andanalysis 

#### Google Books API
- Describing the process with Google Books API, initiailly having a daily quota to request for the data. We used the ISBN from Open Library API's in google books search api to get the data and do the further analysis.

#### Data Processing
- Data created with OpenLibrary and Google Books API: Dropped Duplicate Data Rows, Cleaned Genre column, Dropped Null values and calculated average ratings based on rating count and actual ratings.

- Data created with Gutenberg API (GutenDex.org): Mapped language column with full languages, optimized authors column with author name, birth year and death year, dropped null values.

#### Data Analysis
- Provided with insights into the books dataset performed on different areas. This includes top publishers, with most books published, based on ratings, number of books published each year, and so on.

#### Results
- The visualizations and summaries of the results obtained from the data we collected can be used for recommendation system for a limited purposes, also the results we have obtained is based on limited data obtained from different API's and merged them together into one.

#### License
This project is licensed under the MIT License.

