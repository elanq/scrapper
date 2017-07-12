# Scrapper

These are my collection of different purpose scripts that basically scrap data from various websites

### reddit_scrapper
this script intent is to scrap first 25 replies in reddit thread(s) and generate them into pdf format.
there are subreddits that have interesting replies instead of the original post. For example `/r/WritingPrompts` where all the replies are the core of the subreddit itself (in fact this script was originally intended only to scrap this subreddit. But i've made it to not specifically target specific subreddit)
#### Usage
just run this command
```sh
cd /target/to/reddit_scrapper
./reddit_scrap [post_urls]
```

example

```sh
./reddit_scrap https://www.reddit.com/r/WritingPrompts/comments/6i00oy/wp_you_hire_a_female_prostitute_tell_her_to_meet/.json https://www.reddit.com/r/WritingPrompts/comments/6gl289/wp_all_of_the_1_dad_mugs_in_the_world_change_to/.json
```

remember to end the url with .json so that this script will able to read the data
