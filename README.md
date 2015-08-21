# Espeak Sings
### What is this?
This is a simple (but amusing) Python script that fetches song lyrics from the internet and feeds them to the speech synthesis programme espeak.

Currently Espeak Sings only supports AZLyrics.com as the lyrics provider, but support for alternate providers may come later if decide to make changes to the HTML parser and URL resolver (which are both very basic right now).

### Dependencies
This script requires the [`python-espeak`](https://launchpad.net/python-espeak) python bindings for the speech synthesis programme `espeak`.

### What's new?
Version 0.1
 * Initial release
 
### Known issues/annoyances
Without the sleep timer espeak quits about 1 second into the song.
The sleep timer is an ugly work around to make espeak do its thing. It results in a 5 minute silence after espeak finishes, and limits songs to 5 minutes in length. A more dynamic solution is required.
