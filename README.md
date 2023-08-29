# media control for spotify
 control spotify with keyboard shortcuts using autohotkey
# # requirements
require: autohotkey if not using exe
require: send-keys-to-spotify.ahk(included on this github repo)
optional: nvdaControllerClient{x86/64}.dll (https://github.com/nvaccess/nvda/tree/master/extras/controllerClient)
note, you have to rename the file to "nvdaControllerClient.dll".
# # default keyboard shortcuts
here are the default keyboard shortcuts
you can change it using by editing the file
* alt+win+up/down: increase / decrease volume by 5%.
* alt+win+left / right: previous / next song
* ctrl+alt+win+up / down: increase / decrease the spotify's volume.
note, only works if the spotify is not minimised to the tray
* alt+win+m: mute / unmute the system
* alt+win+space: play / pause
* ctrl+win+alt+r: reload the scrypt
* ctrl+win+shift+left / right: rewind / fast forward
note, only works if the spotify is not minimised to the tray
* win+alt+t: enable / disable the title announcement
note, only works if you use nvda
* alt+win+l: like / dislike songs, but it have know way to know if a song is liked or not
# # how to use
just run the scrypt
it will run on the background
# # nown limitations
* it won't know if a song is liked or not.
* some keyboard shortcuts won't work if the spotify is minimized to the tray.
## thats it
enjoi
this is a scrypt that i wrote for my own use
feedback and suggestions are welcome.
