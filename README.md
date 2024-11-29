# IMDB Web Scraping and Sentiment Analysis  

## Project Overview  
This project focuses on scraping movie data from IMDB, performing exploratory data analysis (EDA), and conducting sentiment analysis on user reviews. The goal is to provide insights into movie performance, audience reception, and trends over the years. The project features an interactive menu-driven interface for data visualization and analysis.

## Features  
- **Web Scraping**: Extract movie details (titles, genres, ratings, budgets) from IMDB using `BeautifulSoup` and `requests`.  
- **Data Storage and Cleaning**: Store data in MySQL, clean and preprocess using `pandas` and `numpy`, and convert currency values using `CurrencyConverter`.  
- **Sentiment Analysis**: Analyze user reviews using `VADER` and `nltk` to classify sentiment as positive, negative, or neutral.  
- **Machine Learning**: Use `LinearSVC` and `TfidfVectorizer` to classify text data and predict sentiment trends.  
- **Visualization**: Generate bar plots, boxplots, and distribution plots using `seaborn` and `matplotlib` for insights on ratings, budgets, and audience reception.  

## Libraries Used  
- **Data Processing**: `pandas`, `numpy`, `CurrencyConverter`, `scipy`  
- **Web Scraping**: `BeautifulSoup`, `requests`, `urllib`  
- **Database**: `mysql.connector`  
- **Sentiment Analysis**: `nltk`, `VADER`  
- **Machine Learning**: `scikit-learn`  
- **Visualization**: `matplotlib`, `seaborn`  

## Installation  
1. Clone this repository.  
   ```bash  
   git clone <repository_url>  
   ```  
2. Install the required Python packages.  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Set up MySQL and configure the database connection in the script.  

## Usage  
1. Run the script to access the menu-driven interface:  
   ```bash  
   python main.py  
   ```  
2. Select from the following menu options:  
   - **Search Movie**: Scrape and display data for a specific movie.  
   - **Analyze Data**: Perform EDA and visualize trends.  
   - **Quit**: Exit the application.  

3. In the **Analyze Data** option, input a year range (e.g., 2000-2015) to explore:  
   - Top-rated and high-budget movies  
   - Comparison of critic vs. audience ratings  
   - Visual distribution of budgets and ratings  

## Examples  
- **Top 10 Rated Movies**: Displays the highest-rated movies within the selected year range.  
- **Sentiment Analysis**: Displays sentiment polarity of user reviews as positive, negative, or neutral, providing insights into audience perception.  

  
