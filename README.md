


<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->




<h3 align="center">Data Scraping and NLP</h3>

  <p align="center">
    



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#installation">Next Steps</a></li>
      </ul>
    </li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
Import the code and the given imput file as well as the stopwords and master dictionary folders into your Jupyter notebook or any other python dev env
### Prerequisites
Install:
1. pip
2. BeautifulSoup4


<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Installation

```
!pip install beautifulsoup4
!pip install requests
!pip install urllib2

```
<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Next Steps

Write functions for performing textual analysis :
1. Cleaning of data using stop words
2. To scrape the title and content of the articles from the urls given in the input urls
3. Export the scraped data by creating .txt files according to urlid.txt and then importing the scraped data into these files
4. Calculate the NLP variables using TextBlob as shown in the code
5. Export them to appropriate columns in the output.xlx file



