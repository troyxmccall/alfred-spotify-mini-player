---
layout: article
title: "Troubleshooting"
date: 2014-12-22T11:39:03-04:00
modified:
categories: articles
excerpt: "What to do when you're facing an issue."
image:
  teaser: teaser-troubleshooting.jpg
  feature:
  credit: 
  creditlink:
noindex: true
toc: false
---

If you experience an issue with the workflow, follow these steps:-

* Use the ```spot_mini_debug``` command, it will generate a ````spot_mini_debug.tgz```` file in your *Downloads* directory. 

<figure>
	<img src="{{ site.url }}/images/spot_mini_debug.png"></a>
	<figcaption>An exception occurred.</figcaption>
</figure>

* Open an issue on the [Github page](https://github.com/vdesabou/alfred-spotify-mini-player/issues/new). You can also use command ```spot_mini_issue``` to open the issue:-

<figure>
	<img src="{{ site.url }}/images/spot_mini_issue.png"></a>
	<figcaption>Open an issue on Github page.</figcaption>
</figure>


* Send the ```spot_mini_debug.tgz``` to [this email](mailto:alfred-spotify-mini-player@gmail.com)


**Note:** With the ```spot_mini_debug.tgz```, I'll have access to your Spotify library (but not your credentials), this is for the time of investigation. Once investigation, you can regenerate a ```Client Secret```, as explained on the [Spotify Application page](https://developer.spotify.com/my-applications):-



<figure>
	<img src="{{ site.url }}/images/application_regenerate_key.png"></a>
	<figcaption>Regenerate Client Secret once investigation is over.</figcaption>
</figure>
