# NEWS_ANALYZER

Overview
NEWS_ANALYZER is a web-based application that extracts and analyzes news content from a given URL. The portal requires users to log in or sign up before accessing the features. Once logged in, users can submit a news URL, and the system will extract the following information:

News Heading

News Title

Main Content (with summary highlights) 

Technologies Used
Frontend:
HTML, CSS, JavaScript – For building a user-friendly interface

Backend:
Flask – For handling authentication, request processing, and routing

SQL Database – For storing user login data

Web Scraping & Text Processing:
BeautifulSoup – For extracting data from web pages

NLTK (Natural Language Toolkit) – For text processing

Regular Expressions (re) – For cleaning and extracting relevant content

Features
✔️ User Authentication: Login and Sign-up system with data stored in an SQL database
✔️ News Extraction: Retrieves the title, heading, and main content of the news article
✔️ Web Scraping: Uses BeautifulSoup to extract and process text from the given URL
✔️ Text Cleaning: Implements regular expressions and NLP techniques for better readability
✔️ Deployment: Hosted on Render for public access

