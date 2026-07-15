# API Advanced

This project uses the Reddit API to query subreddit data: subscriber counts,
hot post titles, recursive pagination through all hot posts, and keyword
counting across post titles.

## Requirements

Ubuntu 14.04 LTS / \python3\ (version 3.4.3)
The \Requests\ module is used for all HTTP requests
A custom \User-Agent\ is set to avoid Reddit rate limiting
Redirects are not followed, so invalid subreddits are handled correctly
All files are executable and follow the PEP 8 style

## Files

| File | Description |
| ---- | ----------- |
| \0-subs.py\ | \number_of_subscribers( total subscribers, or 0 if invalid. |subreddit)\ 
| \1-top_ten.py\ | \top_ten( prints the first 10 hot post titles. |subreddit)\ 
| \2-recurse.py\ | \recurse(subreddit, hot_ recursive list of all hot titles. |list=[])\ 
| \3-count.py\ | \count_words(subreddit, word_ sorted keyword counts. |list)\ 

## Usage

\`
python3 0-main.py programming
python3 1-main.py programming
python3 2-main.py programming
python3 3-main.py programming 'python java javascript'
\`
