# Find Complete Movie Info
This tool finds all important info about a movie from three sources, IMDB, Meta Critic, and Rotten Tomatoes, and generate a JSON object with the data.

The interface uses Python Flask, and the data fetching depends on Python 2.7 libraries; these libraries need to be installed for the code to work.

This code uses the following libraries:
- beautifulsoup4
- Flask
- lxml
- requests

## How to install:
Run `pip install -r requirements.txt`

## How to use
- Run the app using `python app.py`
- Go to your browser, navigate to `http://127.0.0.1:5000/` (usually).
- Enter the movie link from IMDB, e.g. `https://www.imdb.com/title/tt0076759`
- Click the triangular button.
- Wait for a few seconds for the result JSON Object.

