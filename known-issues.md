---
layout: article
permalink: /known-issues/
title: "Known Issues"
modified: 2015-01-15
excerpt: "List of Known Issues."
image:
  feature:
  teaser:
  thumb:
share: false
toc: false
noindex: false
---


This is the list of current known issues:

* Collaborative playlists are not currently retrievable. This is a [limitation](https://developer.spotify.com/web-api/get-list-users-playlists/) of WEB API.

* Local tracks are not currently supported. This is a [bug](http://disq.us/8llqxk) of Web API. As a workaround, you can enable "lookup for local tracks" in Settings menu in order to find matches for your local tracks. Note that is it disabled by default as it obviously slows down library updates.

* The *Starred* playlist is not returned by Web API. Spotify has removed the notion of _starred tracks_ (which is now kind of replaced by _Your Music_).
As a workaround, you can create a new playlist (called 'Starred' for example) and copy all your starred tracks in it.