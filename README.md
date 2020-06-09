

# Code for analyzing podcast transcripts

Hypothesis: narrative-driven podcasts that utilize storytelling tend to follow a similar pattern, which follows the pattern identified by Joseph Campbell in "The [Hero's Journey](https://blog.reedsy.com/heros-journey/". 

This is a research project.

## Pipeline

### Extraction

- Use Listennotes API to identify raw mp3/wav file for podcast audio file
- Use curl/requests, save podcast audio files onto harddrive
- sync to Google Cloud Storage

### Tranformations

- Use Google's Speech-to-Text API to transcribe audio to transcript

## Viz

- Timeseries/Sentiment analysis over time; sentiment is proxy for the hero's journey, negative sentiment correlates with the downward/discovery parts of the narrative; positive sentiment during the hero's rise.
- Change in vocal expressions/levels of excitement


## Current Status:



