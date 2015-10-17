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
{% if game.day %}
	{% if game.team %}
	<div class="cal0" onclick="gametime(1{{ forloop.index }})" style="cursor:pointer;">
 	  <img src="/content/schedule/days/game.png" class="cal1" />
	  {% if game.home %}
 	  <img id="away1{{ forloop.index }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  <img id="home1{{ forloop.index }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  {% else %}
 	  <img id="away1{{ forloop.index }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  <img id="home1{{ forloop.index }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  {% endif %}
	  {% if game.time %}
	  <img id="time1{{ forloop.index }}" class="cal2" src="/content/schedule/tv/{{ game.time }}.png" style="visibility:hidden;" />
	  {% endif %}
	  {% if game.chan %}
	  <img id="chan1{{ forloop.index }}" class="cal3" src="/content/schedule/tv/{{ game.chan }}.png" style="visibility:hidden;" />
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
{% if game.day %}
	{% if game.team %}
	<div class="cal0" onclick="gametime(2{{ forloop.index }})" style="cursor:pointer;">
 	  <img src="/content/schedule/days/game.png" class="cal1" />
	  {% if game.home %}
 	  <img id="away2{{ forloop.index }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  <img id="home2{{ forloop.index }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  {% else %}
 	  <img id="away2{{ forloop.index }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  <img id="home2{{ forloop.index }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  {% endif %}
	  {% if game.time %}
	  <img id="time2{{ forloop.index }}" class="cal2" src="/content/schedule/tv/{{ game.time }}.png" style="visibility:hidden;" />
	  {% endif %}
	  {% if game.chan %}
	  <img id="chan2{{ forloop.index }}" class="cal3" src="/content/schedule/tv/{{ game.chan }}.png" style="visibility:hidden;" />
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

<h3 style="border-bottom: 1px solid #FDBB30;color:#F05133;">JAN 2015</h3>

<div class="cal">
{% for game in site.data.2015-16.4 %}
{% if game.day %}
	{% if game.team %}
	<div class="cal0" onclick="gametime(3{{ forloop.index }})" style="cursor:pointer;">
 	  <img src="/content/schedule/days/game.png" class="cal1" />
	  {% if game.home %}
 	  <img id="away3{{ forloop.index }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  <img id="home3{{ forloop.index }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  {% else %}
 	  <img id="away3{{ forloop.index }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  <img id="home3{{ forloop.index }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  {% endif %}
	  {% if game.time %}
	  <img id="time3{{ forloop.index }}" class="cal2" src="/content/schedule/tv/{{ game.time }}.png" style="visibility:hidden;" />
	  {% endif %}
	  {% if game.chan %}
	  <img id="chan3{{ forloop.index }}" class="cal3" src="/content/schedule/tv/{{ game.chan }}.png" style="visibility:hidden;" />
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

<h3 style="border-bottom: 1px solid #FDBB30;color:#F05133;">FEB 2015</h3>

<div class="cal">
{% for game in site.data.2015-16.5 %}
{% if game.day %}
	{% if game.team %}
	<div class="cal0" onclick="gametime(4{{ forloop.index }})" style="cursor:pointer;">
 	  <img src="/content/schedule/days/game.png" class="cal1" />
	  {% if game.home %}
 	  <img id="away4{{ forloop.index }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  <img id="home4{{ forloop.index }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  {% else %}
 	  <img id="away4{{ forloop.index }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  <img id="home4{{ forloop.index }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  {% endif %}
	  {% if game.time %}
	  <img id="time4{{ forloop.index }}" class="cal2" src="/content/schedule/tv/{{ game.time }}.png" style="visibility:hidden;" />
	  {% endif %}
	  {% if game.chan %}
	  <img id="chan4{{ forloop.index }}" class="cal3" src="/content/schedule/tv/{{ game.chan }}.png" style="visibility:hidden;" />
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

<h3 style="border-bottom: 1px solid #FDBB30;color:#F05133;">MAR 2015</h3>

<div class="cal">
{% for game in site.data.2015-16.6 %}
{% if game.day %}
	{% if game.team %}
	<div class="cal0" onclick="gametime(5{{ forloop.index }})" style="cursor:pointer;">
 	  <img src="/content/schedule/days/game.png" class="cal1" />
	  {% if game.home %}
 	  <img id="away5{{ forloop.index }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  <img id="home5{{ forloop.index }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  {% else %}
 	  <img id="away5{{ forloop.index }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  <img id="home5{{ forloop.index }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  {% endif %}
	  {% if game.time %}
	  <img id="time5{{ forloop.index }}" class="cal2" src="/content/schedule/tv/{{ game.time }}.png" style="visibility:hidden;" />
	  {% endif %}
	  {% if game.chan %}
	  <img id="chan5{{ forloop.index }}" class="cal3" src="/content/schedule/tv/{{ game.chan }}.png" style="visibility:hidden;" />
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

<h3 style="border-bottom: 1px solid #FDBB30;color:#F05133;">APR 2015</h3>

<div class="cal">
{% for game in site.data.2015-16.7 %}
{% if game.day %}
	{% if game.team %}
	<div class="cal0" onclick="gametime(6{{ forloop.index }})" style="cursor:pointer;">
 	  <img src="/content/schedule/days/game.png" class="cal1" />
	  {% if game.home %}
 	  <img id="away6{{ forloop.index }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  <img id="home6{{ forloop.index }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  {% else %}
 	  <img id="away6{{ forloop.index }}" class="cal3" src="/content/schedule/teams/okc.png" />
	  <img id="home6{{ forloop.index }}" class="cal2" src="/content/schedule/teams/{{ game.team }}.png" />
	  {% endif %}
	  {% if game.time %}
	  <img id="time6{{ forloop.index }}" class="cal2" src="/content/schedule/tv/{{ game.time }}.png" style="visibility:hidden;" />
	  {% endif %}
	  {% if game.chan %}
	  <img id="chan6{{ forloop.index }}" class="cal3" src="/content/schedule/tv/{{ game.chan }}.png" style="visibility:hidden;" />
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