---
layout: article
title: "Troubleshooting"
date: 2014-12-22T11:39:03-04:00
modified: 2015-01-06T11:39:03-04:00
categories: articles
excerpt: "What to do when you're facing an issue."
image:
  teaser: teaser-troubleshooting.jpg
  feature:
  credit:
  creditlink:
noindex: false
toc: false
comments: true
onhomepage : true
---

If you experience an issue with the workflow, follow these steps:-

* Use the `spot_mini_debug` keyword input (note that if an exception occurs, it is automatically called). This will generate a `spot_mini_debug.tgz` file in your _Downloads_ directory.

<figure>
	<img src="{{ site.url }}/images/spot_mini_debug.png"></a>
	<figcaption>An exception occurred.</figcaption>
</figure>

* Send the `spot_mini_debug.tgz` to this [email](mailto:alfred.spotify.mini.player@gmail.com) (you can also use the _Send an email to the author_ option when using `spot_mini_debug`)

**Note:** With the `spot_mini_debug.tgz`, I'll have access to your Spotify library (but not your Spotify password, don't worry :smile:). This is only for the time of investigation. Once investigation is over, you can regenerate a _Client Secret_, as explained in the [Spotify Application page](https://developer.spotify.com/my-applications):-

<figure>
	<img src="{{ site.url }}/images/application_regenerate_key.png"></a>
	<figcaption>Regenerate Client Secret once investigation is over.</figcaption>
</figure>


* Open an issue on the [Github page](https://github.com/vdesabou/alfred-spotify-mini-player/issues/new). You can also use command `spot_mini_issue` to open the issue:-

<figure>
	<img src="{{ site.url }}/images/spot_mini_issue.png"></a>
	<figcaption>Open an issue on Github page.</figcaption>
</figure>

* Before opening an issue, you can also have a look at the list of [known issues]( {{ site.url }}/known-issues)