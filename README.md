# web-scraping-challenge
The project consisted of two technical products: scraping titles and preview text from Mars news articles, and scraping and analyzing Mars weather data.

## Deliverable 1: part_1_mars_news.ipynb
In Deliverable 1, the task was to scrape titles and preview text from the Mars News website. The process involved using automated browsing to visit the website and inspecting the page to identify the elements to scrape. The Beautiful Soup library was recommended for extracting text elements from the website. The scraped data was stored in Python data structures, specifically in dictionaries with two keys: "title" and "preview". All the dictionaries were stored in a Python list. The final step was to print the list in the Jupyter Notebook. Optionally, the scraped data could be exported to a JSON file for easier sharing, although this was not required for the assignment.

## Deliverable 2: part_2_mars_weather.ipynb
In Deliverable 2, the objective was to scrape and analyze Mars weather data from the Mars Temperature Data Site. Similar to the previous task, automated browsing was used to visit the website and identify the elements to scrape. The instructions suggested using Beautiful Soup for scraping the data from the HTML table. The scraped data was assembled into a Pandas DataFrame, with columns corresponding to the headings of the table. The columns included information such as the identification number, terrestrial date, sol (Martian day), solar longitude, month, minimum temperature, and atmospheric pressure. The data types of the columns were examined, and if necessary, they were converted to the appropriate datetime, int, or float data types.

The analysis of the dataset involved answering several questions using Pandas functions. The questions included determining the number of months on Mars (determined to be 12), the number of Martian days' worth of data in the dataset (1867), identifying the coldest and warmest months on Mars (months 3 and 8) by finding the average minimum daily temperature and plotting the results as a bar chart, identifying the months with the lowest and highest atmospheric pressure (months 6 and 9) by finding the average daily atmospheric pressure and plotting the results as a bar chart, and estimating the number of terrestrial days in a Martian year by considering the time it takes for Mars to orbit the Sun (~650 days) and plotting the daily minimum temperature.

Finally, the DataFrame was exported to a CSV file.
