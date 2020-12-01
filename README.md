# Vizz
**Speech to text, then keyword extraction and vizualization, wrapped up in a beautiful UI**


## Getting started
To create a virtual environment for the Flask server,
`python3 -m virtualenv venv`
`source venv/bin/activate`

## Links
* Speech to text 
https://azure.microsoft.com/en-ca/services/cognitive-services/speech-to-text/
* Speech to text previous implementation
https://github.com/maxgillham/SmartEQ/blob/master/server/utils.py
* Immersive reader
https://azure.microsoft.com/en-ca/services/cognitive-services/immersive-reader/

# What it does

1. Press record
2. Speech input is taken in.
3. The input is presented in the UI
4. The Azure cognitive service API parses the input.
5. This app extracts key phrases
6. Visual interface presents the words and a visual representation of the words
7. Features offered
    1. Syllable parsing
    2. Adjust text spacing, size, themes, etc.
    3. Grammar clarification
    4. Noun / verb / adjective / adverb highlighting
    5. Color-coding

# How we built it
1. Things utilized
    1. Vanilla, HTML, CSS, JS for frontend
    2. Python flask web server for the backend
    3. Azure cognitive service speech recognition API
