---
layout: default
title: Webshooter
group: "navigation"
---
<h2>Webshooter</h2>
<p>We're trying to get away from dynamic websites, which tend to re-execute code when nothing's changed by catering individually to every page request. As a maintainable alternative we're leveraging Hyde and Jekyll, static website generators.</p>
<p>With them, we still gain the advantages of reusable content (e.g. one header file used by all pages), but we use that content to generate pages only once in a while, instead of at run time (i.e. at every page request).</p>
<p>Additionally, when the templates we use with Hyde and Jekyll are changed at the source, it's easy for the people who used them to pull down those changes and merge them into their own generated sites (if they want to). This works backwards as well: generated sites are effectively forks of the templates they use, and GitHub makes pulling changes and fixes an easy (but conscious) process for template maintainers.</p>
