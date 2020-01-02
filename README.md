## VLC addons
### Youtube playlist addon

This addon is published at [videolan](https://addons.videolan.org/p/1344170/) with the below description.

#### Description (possibly out of sync with videolan page)
Import a youtube video / playlist into VLC.

##### History and maintenance
This is a modification of https://addons.videolan.org/p/1154080/ . The original author seems incommunicado, hence submitting this separate plugin. Please submit pull requests and issues at https://github.com/vvasuki/vlc-addons/blob/master/lua-addons/playlist_youtube.luac .

##### INSTALLATION:
- Download https://raw.githubusercontent.com/vvasuki/vlc-addons/master/lua-addons/playlist_youtube.luac or use the Download button (Some browser (Chrome...) may change the file extension for ".txt" instead of ".luac", so make sure you choose "All extensions" in the dialog box when you save the file on your computer.)
- put the file in the vlc /lua/playlist folder, by default (create directories if they don't exist):
  * Windows (all users): %ProgramFiles%/VideoLAN/VLC/lua/playlist
  * Windows (current user): %APPDATA%/vlc/lua/playlist
  * Linux (all users): /usr/lib/vlc/lua/playlist/
  * Linux (current user): ~/.local/share/vlc/lua/playlist/
  * Mac OS X (all users): /Applications/VLC.app/Contents/MacOS/share/lua/playlist/


##### USAGE:
- Copy the URL of the youtube video or playlist (must contain "list=PL...")
- Start VLC, press Ctrl+N, paste the url then click on "Play" (or Alt+P then Enter), the video /playlist should start

## Misc playlists
TODO
