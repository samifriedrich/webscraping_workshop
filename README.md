# Web Scraping in python: From HTML Soup to Tidy Data

A workshop created by Sami Friedrich for the [BioData Club](https://biodata-club.github.io/) Workshop Series.


## Overview
The internet is overflowing with data ripe for harvesting. The challenge is that not all of that data is formatted neatly or easily accessible. Enter the web scraping multitool! With the power of web scraping, the contents of virtually any webpage can be transformed into analysis-ready data. During this workshop, you’ll learn using python how to:
 
1. Scavenge the contents of an HTML webpage
2. Extract only the data you want
3. Format the data into a table

## Libraries used:
  - `requests`
  - `BeautifulSoup4`
  - `pandas`

## Developer tools used:
  - the browser [Inspector/Inspect tool](https://www.toolsqa.com/selenium-webdriver/inspect-elements-using-browser-inspector/)
  - [Google Colab](https://research.google.com/colaboratory/faq.html)

## Prerequisites
1. Some basic python knowledge (looping through list elements, passing arguments to functions, writing basic functions) is a prerequisite for this workshop. 
  - If you are new to python or want to brush up on these topics before the workshop, check out these free tutorials:
    - http://introtopython.org/introducing_functions.html
    - http://introtopython.org/lists_tuples.html#Lists-and-Looping
2. We will also be working with HTML, and no prior experience is necessary.  However, it will be helpful to have a surface-level understanding of HTML elements - namely, their open/close tag structure, and how they nest within each other.
  - If you are not familiar with HTML elements or tags, please take a look at [this short overview on HTML Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics) before beginning.
 
 ## Files
 - [webscraping_workshop.ipynb](https://github.com/samifriedrich/webscraping_workshop/blob/main/webscraping_workshop.ipynb) is the Jupyter Notebook (without solutions) for the workshop. Follow the badge at the top to open in Google Colab, or download and run locally (just make sure you've already installed the libraries listed above.)
 - [solutions_to_webscraping_workshop.ipynb](https://github.com/samifriedrich/webscraping_workshop/blob/main/solutions_to_webscraping_workshop.ipynb) contains solutions to the Jupyter Notebook exercises.
 - [taphunter_belmont_station.html](https://github.com/samifriedrich/webscraping_workshop/blob/main/taphunter_belmont_station.html) is the downloaded .html file for the webpage this workshop is designed to scrape. If you're running things locally, be sure to place this file in the same folder as webscraping_workshop.ipynb.
 
 ## Other materials
  The Google Slides presentation accompanying this workshop can be found [here](https://docs.google.com/presentation/d/1ebdksaWybsPGxfdEWMW1Yz00m4g5wyR2Vk1Lue8IHGU/edit?usp=sharing).
  
 ## Author
Sami Friedrich, PhD candidate at Oregon Health and Science University. Please feel free to reach out with questions or comments!
- [LinkedIn](https://www.linkedin.com/in/sami-friedrich/)
- [Twitter](https://twitter.com/SamiFriedrich)
 
## License
This project is licensed under the MIT License (see [LICENSE](https://github.com/samifriedrich/webscraping_workshop/blob/main/LICENSE)).
