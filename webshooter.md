---
layout: default
title: ebshooter
---
<h2>webshooter.py</h2>
<p>We're trying to get away from dynamic websites, which tend to re-execute code when nothing's changed by catering individually to every page request. As a maintainable alternative we're leveraging Hyde and Jekyll, static website generators.</p>
<p>With them, we still gain the advantages of reusable content (e.g. one header file used by all pages), but we use that content to generate pages only once in a while, instead of at run time (i.e. at every page request).</p>
<p>Additionally, when the templates we use with Hyde and Jekyll are changed at the source, it's easy for the people who used them to pull down those changes and merge them into their own generated sites (if they want to). This works backwards as well: generated sites are effectively forks of the templates they use, and GitHub makes pulling changes and fixes an easy (but conscious) process for template maintainers.</p>

<div class="row">
<p>
<div class="span4">
<h2>Bootstrap</h2>
<p>Bootstrap is an open source web framework made by the folks at Twitter. It's praised as clean, easy, and designer-friendly. It's used by a number of websites which is too high to count to, but which includes some big shots like NASA and MSNBC.</p>
<p><a href="bootstrap.html" class="btn" href="#">View details &raquo;</a></p>
</div>
<div class="span4">
<h2>One.5lab</h2>
<p>One.5lab is an adaptation of OneLab, which is an LLNL web template/framework (and which itself actually uses Bootstrap). The OneLab guys' mission is to provide a (good looking) thematic consistency to LLNL's public-facing websites.</p>
<p><a href="one.5lab.html" class="btn" href="#">View details &raquo;</a></p>
</div>
<div class="span4">
<h2>More</h2>
<p>Webshooter was built with Bootstrap and One.5lab in mind, but who's really that close minded? If you've got a template that works in Hyde or Jekyll, it'll work with Webshooter. In fact, Webshooter will even clone it from any public Git repository for you.</p>
<p><a href="more.html" class="btn" href="#">View details &raquo;</a></p>
</div>
</p>
</div> 
