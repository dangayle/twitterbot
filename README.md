twitterbot
==========

Twitter bot that tweets a random line from a file.

Uses Twisted to periodically select a random line from an input file,
and Twython to post it to Twitter using your credentials.

Usage
-----
Where each line in file.txt is a single sentence terminated by a newline ('\n'):

```
python twitterbot.py example.txt
```

Dependencies
------------

Requires Twython and Twisted

```
pip install twython twisted
```
