---
layout: home
permalink: /
image:
  feature: background.jpg
noindex: false
---

<sectionleft>
  <leftside>

<h2>Lightning search !</h2>

<p>Search in <em>your</em> Spotify library from <a href="http://www.alfredapp.com">Alfred</a> App.

<br>
Instantaneous search in your tracks, albums, artists, <em>Your Music</em> and playlists.</p>

  </leftside>
  <rightside><!--<a href="{{ site.url }}/images/index1.gif">--><img src="{{ site.url }}/images/index1.jpg"></a></rightside>
</sectionleft>


<br>
<br>


<sectionright>
  <leftside><img src="{{ site.url }}/images/index3.jpg"></a></leftside>
  <rightside>
  
<h2>Full control of your playlists !</h2>

<p>Browse and launch all your playlists
<br>
<a href="{{ site.url }}/articles/add">Add</a> tracks, album or even playlists to any of your playlist, or <em>Your Music</em> right from the workflow.
You can also <a href="{{ site.url }}/articles/remove">remove</a> tracks.</p>

  </rightside>
</sectionright>


<br>
<br>


<sectionleft>
  <leftside>

<h2>Search anything online !</h2>

<p>Missing something in your library? Search online for tracks, albums, artists and playlists</p>

<br>
<a href="{{ site.url }}/articles/search-online" class="btn-success">Read more</a>

  </leftside>
  <rightside><!--<a href="{{ site.url }}/images/index2.gif">--><img src="{{ site.url }}/images/index2.jpg"></a></rightside>
</sectionleft>

<br>
<br>


<sectionright>
  <leftside><img src="{{ site.url }}/images/play-queue2.jpg"></a></leftside>
  <rightside>
  
<h2>Play queue</h2>

<p>Get the list of tracks queued, aka the <a href="{{ site.url }}/articles/play-queue">Play Queue</a> directly in the workflow !</p>

<br>
<a href="{{ site.url }}/articles/play-queue" class="btn-success">Read more</a>

  </rightside>
</sectionright>


<br>
<br>

<h2>And much more !</h2>

<div class="bullets">
	{% for post in site.posts %}
	{% if post.bulletlist %}	
	<div class="bullet three-col-bullet">
		<div class="bullet-icon">
			<a href="{{ site.url }}{{ post.url }}"><img src="{{ site.url }}/images/bullet-{{ post.title | slugify }}.png" alt=""></a>
		</div><!-- /.bullet-icon -->
		<div class="bullet-content">
			<h2><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></h2>
			<p>{{ post.excerpt | remove: '<p>' | remove: '</p>'}}</p>
		</div><!-- /.bullet-content -->
	</div><!-- /.bullet -->
	{% endif %}
	{% endfor %}
</div><!-- /.bullets -->
