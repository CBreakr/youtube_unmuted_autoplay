# youtube_unmuted_autoplay
Autoplay youtube videos without mute, also dynamically switch between videos

This code is mostly the same as this entry from google: https://developers.google.com/youtube/iframe_api_reference

It replaces a div on the body with a new iframe containing the video.

Switching between videos seems kind of strange. If there's a better way then please let me know. 
For now it seems like you need to replace the iframe that was added with a new div, and then run the original process over again.
