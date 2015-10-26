---
layout: page
title: Roster
permalink: /roster/
---

{% for player in site.data.roster %}
<div class="roster0" onclick="roster('p{{ player.number }}')">
	<div class="roster1">
		<h3 class="roster2">{{ player.name }}</h3>
		<h2 class="roster3">{{ player.number }}</h2>
	</div>
</div>
<div id="p{{ player.number }}" style="display:none;width:100%;overflow:hidden;">
	<div class="roster4">
		<p class="roster5">Position</p>
		<p>{{ player.position }}</p>
	</div>
	<div class="roster4">
		<p class="roster5">DOB</p>
		<p>{{ player.DOB }}</p>
	</div>
	<div class="roster4">
		<p class="roster5">Height</p>
		<p>{{ player.height }}</p>
	</div>
	<div class="roster4">
		<p class="roster5">Weight</p>
		<p>{{ player.weight }}</p>
	</div>
	<div class="roster4">
		<p class="roster5">Draft Position</p>
		<p>{{ player.draft_number }}</p>
	</div>
	<div class="roster4">
		<p class="roster5">Draft Year</p>
		<p>{{ player.draft_year }}</p>
	</div>
	<div class="roster4">
		<p class="roster5">College</p>
		<p>{{ player.college }}</p>
	</div>
	<div class="roster4">
		<p class="roster5">Country</p>
		<p>{{ player.country }}</p>
	</div>
</div>
{% endfor %}

<!--
<img src="/content/roster/steven-adams.jpg" style="width:48%;display:inline;float:left;margin:10px 1%;"/>

<img src="/content/roster/dj-augustin.jpg" style="width:48%;display:inline;float:left;margin:10px 1%;"/>

<img src="/content/roster/nick-collison.jpg" style="width:48%;display:inline;float:left;margin:10px 1%;"/>

<img src="/content/roster/kevin-durant.jpg" style="width:48%;display:inline;float:left;margin:10px 1%;"/>

<img src="/content/roster/josh-huestis.jpg" style="width:48%;display:inline;float:left;margin:10px 1%;"/>

<img src="/content/roster/serge-ibaka.jpg" style="width:48%;display:inline;float:left;margin:10px 1%;"/>

<img src="/content/roster/enes-kanter.jpg" style="width:48%;display:inline;float:left;margin:10px 1%;"/>

<img src="/content/roster/mitch-mcgary.jpg" style="width:48%;display:inline;float:left;margin:10px 1%;"/>

<img src="/content/roster/anthony-morrow.jpg" style="width:48%;display:inline;float:left;margin:10px 1%;"/>

<img src="/content/roster/steve-novak.jpg" style="width:48%;display:inline;float:left;margin:10px 1%;"/>

<img src="/content/roster/cameron-payne.jpg" style="width:48%;display:inline;float:left;margin:10px 1%;"/>

<img src="/content/roster/andre-roberson.jpg" style="width:48%;display:inline;float:left;margin:10px 1%;"/>

<img src="/content/roster/kyle-singler.jpg" style="width:48%;display:inline;float:left;margin:10px 1%;"/>

<img src="/content/roster/dion-waiters.jpg" style="width:48%;display:inline;float:left;margin:10px 1%;"/>

<img src="/content/roster/russell-westbrook.jpg" style="width:48%;display:inline;float:left;margin:10px 1%;"/>
-->