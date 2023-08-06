# Project Overview

This is a custom search engine with advanced filtering capabilities based on trackers and ads made with Flask, SQLite and using the search data from Google Custom Search API.

File overview:

* `app.py` - the web interface
* `filter.py` - the code to filter results
* `search.py` - code to get the search results
* `settings.py` - settings needed by the other files
* `storage.py` - code to save the results to a database
  
## Run

Run the project with:

* `pip install -r requirements.txt`
* `flask --debug run --port 5001`
