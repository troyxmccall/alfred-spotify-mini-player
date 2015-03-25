---
layout: article
title: "Issue with latest Spotify update"
date: 2015-03-20
modified: 2015-03-25
categories: blog
excerpt: "Version 1.0.x breaks the workflow"
image:
  teaser: 
  feature:
  credit:
  creditlink:
noindex: false
toc: true
comments: true
onhomepage : false
---

Spotify is currently deploying a version 1.0.2.x (latest one is `1.0.2.6.g9977a14b`) which breaks the [AppleScript](https://community.spotify.com/t5/Help-Desktop-Linux-Mac-and/Apple-scripting-broken-in-1-0-1-988-g8f17a348/td-p/1029434) support.

This version is a big downgrade, many users are complaining on their [forums](https://community.spotify.com/t5/Help-Desktop-Linux-Mac-and/The-latest-desktop-version-is-a-downgrade/td-p/1039724) because a lot of existing features have been removed or are no more working(AppleScript support is one of them).

Spotify is [explaining](https://community.spotify.com/t5/Help-Desktop-Linux-Mac-and/Desktop-Update-Version-1-0-1/td-p/1050266) that this is a complete rewrite, but that does not justify the fact they're pushing this _alpha_ version to end users...!

If you're one of the users who have been upgraded to 1.0.x version, the workflow will no more work. See this [issue](https://github.com/vdesabou/alfred-spotify-mini-player/issues/66) for more details. 

If you have latest version 6.1.1 of the workflow, you'll get a warning message indicating an AppleScript error :-

<figure>
    <img src="{{ site.url }}/images/blog/spotify_update_problem2.jpg"></a>
    <figcaption>Error message you get with version 6.1.1</figcaption>
</figure> 

There is a [workaround](http://dangercove.github.io/Spotify-AppleScript-Patch/) to have AppleScript working with version 1.x *BUT* the `play track` is still broken with the workaround, so the workflow will not be able to launch tracks or playlists, which is pretty useless.

The only way is to revert back to previous Spotify version by following steps [here](http://supraliminal.net/blog/2013/4/21/how-to-revert-back-to-the-older-better-spotify-client), see section _MAC OS X_.

Note that you can download `0.9.15.27` and not `0.8.5.1356` as described in the article.

After applying the workaround, you should see a message _There was a problem updating Spotify (BAD FILE SIG)_ :-

<figure>
    <img src="{{ site.url }}/images/blog/spotify_update_problem.jpg"></a>
    <figcaption>Message: There was a problem updating Spotify</figcaption>
</figure>

Update (20th March): a Spotify developer [informed](http://stackoverflow.com/questions/29039514/applescript-to-tell-spotify-to-play-isnt-working-after-osx-update-to-yosemite/29047174#29047174) that it is fixed in next Spotify version (no availability date yet).




