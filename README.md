# Take Home Test

## Assignment

In Python, write an application which accepts a CSV with two columns, `subreddit` and `count`.

Example input .csv:

```
aww,25
cats,60
```

When executed, it should use the [Reddit API](https://www.reddit.com/dev/api/) to do the following for each row in the input .csv:

- Pull `count` of the top posts from `subreddit` (e.g. pull the top 25 posts from r/aww, the top 60 posts from r/cats)
- For each top post, download its thumbnail image, save it in a directory corresponding to the subreddit (e.g. `aww`, `cats`)
- Resize and crop all downloaded images to 100x100 pixels.

