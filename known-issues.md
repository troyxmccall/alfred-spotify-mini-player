---
layout: article
permalink: /known-issues/
title: "Known Issues"
modified: 2014-12-23
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

* Collaborative playlists are not currently retrievable (see [Web API](https://developer.spotify.com/web-api/get-list-users-playlists/))

* Local tracks are not currently supported. This is a bug of Web API. As a workaround, you can enable "lookup for local tracks" in Settings menu in order to find matches for your local tracks. Note that is it disabled by default as it obviously slows down library updates.

* It is not possible as of now to subscribe to a playlist with the Web API. As a workaround, you can choose "Open playlist in Spotify" option and then click _Subscribe_ button. Then refresh your library. Also, you can easily create a copy of the playlist with the [Add to...]( {{ site.url }}/articles/add) option.

* The *Starred* playlist is not returned by Web API: Spotify has removed the notion of _starred tracks_ (which is now kind of replaced by _Your Music_).
As a workaround, you can create a new playlist (called 'Starred') and copy all your starred tracks in it.