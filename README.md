
# Youtube API microproject

Since I watch a lot of mindless Chinese Shotform dramas, I had curated data on all the mini dramas that I had watched - the name of the drama and it's YouTube link.

Since I already had the names and it's links I just wanted to fill in the runtime and the Channel name of that particular video. 

Instead of doing this manually, I thought of using the YouTube API to extract all the info that I needed.

Nothing groundbreaking just a personal project that stemmed out of laziness.
## Documentation

Prerequisites:

    1. Get a YouTube API Key
    2. Go to Google Cloud Console
    3. Enable the YouTube Data API v3
    4. Generate an API Key

Install Required Libraries:

    pip install pandas google-auth google-auth-oauthlib google-auth-httplib2 

How It Works:

    1. Reads an Excel file containing video names and YouTube links.
    2. Extracts the video ID from the URL.
    3. Calls the YouTube Data API to fetch:
        i.  Total duration (in seconds)
        ii. Channel name
    4. Saves the updated data back into a new Excel file.


## API Reference

[Youtube Data API Reference ](https://developers.google.com/youtube/v3/docs)

## Authors

- [@krithiksharan](https://www.github.com/krithiksharan13)


## License

[MIT](https://choosealicense.com/licenses/mit/)

