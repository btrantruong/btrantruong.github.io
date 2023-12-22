---
layout: page
title: Metro Map Maker
description: An application that allows users to create graphical representations to create subway maps
img: assets/img/projects/m3.jpg
category: undergrad
--- 

<!-- Content -->
<h3> Functionality Highlights</h3>
<ul>
<li>Save, Export Work</li>
<li>Undo, Redo system</li>
<li>Add, Delete, Modify Map ELements</li>
<li>Path finding</li>
</ul>
<p>
The application allows user to create graphical representations to create subway maps. The elements are: subway station, subway line, label, image. They can be edited and customized to adapt user's aesthetic needs. This project was done for CSE219 (Software Engineering) with <b>Java</b>. Head to <a href="https://github.com/btrantruong/metro-map-maker">my github page</a> to see source code.</p>

<h3>1. Add elements</h3>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/m3images/m3-begin.jpg" title="m3_Begin Work" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Start by adding stations and metro lines into the map.
</div>

<h3>2. Keep at it</h3>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/m3images/m3-changebackground.jpg" title="m3_ChangeBackground" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    After a while, the map will look something like this.
</div>

<p>Of course, you can <b>save your work</b> and come back to it later when you have time. After you've planned out the stations and subway postions, just hit save. <b>Editing is easy - click and drag</b> the station or label you want to move. For subway line, click the (-) button on the Subway Line toolbar.</p>

<h3>3. Make it pretty</h3>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/m3images/m3-final.jpg" title="m3_Final" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Then choose a background that you like and click Export.
</div>

<p>Voila! You have yourself a map. Save the work and come back later for modifications or export into a .JPG image</p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/m3images/m3-editstation.jpg" title="m3_Edit Station" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can <b>edit station's name and color</b> as well as most of the elements on the map.
</div>

<h3>4. Path Finding</h3>
<p>To <b>find the minimum transfer path</b> from one station to another, simply choose the start station and your destination and click the big yellow "Find Route" button.</p>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/m3images/m3-pathfinding.jpg" title="m3_findpath" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    How Find Route works.
</div>

<h3> Role within the project </h3>
<p>The project was done by me, according to the system specifications by Professor <a href="http://www3.cs.stonybrook.edu/~richard/">Richard McKenna </a></p> in CSE219 class. 