# Web-Scraping
![image](https://github.com/aashok30/Web-Scraping/assets/101622691/be94994e-9b7f-47ee-a447-7f135ebba281)

Welcome to the IMDb Top-Rated Movies Web Scraping project powered by AutoScraper. In this repository, I demonstrate how to extract structured information from IMDb's list of top-rated movies using Python's AutoScraper library! In this repository, you will find a Python-based web scraping solution to extract valuable data from IMDb's list of top-rated movies. IMDb is a well-known database of movies, TV shows, and celebrities, making it an excellent source for movie-related data.

## AutoScraper:
AutoScraper is a Python library that simplifies the process of web scraping. It automatically identifies and extracts data from web pages based on user-defined patterns, making it an efficient tool for collecting structured information from websites.

Below, I outline the steps to get started:

## Step 1: Install AutoScraper
Before using AutoScraper, you need to install it. You can do this with pip, the Python package manager, using the following command:

<img width="219" alt="image" src="https://github.com/aashok30/Web-Scraping/assets/101622691/caf86f14-37c3-465f-b8e2-74e802791ab8">

## Step 2: Import AutoScraper Module
Once you have AutoScraper installed, I have imports the AutoScraper class from the AutoScraper library, which is used for web scraping.


<img width="256" alt="image" src="https://github.com/aashok30/Web-Scraping/assets/101622691/5e28b5f2-8fcc-4248-ab8d-3a5932786fb1">

## Step 3: Define the IMDb URL and Wanted List
Defines the URL of the web page from which you want to scrape data. In this case, it's the IMDb top-rated movies page and specify the data I want to extract. In this case, we are interested in movie titles, release years, durations, and ratings. Define these as a list.

<img width="460" alt="image" src="https://github.com/aashok30/Web-Scraping/assets/101622691/5cb6d80a-d094-4b44-915d-02ccb2714229">

## Step 4: Initialize AutoScraper and Build the Scraper
Initializes an instance of the AutoScraper class, which will be used for defining scraping rules and extracting data and then sets up the scraping rules which tells the scraper to look for the specified data elements in the given URL. The method build returns a dictionary containing the scraped data.

<img width="329" alt="image" src="https://github.com/aashok30/Web-Scraping/assets/101622691/c349003f-9664-4d5f-8ab2-648c17f325db">

## Step 5: Extract and Display Scraped Data
Retrieves the scraped data in a more structured format. The get_result_similar method returns the data as a dictionary grouped by common keys. This step is useful for organizing and processing the scraped data.

<img width="347" alt="image" src="https://github.com/aashok30/Web-Scraping/assets/101622691/bf1cede7-09cb-47d9-855e-cf9ba3e60b8f">

## Step 6: Retrieve and Print Data Keys
Extracts the keys (attributes) from the dictionary containing the scraped data and stores them in a list.

<img width="215" alt="image" src="https://github.com/aashok30/Web-Scraping/assets/101622691/37587253-59af-47bd-a77e-0af38a9853a2">

## Step 7: Set Rule Aliases for Data Clarity
Assignd rule aliases to the keys extracted. The aliases make it easier to access specific data elements in the future.

<img width="289" alt="image" src="https://github.com/aashok30/Web-Scraping/assets/101622691/981bb159-3e48-4077-b4c7-6eb22f08b40c">


Please do not hesitate to contact for any suggestions. I greatly value your input and guidance, and it is always welcome.
