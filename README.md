# Mission-to-Mars
##Purpose of Analysis

This analysis was divided into two parts. For the first part of the analysis, automated browsing using Splinter, was used to visit the Mars news site. The HTML code was extracted via Beautiful Soup. The titles and preview text of the news articles were scraped and extracted, and the scraped info was stored in a Python data structure. For the second part of the analysis, automated browsing was used to visit the Mars temperature data site, and the HTML code was extracted. The Mars data table was scraped and extracted, and stored in a Pandas DataFrame. The following observations were made with the scraped data:

- There are 12 months on Mars
- The dataset contained 1,867 Martian days worth of data
- Months 3 and 4 were the coldest months, average temperature being -83 C
- Month 8 was the warmest month, average temperature of -68 C
- Month 6 had the lowest atmospheric pressure, average of 745 Pascals
- Month 9 had the highest atmospheric pressure, average of 913 Pascals
- One Martian year is equivalent to 687 days on Earth
