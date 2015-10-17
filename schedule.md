---
layout: page
title: Schedule
permalink: /schedule/
---

<h3 style="border-bottom: 1px solid #FDBB30;color:#F05133;">OCT 2015</h3>

<!--<img src="/content/schedule/2015-10.png" style="width:100%;margin-top:20px;"/>-->

<div class="cal">
{% for game in site.data.2015-16.1 %}
{% assign counter = forloop.index %}
{% if game.day %}
	{% if game.team %}
	<div class="cal0" onclick="gametime('0{{ counter }}')" style="cursor:pointer;">
 	  <img src="/content/schedule/days/game.png" class="cal1" />
	  {% if game.home %}
 	  <img id="away0{{ counter }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  <img id="home0{{ counter }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  {% else %}
 	  <img id="away0{{ counter }}" class="cal2" src="/content/schedule/teams/okc.png" />
	  <img id="home0{{ counter }}" class="cal3" src="/content/schedule/teams/{{ game.team }}.png" />
	  {% endif %}
	  {% if game.time %}
	  <img id="time0{{ counter }}" class="cal2" src="/content/schedule/tv/{{ game.time }}.png" style="visibility:hidden;" />
	  {% endif %}
	  {% if game.chan %}
	  <img id="chan0{{ counter }}" class="cal3" src="/content/schedule/tv/{{ game.chan }}.png" style="visibility:hidden;" />
	  {% endif %}
	</div>
	{% else %}
	<div class="cal0">
		<img src="/content/schedule/days/{{ game.day }}.png" class="cal1" />
	</div>
	{% endif %}
{% else %}
   <div class="cal0">
 	  <img src="/content/schedule/days/blank.png" class="cal1" />
   </div>
{% endif %}
{% endfor %}
</div>

<h3 style="border-bottom: 1px solid #FDBB30;color:#F05133;">NOV 2015</h3>

<div class="cal">
{% for game in site.data.2015-16.2 %}
{% assign counter = forloop.index %}
{% if game.day %}
	{% if game.team %}
	<div class="cal0" onclick="gametime(1{{ counter }})" style="cursor:pointer;">
 	  <img src="/content/schedule/days/game.png" class="cal1" />
	  {% if game.home %}
 	  <img id="away1{{ counter }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  <img id="home1{{ counter }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  {% else %}
 	  <img id="away1{{ counter }}" class="cal2" src="/content/schedule/teams/okc.png" />
	  <img id="home1{{ counter }}" class="cal3" src="/content/schedule/teams/{{ game.team }}.png" />
	  {% endif %}
	  {% if game.time %}
	  <img id="time1{{ counter }}" class="cal2" src="/content/schedule/tv/{{ game.time }}.png" style="visibility:hidden;" />
	  {% endif %}
	  {% if game.chan %}
	  <img id="chan1{{ counter }}" class="cal3" src="/content/schedule/tv/{{ game.chan }}.png" style="visibility:hidden;" />
	  {% endif %}
	</div>
	{% else %}
	<div class="cal0">
		<img src="/content/schedule/days/{{ game.day }}.png" class="cal1" />
	</div>
	{% endif %}
{% else %}
   <div class="cal0">
 	  <img src="/content/schedule/days/blank.png" class="cal1" />
   </div>
{% endif %}
{% endfor %}
</div>

<h3 style="border-bottom: 1px solid #FDBB30;color:#F05133;">DEC 2015</h3>

<div class="cal">
{% for game in site.data.2015-16.3 %}
{% assign counter = forloop.index %}
{% if game.day %}
	{% if game.team %}
	<div class="cal0" onclick="gametime(2{{ counter }})" style="cursor:pointer;">
 	  <img src="/content/schedule/days/game.png" class="cal1" />
	  {% if game.home %}
 	  <img id="away2{{ counter }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  <img id="home2{{ counter }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  {% else %}
 	  <img id="away2{{ counter }}" class="cal2" src="/content/schedule/teams/okc.png" />
	  <img id="home2{{ counter }}" class="cal3" src="/content/schedule/teams/{{ game.team }}.png" />
	  {% endif %}
	  {% if game.time %}
	  <img id="time2{{ counter }}" class="cal2" src="/content/schedule/tv/{{ game.time }}.png" style="visibility:hidden;" />
	  {% endif %}
	  {% if game.chan %}
	  <img id="chan2{{ counter }}" class="cal3" src="/content/schedule/tv/{{ game.chan }}.png" style="visibility:hidden;" />
	  {% endif %}
	</div>
	{% else %}
	<div class="cal0">
		<img src="/content/schedule/days/{{ game.day }}.png" class="cal1" />
	</div>
	{% endif %}
{% else %}
   <div class="cal0">
 	  <img src="/content/schedule/days/blank.png" class="cal1" />
   </div>
{% endif %}
{% endfor %}
</div>

<h3 style="border-bottom: 1px solid #FDBB30;color:#F05133;">JAN 2016</h3>

<div class="cal">
{% for game in site.data.2015-16.4 %}
{% assign counter = forloop.index %}
{% if game.day %}
	{% if game.team %}
	<div class="cal0" onclick="gametime(3{{ counter }})" style="cursor:pointer;">
 	  <img src="/content/schedule/days/game.png" class="cal1" />
	  {% if game.home %}
 	  <img id="away3{{ counter }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  <img id="home3{{ counter }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  {% else %}
 	  <img id="away3{{ counter }}" class="cal2" src="/content/schedule/teams/okc.png" />
	  <img id="home3{{ counter }}" class="cal3" src="/content/schedule/teams/{{ game.team }}.png" />
	  {% endif %}
	  {% if game.time %}
	  <img id="time3{{ counter }}" class="cal2" src="/content/schedule/tv/{{ game.time }}.png" style="visibility:hidden;" />
	  {% endif %}
	  {% if game.chan %}
	  <img id="chan3{{ counter }}" class="cal3" src="/content/schedule/tv/{{ game.chan }}.png" style="visibility:hidden;" />
	  {% endif %}
	</div>
	{% else %}
	<div class="cal0">
		<img src="/content/schedule/days/{{ game.day }}.png" class="cal1" />
	</div>
	{% endif %}
{% else %}
   <div class="cal0">
 	  <img src="/content/schedule/days/blank.png" class="cal1" />
   </div>
{% endif %}
{% endfor %}
</div>

<h3 style="border-bottom: 1px solid #FDBB30;color:#F05133;">FEB 2016</h3>

<div class="cal">
{% for game in site.data.2015-16.5 %}
{% assign counter = forloop.index %}
{% if game.day %}
	{% if game.team %}
	<div class="cal0" onclick="gametime(4{{ counter }})" style="cursor:pointer;">
 	  <img src="/content/schedule/days/game.png" class="cal1" />
	  {% if game.home %}
 	  <img id="away4{{ counter }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  <img id="home4{{ counter }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  {% else %}
 	  <img id="away4{{ counter }}" class="cal2" src="/content/schedule/teams/okc.png" />
	  <img id="home4{{ counter }}" class="cal3" src="/content/schedule/teams/{{ game.team }}.png" />
	  {% endif %}
	  {% if game.time %}
	  <img id="time4{{ counter }}" class="cal2" src="/content/schedule/tv/{{ game.time }}.png" style="visibility:hidden;" />
	  {% endif %}
	  {% if game.chan %}
	  <img id="chan4{{ counter }}" class="cal3" src="/content/schedule/tv/{{ game.chan }}.png" style="visibility:hidden;" />
	  {% endif %}
	</div>
	{% else %}
	<div class="cal0">
		<img src="/content/schedule/days/{{ game.day }}.png" class="cal1" />
	</div>
	{% endif %}
{% else %}
   <div class="cal0">
 	  <img src="/content/schedule/days/blank.png" class="cal1" />
   </div>
{% endif %}
{% endfor %}
</div>

<h3 style="border-bottom: 1px solid #FDBB30;color:#F05133;">MAR 2016</h3>

<div class="cal">
{% for game in site.data.2015-16.6 %}
{% assign counter = forloop.index %}
{% if game.day %}
	{% if game.team %}
	<div class="cal0" onclick="gametime(5{{ counter }})" style="cursor:pointer;">
 	  <img src="/content/schedule/days/game.png" class="cal1" />
	  {% if game.home %}
 	  <img id="away5{{ counter }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  <img id="home5{{ counter }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  {% else %}
 	  <img id="away5{{ counter }}" class="cal2" src="/content/schedule/teams/okc.png" />
	  <img id="home5{{ counter }}" class="cal3" src="/content/schedule/teams/{{ game.team }}.png" />
	  {% endif %}
	  {% if game.time %}
	  <img id="time5{{ counter }}" class="cal2" src="/content/schedule/tv/{{ game.time }}.png" style="visibility:hidden;" />
	  {% endif %}
	  {% if game.chan %}
	  <img id="chan5{{ counter }}" class="cal3" src="/content/schedule/tv/{{ game.chan }}.png" style="visibility:hidden;" />
	  {% endif %}
	</div>
	{% else %}
	<div class="cal0">
		<img src="/content/schedule/days/{{ game.day }}.png" class="cal1" />
	</div>
	{% endif %}
{% else %}
   <div class="cal0">
 	  <img src="/content/schedule/days/blank.png" class="cal1" />
   </div>
{% endif %}
{% endfor %}
</div>

<h3 style="border-bottom: 1px solid #FDBB30;color:#F05133;">APR 2016</h3>

<div class="cal">
{% for game in site.data.2015-16.7 %}
{% assign counter = forloop.index %}
{% if game.day %}
	{% if game.team %}
	<div class="cal0" onclick="gametime(6{{ counter }})" style="cursor:pointer;">
 	  <img src="/content/schedule/days/game.png" class="cal1" />
	  {% if game.home %}
 	  <img id="away6{{ counter }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  <img id="home6{{ counter }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  {% else %}
 	  <img id="away6{{ counter }}" class="cal2" src="/content/schedule/teams/okc.png" />
	  <img id="home6{{ counter }}" class="cal3" src="/content/schedule/teams/{{ game.team }}.png" />
	  {% endif %}
	  {% if game.time %}
	  <img id="time6{{ counter }}" class="cal2" src="/content/schedule/tv/{{ game.time }}.png" style="visibility:hidden;" />
	  {% endif %}
	  {% if game.chan %}
	  <img id="chan6{{ counter }}" class="cal3" src="/content/schedule/tv/{{ game.chan }}.png" style="visibility:hidden;" />
	  {% endif %}
	</div>
	{% else %}
	<div class="cal0">
		<img src="/content/schedule/days/{{ game.day }}.png" class="cal1" />
	</div>
	{% endif %}
{% else %}
   <div class="cal0">
 	  <img src="/content/schedule/days/blank.png" class="cal1" />
   </div>
{% endif %}
{% endfor %}
</div>