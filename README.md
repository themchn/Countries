# Countries
Free legally receivable IPTV channels for Kodi, VLC or other media players as .m3u for Kodi. :-)

The lists work fine with me in the IPTV Simple Client from Kodi or the VLC Player. To automatically create the individual lists
to one list, I use the Add-on IPTV-Merge from Matt Huisman. ;-) You find this great Add-on here: [IPTV Merge Kodi Add-on](https://www.matthuisman.nz/2019/02/iptv-merge-kodi-add-on.html)

Without Kodi you can use the lists in the VLC Media Player. :-)

You can also use the `ZZ_PLAYLIST_ALL_TV.m3u`, there you have all TV stations in one list (.m3u).

The correct link to use the Playlist-ALL in the VLC Player or with the IPTV Simple Client in Kodi is:

[https://raw.githubusercontent.com/themchn/Countries/master/ZZ_PLAYLIST_ALL_TV.m3u](https://raw.githubusercontent.com/Free-IPTV/Countries/master/ZZ_PLAYLIST_ALL_TV.m3u)

Important! Some streams (very few) only work in Kodi with the Youtube add-on ;-)

Should a channel stop working, just leave a message. You can do this in the tab "[Issues](https://github.com/themchn/Countries/issues)". :-)

My `ZZ_PLAYLIST_ALL_TV.m3u` is also used in the pre-configuration of the new Hypnotix app. This app comes from the Linux Mint team. :-)

[https://itsfoss.com/hypnotix-iptv-app/](https://itsfoss.com/hypnotix-iptv-app/)

If you add streams to your current fork and make a pull request, please note the following:

1. Pay attention to the alphabetical order (0-9. A-Z).
2. Add the same Group-Name, it is the Country
3. Do not add any GEO-Blocked streams, the streams in my M3Us can be seen by anyone, anywhere.
4. Don't add illegal streams. Unfortunately there have been people who already did that and gave the name Kodi a bad reputation through their ignorance.
5. Don't add new parameters. Only use `#EXTINF:-1 tvg-id="" tvg-name="" tvg-logo="" group-title=""` and no others!

