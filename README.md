# IMDb Top 250 Movies Scraper  

This project extracts data about the top 250 movies from the IMDb website using web scraping techniques. The goal is to gather accurate and well-structured information for analysis or further use.  

![imdb data](https://github.com/user-attachments/assets/28e6a36d-4e94-4d04-bcc9-34714df9fd46)

## Features  

The scraper collects the following details for each movie:  
- **Movie Name**  
- **Year of Release**  
- **Duration**  
- **MPAA Rating**  
- **IMDb Rating**  

The data is cleaned, formatted, and saved in a structured format (e.g., CSV or database).  

## Technologies Used  

- **Python**: Core programming language for the project.  
- **Selenium**: Used for automating browser actions and navigating the IMDb website.  
- **BeautifulSoup**: For parsing HTML content and extracting the required information.  
- **lxml**: A fast and efficient parser for processing HTML and XML data.  

## Process  

1. **Web Inspection**:  
   The IMDb website was inspected to identify relevant HTML elements for extracting movie details.  

2. **Data Extraction**:  
   Selenium automated the browser to load the webpage, while BeautifulSoup and lxml parsed the HTML to extract movie data.  

3. **Data Cleaning and Formatting**:  
   - Ensured all extracted fields were accurate and properly formatted.  
   - Handled inconsistencies and missing values to maintain data quality.  

4. **Data Storage**:  
   The cleaned data was saved in a structured format for further analysis or visualization.  

## Output  

The final output is a dataset containing details of the top 250 IMDb movies, ready for analysis or use in other projects.  

This project showcases skills in web scraping, data cleaning, and automation using Python and popular libraries like Selenium and BeautifulSoup.  
