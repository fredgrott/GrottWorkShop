---
layout: page
title: Colophon
header: Colophon
group: navigation
---
{% include JB/setup %}

## How This Was Built

<a href="{{ BASE_PATH }}/assets/img/colophon_browser_full.png" target="_blank">
<div class="well">
<img src="{{ BASE_PATH }}/assets/img/colophon_browser_small.png"/>
</div>
</a>
Okay so I am using some basic Ruby items:
     <ul class="well">
      <li>Jekyll</li>
      <li>Liquid</li>
      <li>YAML</li>
      <li>Maruku</li>
     </ul>

Jekyll is a templete engine among several template engines suhc as hyde ClearSilver, etc. With a 
template engine you have what we use to rely on with server side includes in that it allows us to
repeat snippets of code/html. In my particular set-up I am not using plugins but if you want you 
can add ruby plugins that hook into both Jekyll and Liquid to add even more features.

Liquid is more of a layout engine in that you can specify certain logic constructs and use 
variables to create dynamic layouts of such things like aproduct catalogue for example. In this site
example, the top navigaition bar is dynamically created via liquid logic and variables.


What is nice about Maruku is that you get nice helpful warnings in the terminal to correct your
markdown/html syntax and often its close to suggesting where the actual error occurred.     
     
     
 And some other stuff that is not Ruby based:
 <ul class="well">
       <li>Markdown</li>
       <li>Twitter BootStrap</li>
       <li>JekyllBootstrap</li>
       <li>Eclipse IDE/Aptana</li>
       <li>Github hosting</li>
</ul>
While testing I use a command:

<code>jekyll --server</code>

to run jekyll to generate the pages in -site sub-folder and view it in a browser at:

<code>localhost:4000</code>

as Jade's JekyllBootstrap has some liquid and config.yml magic to allow me to do that without large
amount of manual settings.

I am using Github hosting as will eventually be using this on my own domain and Github allows
one to use CNAME to redirect everything to the domain name.

While their exists several responsive hmtl5 frameworks I have found that Twitter's Bootstrap is the 
one that most servers my needs. And because I also use that same framework for my project codeqa 
and project docs I get a full re-use.

You can find my git of this site at:

[Git of GrottWorkshop](http://github.com/shareme/GrottWorkShop)

to see what modifications I made to Jade's JekyllBootstrap.
