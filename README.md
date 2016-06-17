# Ten Word News
This Twitter bot uses the [Mediacloud](http://mediacloud.org/) Python API, found [here](https://pypi.python.org/pypi/mediacloud), to retrieve the ten most common words in the last seven days of mainstream US news.

See the bot in action [here](https://twitter.com/ten_word_news).

# Try it yourself
Fill in your Mediacloud and Twitter API tokens in `config.txt.template` and rename it `config.txt`. Run `pip install -r requirements.txt` to install dependencies. Then run `python dashboardbot.py` to post a tweet.