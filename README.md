#Practice 1: Web scraping

##Description
<p>In this notebook, I scrape the novel <em>Alice's adventures in Wonderland</em> from the website <a href="https://www.gutenberg.org/">Project Gutenberg</a>. Then I'll extract words from this web data using <code>BeautifulSoup</code> and <code>Requests packages</code>. Finally, I'll dive into analyzing the distribution of words using the Natural Language ToolKit (<code>nltk</code>). </p>

##Team members
The activity has been carried out individually by Noel Gallego Alarcón

##Source code files
src / main.py: point of entry to the program. Start the scraping process.
src / scraper.py: contains the implementation of the AccidentsScraper class whose methods generate the data set from the PlaneCrashInfo online database.
src / reason_classifier.py: contains the implementation of the class that is responsible for assigning a cause to a given accident summary. To do this, it uses the TextBlob library.


##Resources
Lawson, R. (2015). Web Scraping with Python. Packt Publishing Ltd. Chapter 2. Scraping the Data.
Subirats, L., Calvo, M. (2018). Web Scraping. Editorial UOC.
      
