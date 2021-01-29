# Hacker News Grude Script

Holding a grudge against other users on Hacker News? Wish there was a way to downvote your enemies' posts automatically? This is the script for you. This script takes a list of usernames you hold a grudge against and will automatically downvote all of their recent posts, if possible. Simply provide a list of usernames, plug in your Hacker News credentials, and run the script.

## How to use

Add a list of usernames you wish to automatically downvote to the `names.txt` file in the same directory as the script. Then invoke the script in the following fashion:

```
./downvote_grudges <your_username> <your_password>
```

It goes without saying that this script requires that your user account has sufficient 'karma' to downvote other users.

## Should I just trust this script with my credentials?

No. You should never *trust* any script with your credentials. Look through the script for yourself and rest assured that it isn't doing anything malicious with your Hacker News credentials. It's only ~130 lines of well-formed and documented Python, so you can easily audit it for yourself.

## Will I get caught using this and banned?

Unlikely. I've been using it for some time without any negative repercussions.
