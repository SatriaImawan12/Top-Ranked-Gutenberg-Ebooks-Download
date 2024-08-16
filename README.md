# Top Ranked Gutenberg Ebooks Download

## What is Project Gutenberg? 
Project Gutenberg is a volunteer effort to digitize and archive cultural works, to "encourage the creation and distribution of eBooks". It was founded in 1971 by American writer Michael S. Hart and is the oldest digital library. This longest-established ebook project releases books that entered the public domain, and can be freely read or downloaded in various electronic formats.

## Project Implementation Steps:
- This starter code scrapes the url of the Project Gutenberg's Top 100 ebooks (yesterday's ranking) for identifying the ebook links.
- It uses BeautifulSoup4 for parsing the HTML and regular expression code for identifying the Top 100 ebook file numbers.
- It includes a function to take an usser input on how many books to download and then crawls the server to download them in a dictionary object.
- Finally, it also includes a function to save the downloaded Ebooks as text files in a local directory.
