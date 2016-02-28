# mpdcover

Displays the embedded album art for the current mp3 playing
on an mpd server.

Album art is extraced using ffmpeg, processed with ImageMagick and displayed in a GTK3 window.


MPD Library must be accessible locally (e.g. network mount, sshfs)
in order for ffmpeg to export embedded image.

Requires:  
GTK+3  
gobject-introspection   
ffmpeg   
ImageMagick   
mpc  
