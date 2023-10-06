# Barbie Movie Analysis

This project involves analyzing the performance of the Barbie movie from two main perspectives: box office success and sentiment analysis of user reviews. aiming to understand the movie's financial success in various countries and gauge audience sentiment based on their reviews.

## Part 1: Box Office Analysis

### Data Collection

The data was collected from [Box Office Mojo](https://www.boxofficemojo.com/releasegroup/gr629756421/) using web scraping techniques. The data includes information about the movie's performance in different countries, including opening night revenue and total earnings.

#### Libraries Used

- pandas
- requests
- BeautifulSoup
- numpy
- matplotlib

### Data Extraction and Cleaning

I extracted relevant data from the webpage, including the country name, opening income (in millions), and total earnings (in millions). data cleaning was done by removing unnecessary characters, standardizing country names, and converting numeric columns to float data types.

### Data Visualization

I visualized the opening income for the highest opening countries in the **international** market using a bar chart. The chart provides insights into how the movie performed in different countries on its opening night.

### Data Export

The cleaned and transformed data has been saved to a CSV file for further analysis and reporting. You can find the data in the CSV file.

## Part 2: Sentiment Analysis of User Reviews

### Data Collection

The user reviews data for the Barbie movie was collected from [IMDb](https://www.imdb.com/title/tt1517268/reviews?ref_=tt_urv). The reviews were analyzed to determine their sentiment: _positive, negative, or neutral_ using **TextBlob**.

#### Libraries Used

- pandas
- requests
- BeautifulSoup
- selenium
- TextBlob
- matplotlib

### Data Extraction and Cleaning

I used web scraping techniques such as selenium's automated web drivers to gather user reviews from _IMDb_. Data cleaning involved removing duplicates and reviews with missing data.

### Sentiment Analysis

I performed sentiment analysis on the user reviews using TextBlob. Reviews were categorized as positive, negative, or neutral based on their sentiment polarity scores.

### Data Visualization

visualized the distribution of sentiment categories in the reviews using bar charts and pie charts.
Make sure to learn more about the insights by checking the visualization on [**Tableau**](https://public.tableau.com/app/profile/ahmed.sakka/viz/BarbieMovieAnalysis/Dashboard1)

## Usage

To run the data collection and analysis code for both parts of the project, follow these steps:

1. Install the required libraries mentioned in the respective "Libraries Used" sections.
2. Run the Python scripts provided in this repository.

## Contributing

Contributions to this project are welcome. If you have ideas for improvements, additional analysis, or enhancements to either the box office or sentiment analysis parts, please open an issue or submit a pull request.

## Author

- [Ahmed AlSakka](ahmedsakka101@gmail.com)

## References

- [Box Office Mojo](https://www.boxofficemojo.com/releasegroup/gr629756421/)
- [IMDb](https://www.imdb.com/title/tt1517268/reviews?ref_=tt_urv)
