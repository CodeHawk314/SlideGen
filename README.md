# Worship Slides Generator

## Installation

Install Python dependancies from requirements.txt
Set GENIUS_TOKEN in main.py to a Genius API key. See https://docs.genius.com/#/getting-started-h1.

> `pip install -r requirements.txt`

When instlling packages the order matters so you may have to also separately run `pip install python-pptx` and `pip install lyricsgenius`

## Usage

Run main.py and follow the prompts. If you choose to "search for a song" and pull lyrics from online, a text file will open up for you to edit the lyrics as desired. Double line breaks will cause a new slide to be generated at that point. When done editing, save the file, and press enter in the Python terminal. The finished slides will be saved to the ./output folder.
