# reddit-parser
Parses every post from a given timeframe in a subreddit into video-friendly images

# Installation:
In the root directory:
> pip install -r requirements.txt

On Linux, you will also need to do 
>sudo apt-get install python3-tk

# Usage: 
Simply call parse.py in this format: 

> parse.py subreddits start_time end_time 

Where subreddits is a list of comma seperated subreddits to parse (just one is fine), start_time is the time to begin parsing in epoch time and end_time is the time to end parsing. The parser will then format each image post it finds chronologically into the provided template and save it in the 
`out` folder.

A template to paste images into can be found in `reddit_parse/resources/template.png`.
All parsed posts will be logged in `logs/record.txt`. 
