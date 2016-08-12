# WhoWhatWere
WhoWhatWere is a [YouTube Channel](http://whowhatwere.download) run by [Chris Were](http://site.whowhatwere.download/info.html), focusing on GNU/Linux, Tech and all things Free Software. This repo contains his site, hosted on [ZeroNet](https://zeronet.io) ([proxy here](http://site.whowhatwere.download)), and the tools used to maintain it.

## WereBot
Optional script for quickly updating the site automatically.
##### Requirements
- [YouTube API Key](https://console.developers.google.com) 
- [youtube-dl](https://rg3.github.io/youtube-dl/)

Upon launch, wereBot looks for a `youtubeapi` file in your home directory. If it cannot  
find it, it'll ask you to enter a key and will save it for next time.

##### Restore
In the event that wereBot breaks the index, just run wereBot again and enter `r` to auto  
restore the index.html file from the GitHub repository.

##### Usage
Simply run the script using `./wereBot` and enter `a` and _that's it_.  
The script will automatically download the latest video from Chris's YouTube channel in _webm_ format,  
retrieve all necessary metadata and add the item as an `<article>` to the index page.
