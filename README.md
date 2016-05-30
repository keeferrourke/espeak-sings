# Espeak Sings
### What is this?
This is a simple (but amusing) Python script that fetches song lyrics from the internet and feeds them to the speech synthesis program `espeak`.

Currently Espeak Sings only supports [AZLyrics.com](http://azlyrics.com) as the lyrics provider, but support for alternate providers may come later if decide to make the HTML parser and URL resolver more robust.

### Dependencies
This script requires the [`python-espeak`](https://launchpad.net/python-espeak) python bindings for the speech synthesis programme `espeak`.

### What's new?
Version 0.1
 * Initial release
 
### Known issues/annoyances
Without the sleep timer espeak quits about 1 second into the song. I'm not sure why.
The sleep timer is an ugly work around to make espeak do its thing. It results in a 5 minute silence after espeak finishes, and limits songs to 5 minutes in length. A more dynamic solution is required, but this project was a joke.

### License
This is free software licensed under the permissive What The Fuck You Want Public License (WTFPL). See COPYING for more details.

![WTFPL](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-1.png)
