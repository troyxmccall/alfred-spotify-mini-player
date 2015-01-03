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
noindex: true
---


This is the list of current known issues:

* Collaborative playlists are not currently retrievable (see [Web API](https://developer.spotify.com/web-api/get-list-users-playlists/))

* Local tracks are not currently supported. This is a bug of Web API.

* It is not possible as of now to subscribe to a playlist with the Web API. Once it would be supported, I'll add it.

* The *Starred* playlist is not returned by Web API: Spotify has removed the notion of 'starred tracks' (which is now kind of replaced by "Your Music").
As a workaround, you can create a new playlist (called 'Starred') and copy all your starred tracks in it.