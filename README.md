# Deezer-Artist-Dumper / Downloader

A tampermonkey userscript which adds the functionality to download all of the Artists EPs, Singles, Albums and Features.
Aims to mimic the Deezer Design on desktop. Supports both dark and white mode, although intended for dark mode.
I do not know if "all" are really all songs, with all I mean every song which is listed on the discography page of an artist. I believe the Top 100 Tracks cannot include more songs. If that is wrong, contact me and I will add that.

## Features
- Adds a button on the artist page
- Lets you choose if you want to include EPs, Singles, Albums, Features (Although Deezer shows the whole Album as a Feature, only songs with the artist are added)
- Lets you choose if you want to add songs to a new playlist with the artist profile name/picture or an already existent playlist
- Lets you download a dump log which can be used in later dumps for the same artist to ignore songs which have already been added once (useful if you want to catch up on an artist)
- Lets you use Regex to blacklist Songs with certain titles
![image](https://github.com/bababoi-2/Deezer-Artist-Dumper/assets/165707934/5772bbe8-855c-45d4-b6da-5f51060ed1c1)

# TODO
- use multiple dumps for filtering. If a dump log is used, the new dump should merge with the song_ids from the old dump so that the new dump contains every song. Also remove the artist check for dump, a user should be able to filter out songs, regardless if its the same artist or not.
- artist/contributer blacklist
- combine blacklists into same text area and use some form of fomat to specify which rule is for what
