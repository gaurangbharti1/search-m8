# Search m8

A service that scrapes google and youtube search to transcribe and obtain summaries and keywords of the content in articles and videos. 

Made for Inventure Hackathon 2020 by team Etwas.

# Packages used

* [Flask](https://pypi.org/project/Flask/) - For the server.
* [sumy](https://pypi.org/project/sumy/) - For summarizing transcripts and scrape results.
* [beautiful soup 4 (bs4)](https://pypi.org/project/bs4/) - For web scraping search results.
* [regex](https://pypi.org/project/regex/) - for filtering
* [gensim](https://pypi.org/project/gensim/) - for obtaining keywords from transcripts
* [youtube-transcript-api](https://pypi.org/project/youtube-transcript-api/) - For transcribing youtube videos
* [youtube-search](https://pypi.org/project/youtube-search/) - For obtaining youtube search results
* [requests](https://pypi.org/project/requests/) - For sending http requests to obtain search engine results

# How to run code
```cmd
python main.py
```
**This will run the server on localhost at port 3000*
