
<?xml version="1.0" encoding="utf-8"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en">
<head>
<!-- 2019-03-03 Sun 16:04 -->
<meta http-equiv="Content-Type" content="text/html;charset=utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Org tutorials</title>
<meta name="generator" content="Org mode" />
<meta name="author" content="Worg people" />
<link rel="stylesheet" title="Standard" href="/worg/style/worg.css" type="text/css" />
<link rel="alternate stylesheet" title="Zenburn" href="/worg/style/worg-zenburn.css" type="text/css" />
<link rel="alternate stylesheet" title="Classic" href="/worg/style/worg-classic.css" type="text/css" />
<link rel="SHORTCUT ICON" href="/org-mode-unicorn.ico" type="image/x-icon" />
<link rel="icon" href="/org-mode-unicorn.ico" type="image/ico" />
<script type="text/javascript">
/*
@licstart  The following is the entire license notice for the
JavaScript code in this tag.

Copyright (C) 2012-2019 Free Software Foundation, Inc.

The JavaScript code in this tag is free software: you can
redistribute it and/or modify it under the terms of the GNU
General Public License (GNU GPL) as published by the Free Software
Foundation, either version 3 of the License, or (at your option)
any later version.  The code is distributed WITHOUT ANY WARRANTY;
without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE.  See the GNU GPL for more details.

As additional permission under GNU GPL version 3 section 7, you
may distribute non-source (e.g., minimized or compacted) forms of
that code without the copy of the GNU GPL normally required by
section 4, provided you include this license notice and a URL
through which recipients can access the Corresponding Source.


@licend  The above is the entire license notice
for the JavaScript code in this tag.
*/
<!--/*--><![CDATA[/*><!--*/
 function CodeHighlightOn(elem, id)
 {
   var target = document.getElementById(id);
   if(null != target) {
     elem.cacheClassElem = elem.className;
     elem.cacheClassTarget = target.className;
     target.className = "code-highlighted";
     elem.className   = "code-highlighted";
   }
 }
 function CodeHighlightOff(elem, id)
 {
   var target = document.getElementById(id);
   if(elem.cacheClassElem)
     elem.className = elem.cacheClassElem;
   if(elem.cacheClassTarget)
     target.className = elem.cacheClassTarget;
 }
/*]]>*///-->
</script>
</head>
<body>
<div id="preamble" class="status">
<script type="text/javascript">
  document.addEventListener('DOMContentLoaded',function() {
      document.getElementById("table-of-contents").onclick = function() {
          var elem = document.getElementById("text-table-of-contents");
          elem.style.display = elem.style.display == "block" ? "none" : "block";
      }
  });

  var url = document.location.href;
  var orgsource = url.substring(0, url.lastIndexOf("."))+".org.html";
  function show_org_source(){
      document.location.href = orgsource;
  }
</script>

