# spotify-blocklet
i3blocks blocket for Spotify. Displays currently playing song, and whether it is playing or not.

Uses the spotify-check script to actually run, this checks to see if Spotify is running so that the blocklet does not continue to display if Spotify is not running.

In your i3blocks conf, you have to set the spotify-check script to repeat in order for it to update near instantly. Below is an example from my i3blocks.conf

[spotify-check]                                                                                                    
instance=spotify                                                                                                     
interval=repeat                                                                                                      
separator=true                                                                                                       
color=#689d6a
