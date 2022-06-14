FORKED, I will be trying to modify this repo for adding onto some features I have in mind but first I've got to set it up properly
I'll make releases when possible!
# TwitchTest Revisited
Bandwidth tester for [Twitch](https://twitch.tv/)

![Screenshot](http://i.imgur.com/7PN13yF.png)

TwitchTest creates a test stream to Twitch, using the "?bandwidthtest" option so your channel doesn't actually go live. It will attempt to stream at up to 10 mbps and show the achieved bitrate for each server. An estimation of the connection quality is presented, which is based on the number of retransmissions required and how consistent the delay between consecutive sends are. A connection quality of 80+ is recommended for a reliable stream. The TCP window size (SO_SNDBUF) can be adjusted to see what effects it has, the default setting matches what is used in [OBS](https://obsproject.com/).

Requires Administrator privileges to run, as the Windows TCP connection metrics API is only available to applications running as administrator.

A pre-compiled binary for Windows can be downloaded at https://r1ch.net/projects/twitchtest.