<script>
(function(f, a, t, h, o, m){
	a[h]=a[h]||function(){
		(a[h].q=a[h].q||[]).push(arguments)
	};
	o=f.createElement('script'),
	m=f.getElementsByTagName('script')[0];
	o.async=1; o.src=t; o.id='fathom-script';
	m.parentNode.insertBefore(o,m)
})(document, window, '//stats.orgmode.org/tracker.js', 'fathom');
fathom('set', 'siteId', 'NWSQJ');
fathom('trackPageview');
</script>
</div>
<div id="content">
<h1 class="title">Org tutorials</h1>
<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#orga2a3867">General Introductions to Org-mode</a></li>
<li><a href="#orgff7b885">Power users describe their setup</a></li>
<li><a href="#org2de6cdb">Tutorials on specific features</a>
<ul>
<li><a href="#org61e54a1">Lists</a></li>
<li><a href="#Spreadsheet">Tables, Spreadsheet, Plotting</a></li>
<li><a href="#orgd7662e2">Dates and Times</a></li>
<li><a href="#org5ddb73a">Tags, Properties, and Column View</a></li>
<li><a href="#org3a73350">Remember</a></li>
<li><a href="#org57ff978">Capture</a></li>
<li><a href="#orge7d1793">Agenda and search</a></li>
<li><a href="#orgdb5123b">Customization</a></li>
<li><a href="#org1118275">Export and Publishing</a></li>
<li><a href="#orgc94ee74">Reproducible research</a></li>
<li><a href="#org8806b6a">Import</a></li>
<li><a href="#org842c618">Dependencies between tasks</a></li>
</ul>
</li>
<li><a href="#orge78b1f1">Special tasks</a>
<ul>
<li><a href="#org352f77d">Natural Project Planning</a></li>
<li><a href="#orgb0c504e">Tracking Habits</a></li>
<li><a href="#org0dc49e6">Measuring Personal Effectiveness</a></li>
<li><a href="#org0c53327">Using version Control with Your org files</a></li>
<li><a href="#org575a8cd">How to use jsMath with org-mode</a></li>
<li><a href="#org54ae39b">Creating a Blog with Jekyll and org</a></li>
<li><a href="#org666e5d2">Creating Beamer presentations</a></li>
<li><a href="#org2cb26ea">Creating Non-Beamer presentations</a></li>
<li><a href="#orgfb9603b">Keeping up with your team's tasks</a></li>
<li><a href="#org4f4c418">Tracking tasks through a series of meetings</a></li>
<li><a href="#org91e74c7">Weaving a budget with Org and ledger</a></li>
<li><a href="#org4bcab4f">Managing your web bookmarks</a></li>
<li><a href="#org4320b02">Contact management</a></li>
<li><a href="#org978705d">Contributing your package through Melpa + GitHub</a></li>
</ul>
</li>
<li><a href="#org26816d5">Personal Setup</a></li>
<li><a href="#orgd92f738">Screencasts</a></li>
<li><a href="#orgabae562">Features waiting for tutorials</a></li>
<li><a href="#org3cfa1c6">Org-related pages by Tutorial authors</a></li>
</ul>
</div>
</div>
<p>
<a href="../index.html">{Back to Worg's index}</a>
</p>

<div id="outline-container-orga2a3867" class="outline-2">
<h2 id="orga2a3867">General Introductions to Org-mode</h2>
<div class="outline-text-2" id="text-orga2a3867">
<ul class="org-ul">
<li><a href="https://orgmode.org/talks.html">Google Tech Talk about Org-mode</a>, a 45 minute talk given by Carsten
Dominik during a visit at <a href="http://maps.google.com/?q=37.423156,-122.084917+(Google%20Inc.)&amp;hl=en">Google</a>.</li>

<li><a href="http://www.nf.mpg.de/orgmode/guest-talk-dominik.html">Organizing a Scientist's Life and Work</a>, a 45 minute talk given by
Carsten Dominik during a visit at the <a href="http://www.nf.mpg.de/">Max-Planck Institute for
neurological Research Cologne</a>.</li>

<li>On <a href="http://twit.tv/floss136">FLOSS Weekly Episode 136</a> (Audio+Video download available)
Randal Schwartz interviews Carsten Dominik about Org-mode.</li>

<li><a href="https://orgmode.org/worg/org-tutorials/org-screencasts/ghm2011-demo.html">Emacs Org-mode presentation at GNU Hackers Meeting 2011 in Paris</a> (in
English), by Bastien Guerry.</li>

<li><a href="http://www.linuxjournal.com/article/9116">Getting Organized with Emacs Org-mode</a> by <a href="http://www.planetizen.com/user/2">Abhijeet Chavan</a>, an article
originally published in the <a href="http://www.linuxjournal.com/">Linux Journal</a>.</li>

<li><a href="orgtutorial_dto.html">The OrgMode tutorial</a> by <a href="http://dto.freeshell.org/notebook/">David O'Toole</a>, covering the basics of TODO
lists and the agenda.  It has been translated into <a href="orgtutorial_dto-fr.html">French</a>, <a href="http://hpcgi1.nifty.com/spen/index.cgi?OrgMode/OrgTutorial">Japanese</a>,
<a href="orgtutorial_dto-es.html">Spanish</a>, <a href="http://hokmen.chan.googlepages.com/OrgTutorial.en-cn.html">Chinese</a>, <a href="http://jmjeong.com/index.php?display=Emacs/OrgMode">Korean</a>, <a href="http://habrahabr.ru/blogs/emacs/105300/">Russian</a>, <a href="http://deneb.iszt.hu/~pasztor/orgtutorial/notebook/orgtutorial-hu.html">Hungarian</a> and <a href="orgtutorial_dto-pt.html">Portuguese</a>.</li>

<li><a href="http://jaderholm.com/screencasts.html">A 25 minute screencast</a> by <a href="http://jaderholm.com">Scott Jaderholm</a>, demonstrating the basic
features of Org-mode.</li>

<li><a href="http://sachachua.com/wp/2008/01/18/outlining-your-notes-with-org/">Outlining Your Notes with Org</a> by <a href="http://sachachua.com/wp/">Sacha Chua</a> covers outlining,
searching and internal links.</li>

<li><a href="http://members.optusnet.com.au/~charles57/GTD/orgmode.html">Using Emacs org-mode for GTD</a> by <a href="http://members.optusnet.com.au/~charles57/GTD/">Charles Cave</a> contains an
introduction into Org-mode, among other things.  Charles has also
written a more extensive document (), but here we still
link to the earlier version because of its nice overview over
Org-mode.</li>

<li>Emacs Org-mode, <a href="http://article.gmane.org/gmane.emacs.orgmode/8547">video version of a 2-hour talk</a> by Russell Adams at
the <a href="http://www.hlug.org/">Houston Linux User Group</a>.  The first half of the first hour is
<i>not</i> about Org-mode, but about the Linux command <code>xargs</code>.</li>

<li><a href="https://github.com/novoid/org-mode-workshop/blob/master/featureshow/org-mode-teaser.org">Demonstration of Org-mode features</a> by Karl Voit, presented for the
first time at <a href="http://glt12-programm.linuxtage.at/events/96.de.html">Grazer Linuxtage 2012</a>.</li>

<li><a href="https://github.com/novoid/org-mode-workshop">Org-mode Workshop</a> by Karl Voit, conducted at <a href="http://www.tugraz.at">Graz University of
Technology</a> in November 2012 (3x4 hours). It includes a newer version
of the feature-show from the entry above.</li>

<li><a href="org-outside-org.html">Org-mode outside Org-mode</a> by Thorsten Jolitz and François Pinard. An
introduction to the available libraries for using Org-mode's concepts and
Org-mode's functionality outside of Org-mode files, e.g. when working with
programming-language source-code files.</li>

<li><i>In German language:</i> <a href="ftp://ftp.freiesmagazin.de/2009/freiesMagazin-2009-10.pdf">Ordnung ins Chaos mit Org-Mode</a>, an excellent
introduction into Org-mode, by Rainer Koenig, published in the free
electronic journal <a href="http://www.freiesmagazin.de/">Freies Magazin</a>.</li>

<li><i>In French:</i> A <a href="http://www.olivierberger.com/weblog/index.php?post/2010/08/14/Ma-vie-a-chang%C3%A9-:-j-utilise-org-mode">general introduction</a> on Org for the "<a href="http://lifehacking.fr">lifehacking</a>"
group, by Olivier Berger.</li>

<li><i>In German:</i> <a href="http://www.suenkler.info/emacs-orgmode.html">Der Emacs Org mode</a>, a comprehensive blog post about Org-mode, by
Hendrik Sünkler.</li>

<li><i>In Spanish:</i> <a href="org-reference-guide-es.html">A reference guide</a> of each features, their text format
and their available keys. Don't confuse with
<a href="http://www.davidam.com/docu/orgguide.es.html">Guía Compacta de Org Mode</a>.</li>
</ul>
</div>
</div>

<div id="outline-container-orgff7b885" class="outline-2">
<h2 id="orgff7b885">Power users describe their setup</h2>
<div class="outline-text-2" id="text-orgff7b885">
<p>
In the following documents, the authors describe the details of
their setup, along with the workflows they use to get organized with
Org-mode.  While as a beginner you probably should start with only a
simple setup, these descriptions will be a fantastic source of
inspiration once you start growing your use of Org-mode.
</p>
<ul class="org-ul">
<li><a href="http://newartisans.com/2007/08/using-org-mode-as-a-day-planner">Using Org-mode as a day planner</a> by <a href="http://johnwiegley.com">John Wiegley</a> shows how to use
Org-mode after the fashion of a pen-and-paper day planner.</li>

<li><a href="http://members.optusnet.com.au/~charles57/GTD/gtd_workflow.html">How I use Emacs and Org-mode to implement GTD</a> by <a href="http://members.optusnet.com.au/~charles57/GTD/">Charles Cave</a>
shows one method of doing GTD with org-mode and covers (among
other things) categories, effort estimates, tags, scheduling, and
custom agenda commands.</li>

<li><a href="http://doc.norang.ca/org-mode.html">Organize Your Life In Plain Text!</a> by Bernt Hansen describes how to
use Org-mode to track and clock everything you work on.</li>
</ul>
</div>
</div>

<div id="outline-container-org2de6cdb" class="outline-2">
<h2 id="org2de6cdb">Tutorials on specific features</h2>
<div class="outline-text-2" id="text-org2de6cdb">
</div>
<div id="outline-container-org61e54a1" class="outline-3">
<h3 id="org61e54a1">Lists</h3>
<div class="outline-text-3" id="text-org61e54a1">
<ul class="org-ul">
<li>A short <a href="http://bzg.fr/org-playing-with-lists-screencast.html">screencast</a> presenting a few features of plain lists, by
Bastien.</li>
</ul>
</div>
</div>

<div id="outline-container-org1591c80" class="outline-3">
<h3 id="Spreadsheet">Tables, Spreadsheet, Plotting</h3>
<div class="outline-text-3" id="text-Spreadsheet">
<ul class="org-ul">
<li><a href="tables.html">A very short introduction to tables in Org-mode</a>, by Bastien.</li>

<li><a href="org-spreadsheet-intro.html">A very short introduction to Org as a spreadsheet system</a>, by
Bastien.</li>

<li><a href="org-spreadsheet-lisp-formulas.html">Using Emacs lisp for spreadsheet formulas</a> (<a href="org-tableur-tutoriel.html">french version</a>), by Bastien.</li>

<li><a href="https://github.com/novoid/org-mode-workshop/blob/master/featureshow/org-mode-teaser.org#1131-referencing-example-with-detailed-explanation">Various spreadsheet formulas with explanations how they work</a>
by Karl Voit.</li>

<li><a href="org-plot.html">Plotting tables in Org-Mode using org-plot</a> by Eric Schulte</li>

<li><a href="org-dot-diagrams.html">Plotting process diagrams or work flows in Org-Mode using dot</a> by Karl Voit</li>

<li><a href="http://www.youtube.com/watch?v=EQAd41VAXWo">Can your editor do this</a>, awesome little video showing how to create
HTML tables from an embedded Org-mode table.</li>

<li><a href="multitarget-tables.html">Using multiple-target tables and general formatting functions</a> by
<a href="http://claimid.com/ejr/">Jason Riedy</a>.</li>

<li><a href="http://www.hollenback.net/index.php/EmacsOrgTimestamps">Timestamps in Org and Calc</a>, how to calculate and display times in Org-mode by Phil Hollenback</li>

<li><a href="org-lookups.html">Table lookup functions</a> by Jarmo Hurri</li>

<li>The following are not tutorials but listed here somehow for
"completeness" of the information sources to be checked too:
<ul class="org-ul">
<li><a href="https://orgmode.org/manual/The-spreadsheet.html">Org manual, section about spreadsheet</a></li>

<li><a href="https://orgmode.org/worg/org-faq.html#Tables">Worg FAQ, section about tables</a></li>

<li><a href="https://orgmode.org/worg/org-hacks.html#Tables">Worg hacks, section about tables</a></li>

<li><a href="https://code.orgmode.org/bzg/org-mode/raw/master/testing/lisp/test-org-table.el">most of the automated Emacs Regression Tests (ERT) for Org tables</a></li>
</ul></li>
</ul>
</div>
</div>

<div id="outline-container-orgd7662e2" class="outline-3">
<h3 id="orgd7662e2">Dates and Times</h3>
<div class="outline-text-3" id="text-orgd7662e2">
<ul class="org-ul">
<li><a href="http://members.optusnet.com.au/~charles57/GTD/org_dates/">Using Dates and Times in Emacs Org-mode</a> by <a href="http://members.optusnet.com.au/~charles57/GTD/">Charles Cave</a>.</li>

<li><a href="http://sachachua.com/wp/2007/12/30/clocking-time-with-emacs-org/">Clocking time with Emacs Org</a> by <a href="http://sachachua.com/wp/">Sacha Chua</a>.</li>
</ul>
</div>
</div>

<div id="outline-container-org5ddb73a" class="outline-3">
<h3 id="org5ddb73a">Tags, Properties, and Column View</h3>
<div class="outline-text-3" id="text-org5ddb73a">
<ul class="org-ul">
<li><a href="http://sachachua.com/wp/2008/01/04/tagging-in-org-plus-bonus-code-for-timeclocks-and-tags/">Tagging in Org</a> by <a href="http://sachachua.com/wp/">Sacha Chua</a>.</li>

<li><a href="http://thread.gmane.org/gmane.emacs.orgmode/5107/focus=5134">What's the use of Column View?</a> by Christian Egli is a short tutorial
about Column View that was sent to <a href="http://news.gmane.org/gmane.emacs.orgmode">emacs-orgmode@gnu.org</a>.</li>

<li><a href="org-column-view-tutorial.html">Emacs Org's Column View</a> by <a href="http://bzg.fr">Bastien</a>, with an accompanying <a href="http://emacs-doctor.com/org-column-screencast.html">screencast</a>.</li>
</ul>
</div>
</div>

<div id="outline-container-org3a73350" class="outline-3">
<h3 id="org3a73350">Remember</h3>
<div class="outline-text-3" id="text-org3a73350">
<ul class="org-ul">
<li><a href="http://members.optusnet.com.au/~charles57/GTD/remember.html">Remember mode tutorial</a> by <a href="http://members.optusnet.com.au/~charles57/GTD/">Charles Cave</a>.</li>

<li><a href="http://sachachua.com/wp/2007/10/05/remembering-to-org-and-planner/">Remembering to Org and Planner</a> by <a href="http://sachachua.com/wp/">Sacha Chua</a>.</li>
</ul>
</div>
</div>

<div id="outline-container-org57ff978" class="outline-3">
<h3 id="org57ff978">Capture</h3>
<div class="outline-text-3" id="text-org57ff978">
<ul class="org-ul">
<li><a href="org-protocol-custom-handler.html">Defining custom handlers for use with org-protocol</a> by Sebastian Rose</li>

<li><a href="http://members.optusnet.com.au/~charles57/GTD/datetree.html">Capture mode  and date trees in org-mode</a> by <a href="http://members.optusnet.com.au/~charles57/GTD/">Charles Cave</a>.</li>
</ul>
</div>
</div>

<div id="outline-container-orge7d1793" class="outline-3">
<h3 id="orge7d1793">Agenda and search</h3>
<div class="outline-text-3" id="text-orge7d1793">
<ul class="org-ul">
<li><a href="org-custom-agenda-commands.html">Using custom agenda commands</a> by Matt Lundin</li>

<li><a href="advanced-searching.html">Advanced searching</a> by Matt Lundin</li>

<li><a href="../agenda-optimization.html">Agenda speed up and optimization</a> by Bastien</li>

<li><a href="agenda-filters.html">Agenda filters and limits</a> by Bastien</li>
</ul>
</div>
</div>

<div id="outline-container-orgdb5123b" class="outline-3">
<h3 id="orgdb5123b">Customization</h3>
<div class="outline-text-3" id="text-orgdb5123b">
<ul class="org-ul">
<li><a href="org-customize.html">Using customize to find and set options</a> by Carsten Dominik.</li>
<li><a href="org-appearance.html">Customizing Org appearance</a></li>
</ul>
</div>
</div>

<div id="outline-container-org1118275" class="outline-3">
<h3 id="org1118275">Export and Publishing</h3>
<div class="outline-text-3" id="text-org1118275">
<ul class="org-ul">
<li><a href="org-publish-html-tutorial.html">Publishing Org-mode files to HTML</a>, covering the basics of publishing
to HTML, by Sebastian Rose.</li>
<li><a href="org-publish-layersmenu.html">Phplayersmenu and HTML publishing</a>, shows how to create and maintain JavaScript
menus (Phplayermenu) for HTML export, by Sebastian Rose.</li>
<li><a href="images-and-xhtml-export.html">Images and XHTML export</a>, shows simple image handling in HTML export, by
Sebastian Rose.</li>
<li><a href="org-taskjuggler.html">Creating Gantt charts by exporting to TaskJuggler</a>, explains the usage of
the TaskJuggler exporter.  There is a Serbo-Croatian translation <a href="org-taskjuggler-scr.html">here</a> by
Jovana Milutinovich.</li>
<li><a href="org-latex-export.html">Using the OLD LaTeX exporter</a> introduces configuration topics for
users of Org Mode &lt; 8.0.</li>
<li><a href="org-latex-preview.html">Some notes on previewing LaTeX fragments</a>.</li>
<li><a href="org-google-sync.html">Syncing with Google Calendar</a></li>
<li><a href="http://www.youtube.com/watch?v=1-dUkyn_fZA">Demonstration of Org-mode as a tool for reproducible research</a> by John Kitchin
at SciPy 2013.</li>
<li>Write your book in Org-mode, and publish it with <a href="http://leanpub.com">Leanpub</a> and the <a href="http://juanreyero.com/open/ox-leanpub/index.html">ox-leanpub exporter</a>.</li>
</ul>
</div>
</div>

<div id="outline-container-orgc94ee74" class="outline-3">
<h3 id="orgc94ee74">Reproducible research</h3>
<div class="outline-text-3" id="text-orgc94ee74">
<p>
A talk by <a href="http://www.cheme.cmu.edu/people/faculty/jkitchin.htm">John Kitchin</a> at <a href="http://conference.scipy.org/scipy2013/">SciPy 2013</a>. In his truly amazing talk
<a href="http://www.youtube.com/watch?v=1-dUkyn_fZA">Emacs + org-mode + python in reproducible research</a>, John shows off
the capabilities of Org mode for reproducible research and
authoring.  This may be the best demonstration yet on this subject.
</p>
</div>
</div>
<div id="outline-container-org8806b6a" class="outline-3">
<h3 id="org8806b6a">Import</h3>
<div class="outline-text-3" id="text-org8806b6a">
<ul class="org-ul">
<li><a href="org-import-rtm.html">Importing from remember the milk</a></li>
</ul>
</div>
</div>

<div id="outline-container-org842c618" class="outline-3">
<h3 id="org842c618">Dependencies between tasks</h3>
<div class="outline-text-3" id="text-org842c618">
<ul class="org-ul">
<li><a href="http://karl-voit.at/2016/12/18/org-depend/">Karl Voit on how he is using org-depend.el</a></li>
</ul>
</div>
</div>
</div>

<div id="outline-container-orge78b1f1" class="outline-2">
<h2 id="orge78b1f1">Special tasks</h2>
<div class="outline-text-2" id="text-orge78b1f1">
</div>
<div id="outline-container-org352f77d" class="outline-3">
<h3 id="org352f77d">Natural Project Planning</h3>
<div class="outline-text-3" id="text-org352f77d">
<ul class="org-ul">
<li><a href="http://members.optusnet.com.au/~charles57/GTD/">Charles Cave</a> about using Org-mode to implement <a href="http://members.optusnet.com.au/~charles57/GTD/Natural_Project_Planning.html">Natural Project
Planning</a> according to David Allen.</li>
</ul>
</div>
</div>

<div id="outline-container-orgb0c504e" class="outline-3">
<h3 id="orgb0c504e">Tracking Habits</h3>
<div class="outline-text-3" id="text-orgb0c504e">
<ul class="org-ul">
<li><a href="tracking-habits.html">Tracking habits with org-mode</a>, by Matt Lundin.</li>
</ul>
</div>
</div>

<div id="outline-container-org0dc49e6" class="outline-3">
<h3 id="org0dc49e6">Measuring Personal Effectiveness</h3>
<div class="outline-text-3" id="text-org0dc49e6">
<ul class="org-ul">
<li><a href="org-effectiveness.html">Org Effectiveness Tutorial</a></li>
</ul>
</div>
</div>
<div id="outline-container-org0c53327" class="outline-3">
<h3 id="org0c53327">Using version Control with Your org files</h3>
<div class="outline-text-3" id="text-org0c53327">
<ul class="org-ul">
<li><a href="org-vcs.html">Using version control with your org files</a>, by Ian Barton.</li>
<li>Use <a href="https://github.com/simonthum/git-sync">git-sync</a> (disclaimer: my script) if you have a git repo of your own
somewhere in the interclouds.</li>
<li>Use <a href="http://git-annex.branchable.com/sync/">git-annex</a> for even more decentralized sync and/or heavier workloads.</li>
<li><a href="http://karl-voit.at/2014/08/20/org-losses-determining-post-commit/">Prevent losing collapsed Org lines by mistake</a> by Karl Voit
<ul class="org-ul">
<li>A post-commit hook generates a warning on your agenda if more than
xxx lines were removed.</li>
</ul></li>
</ul>
</div>
</div>

<div id="outline-container-org575a8cd" class="outline-3">
<h3 id="org575a8cd">How to use jsMath with org-mode</h3>
<div class="outline-text-3" id="text-org575a8cd">
<ul class="org-ul">
<li><a href="org-jsmath.html">How to use jsMath with org-mode</a>, by Darlan Cavalcante Moreira.</li>
</ul>
</div>
</div>

<div id="outline-container-org54ae39b" class="outline-3">
<h3 id="org54ae39b">Creating a Blog with Jekyll and org</h3>
<div class="outline-text-3" id="text-org54ae39b">
<ul class="org-ul">
<li>How to create a <a href="org-jekyll.html">blog</a> with Jekyll.</li>
<li><a href="http://juanreyero.com/open/org-jekyll/index.html">Exporting your blog with org-jekyll</a> (a different approach).</li>
</ul>
</div>
</div>

<div id="outline-container-org666e5d2" class="outline-3">
<h3 id="org666e5d2">Creating Beamer presentations</h3>
<div class="outline-text-3" id="text-org666e5d2">
<ul class="org-ul">
<li>A <a href="../exporters/beamer/ox-beamer.html">tutorial</a> for the new (org version 8.x) exporter, by Suvayu Ali.</li>
<li>Here is a <a href="org-beamer/tutorial.html">tutorial</a> for the <i>old</i> exporter (org v7.x), by Eric S. Fraga.</li>
<li>Also available is a <a href="http://www.youtube.com/watch?v=Ho6nMWGtepY&amp;feature=player_embedded">YouTube video</a> by Shulei Zhu, demonstrating the
whole process.</li>
</ul>
</div>
</div>
<div id="outline-container-org2cb26ea" class="outline-3">
<h3 id="org2cb26ea">Creating Non-Beamer presentations</h3>
<div class="outline-text-3" id="text-org2cb26ea">
<ul class="org-ul">
<li>A simple <a href="non-beamer-presentations.html">tutorial</a> by Eric Schulte</li>
</ul>
</div>
</div>

<div id="outline-container-orgfb9603b" class="outline-3">
<h3 id="orgfb9603b">Keeping up with your team's tasks</h3>
<div class="outline-text-3" id="text-orgfb9603b">
<p>
A setup that makes it easy to <a href="http://juanreyero.com/article/emacs/org-teams.html">keep up with the work</a> of several
people, packaged as org-secretary.el in contrib.
</p>
</div>
</div>
<div id="outline-container-org4f4c418" class="outline-3">
<h3 id="org4f4c418">Tracking tasks through a series of meetings</h3>
<div class="outline-text-3" id="text-org4f4c418">
<p>
This tutorial describes a workflow for running a series of
meetings, for example of a commission or any other group, and for
keeping track of the groups tasks.  <a href="org-meeting-tasks.html">Link to the tutorial</a>.
</p>
</div>
</div>
<div id="outline-container-org91e74c7" class="outline-3">
<h3 id="org91e74c7">Weaving a budget with Org and ledger</h3>
<div class="outline-text-3" id="text-org91e74c7">
<p>
<a href="weaving-a-budget.html">This tutorial</a> describes how to use Org and <a href="http://www.ledger-cli.org">ledger</a> to manage your
budget.
</p>
</div>
</div>

<div id="outline-container-org4bcab4f" class="outline-3">
<h3 id="org4bcab4f">Managing your web bookmarks</h3>
<div class="outline-text-3" id="text-org4bcab4f">
<ul class="org-ul">
<li><a href="http://karl-voit.at/2014/08/10/bookmarks-with-orgmode/">Simple method by Karl Voit</a></li>
</ul>
</div>
</div>

<div id="outline-container-org4320b02" class="outline-3">
<h3 id="org4320b02">Contact management</h3>
<div class="outline-text-3" id="text-org4320b02">
<ul class="org-ul">
<li><a href="http://karl-voit.at/2015/02/01/muttfilter/">Per-contact FROM-email Addresses for Users Of mutt and org-contacts.el</a> by Karl Voit
<ul class="org-ul">
<li>Although he is using mutt as email software, the method can be
easily adapted for many other email tools.</li>
</ul></li>
</ul>
</div>
</div>

<div id="outline-container-org978705d" class="outline-3">
<h3 id="org978705d">Contributing your package through Melpa + GitHub</h3>
<div class="outline-text-3" id="text-org978705d">
<p>
Want to contribute ?
GitHub + MELPA + Worg is a popular way to publish your contribution.
</p>

<p>
<a href="melpa-github.html">Contribute through Melpa + GitHub + Worg</a>
</p>
</div>
</div>
</div>

<div id="outline-container-org26816d5" class="outline-2">
<h2 id="org26816d5">Personal Setup</h2>
<div class="outline-text-2" id="text-org26816d5">
<p>
See also 
</p>

<ul class="org-ul">
<li><a href="http://sachachua.com/wp/">Sacha Chua</a> about <a href="http://sachachua.com/wp/2007/12/22/a-day-in-a-life-with-org/">A day in a life with Org</a> and about the basics of
<a href="http://sachachua.com/wp/2007/12/28/emacs-getting-things-done-with-org-basic/">Getting Things Done with Org</a></li>

<li>David O'Toole explains his setup in <a href="http://thread.gmane.org/gmane.emacs.orgmode/4832">this post</a>.</li>

<li>This <a href="http://www.brool.com/?p=82">blog post</a> shows a very simple and clear GTD setup.</li>

<li>Manuel Hermenegildo describes his <a href="http://thread.gmane.org/gmane.emacs.orgmode/6701/focus=6732">Setup for collaborative work
using Org</a>.</li>

<li>Jan Böcker describes his approach to <a href="http://www.jboecker.de/2010/04/14/general-reference-filing-with-org-mode.html">general reference filing</a> with
org-mode.</li>
</ul>
</div>
</div>

<div id="outline-container-orgd92f738" class="outline-2">
<h2 id="orgd92f738">Screencasts</h2>
<div class="outline-text-2" id="text-orgd92f738">
<p>
See the <a href="org-screencasts/index.html">Screencasts</a> page for a complete list of Org-mode screencasts.
</p>
</div>
</div>

<div id="outline-container-orgabae562" class="outline-2">
<h2 id="orgabae562">Features waiting for tutorials</h2>
<div class="outline-text-2" id="text-orgabae562">
<ul class="org-ul">
<li>The Clock Table</li>
<li>Sparse Trees</li>
<li>Hyperlinks</li>
<li>Using TODO states</li>
<li>Using TAGS</li>
<li>Embedded LaTeX</li>
<li>Using orgtbl-mode in LaTeX</li>
<li>Capture</li>
</ul>
</div>
</div>

<div id="outline-container-org3cfa1c6" class="outline-2">
<h2 id="org3cfa1c6">Org-related pages by Tutorial authors</h2>
<div class="outline-text-2" id="text-org3cfa1c6">
<p>
Here are the pages of a number of people that write for or about
Org-mode:
</p>

<ul class="org-ul">
<li><a href="http://www.newartisans.com">John Wiegley</a></li>

<li><a href="http://members.optusnet.com.au/~charles57/GTD/">Charles Cave</a></li>

<li><a href="http://sachachua.com/wp/">Sacha Chua</a></li>

<li><a href="http://karl-voit.at/tags/emacs/">Karl Voit</a></li>
</ul>
</div>
</div>
</div>
<div id="postamble" class="status">
<div id="show_source"><input type="button" value="Show Org source" onClick='show_org_source()'></div><div id="license"><p>Documentation from the orgmode.org/worg/ website (either in its HTML format or in its Org format) is licensed under the <a href="http://www.gnu.org/copyleft/fdl.html">GNU Free Documentation License version 1.3</a> or later.  The code examples and css stylesheets are licensed under the <a href="http://www.gnu.org/licenses/gpl.html">GNU General Public License v3</a> or later.</p></div>
</div>
</body>
</html>
