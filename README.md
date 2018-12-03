# Kashi
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)
[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)

[Kashi](https://www.github.com/zer8ne/kashi)(歌詞) is a custom preset for BTT (BetterTouchTool) that displays the current song's lyrics on the Touch Bar.

Mainly, Kashi does 3 things:
- It gets data about the current song playing via Applescript
- It searches for the song on [Genius](https://www.genius.com) and validates for higher accuracy
- It scrapes the lyrics from the raw HTML and formats them into a string output

Compatible with [Spotify](https://www.spotify.com/us/download/other/) and [iTunes](https://www.apple.com/itunes/download/).

## Installation

### Step 1/2: Install Dependencies

#### Kashi requires the following:
- [Python 3](https://www.python.org/downloads/release/python-371/)
  - [OSAscript](https://github.com/looking-for-a-job/osascript.py) -
  `pip3 install osascript`
  - [Requests](http://docs.python-requests.org/en/master/) - `pip3 install requests`
  - [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/) - `pip3 install bs4`
- [BetterTouchTool](https://folivora.ai/)
- An internet connection

### Step 2/2: Import Kashi Into BTT
- Copy the entire contents of kashi.json
- Go to the "TouchBar" section in BetterTouchTool's Preferences
- Paste

As Gordon Ramsay would say, DONE. You should see Kashi appear as an additional widget on your list.

## Future
Youtube and multi-language support.

## License
Kashi is licensed under GPLv3.
