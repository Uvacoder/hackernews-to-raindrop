# Import Hacker News upvoted posts to raindrop.io

Hacker News doesn't have an API, and mobile apps usually implement their own post saving/bookmarking mechanism. Frustrated with the lack of searchability, I decided to sync posts which I upvote to my raindrop.io account.

## Getting Started

Install required dependencies
```
pip install -r requirements.txt
```

Then add your raindrop API token and collection ID to `import-hackernews-to-raindrop.py`
```
RAINDROP_API_TOKEN="your-token-goes-here"
RAINDROP_COLLECTION_ID="your-collection-id-goes-here"
```

Finally, run `import-hackernews-to-raindrop.py`

```
python3 import-hackernews-to-raindrop.py your-username your-password 
```
Voila!
