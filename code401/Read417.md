# What we will learn

- Web Scrape 

The source of this summary [The first link](https://towardsdatascience.com/how-to-web-scrape-with-python-in-4-minutes-bc49186a8460)

The source of this summary [The second link](https://en.wikipedia.org/wiki/Web_scraping)

The source of this summary [The third link](https://www.scrapehero.com/how-to-prevent-getting-blacklisted-while-scraping/)

______________________________________


## What is Web Scrape

**Web scraping is a term used to describe the use of a program or algorithm to extract and process large amounts of data from the web.which can save a huge amount of time and effort. Whether you are a data scientist, engineer, or anybody who analyzes large amounts of datasets, the ability to scrape data from the web is a useful skill to have.**


### Python Code

1. We start by importing the following libraries.

    import requests
    
    import urllib.request
    
    import time
    
    from bs4 import BeautifulSoup
    
2. we have to set the url to the website and access the site with our requests library

    url = 'http://web.mta.info/developers/turnstile.html'
    
    response = requests.get(url)

3. we shuold parse the html with BeautifulSoup so that we can work with a nicer, nested BeautifulSoup data structure.

    soup = BeautifulSoup(response.text, “html.parser”)

4. We use the method .findAll to locate all of our <a> tags.
    
    soup.findAll('a')
  
5. geting data files with a for loop to download the links

### Techniques
  
**Human copy-and-paste**
  
*The simplest form of web scraping is manually copying and pasting data from a web page into a text file or spreadsheet.*
  
*Sometimes even the best web-scraping technology cannot replace a human's manual examination and copy-and-paste, and sometimes this may be the only workable solution when the websites for scraping explicitly set up barriers to prevent machine automation.*
  
 
### Text pattern matching
 
*A simple yet powerful approach to extract information from web pages can be based on the UNIX grep command or regular expression-matching facilities of programming languages (for instance Perl or Python).*
  
### HTTP programming

*Static and dynamic web pages can be retrieved by posting HTTP requests to the remote web server using socket programming.*

### HTML parsing

>Many websites have large collections of pages generated dynamically from an underlying structured source like a database.Data of the same category are typically encoded into similar pages by a common script or template.In data mining, a program that detects such templates in a particular information source, extracts its content and translates it into a relational form, is called a wrapper.Wrapper generation algorithms assume that input pages of a wrapper induction system conform to a common template and that they can be easily identified in terms of a URL common scheme.
  
  
### How can websites detect and block web scraping? 

**Websites can use different mechanisms to detect a scraper/spider from a normal user**

1. Unusual traffic/high download rate especially from a single client/or IP address within a short time span.

2. Repetitive tasks performed on the website in the same browsing pattern – based on an assumption that a human user won’t perform the same repetitive tasks all the time.  

3. Checking if you are real browser – A simple check is to try and execute javascript. Smarter tools can go a lot more and check your Graphic cards and CPUs to make sure you are coming from real browser. 

4. Detection through honeypots – these honeypots are usually links which aren’t visible to a normal user but only to a spider. When a scraper/spider tries to access the link, the alarms are tripped.  
  
  
