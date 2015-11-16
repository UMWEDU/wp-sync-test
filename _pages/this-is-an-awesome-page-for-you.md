---
ID: 427
post_title: This Is An Awesome Page For You
author:
  - cgrymala
post_date:
  - 2015-11-13 11:41:11
post_excerpt:
  - ""
layout: page
permalink:
  - /this-is-an-awesome-page-for-you/
published: true
---
[caption id="attachment_428" align="alignright" width="225"]<img class="size-medium wp-image-428" src="http://umwwebmaster.staging.wpengine.com/wp-content/uploads/2015/11/5589665399_5d67bc6484_o-225x300.jpg" alt="" width="225" height="300" /> Adding a happy little photo to the awesome page. After all, everything is awesome![/caption]

This is going to be the greatest page ever published, since it was created inside of Atom and then pushed to our GitHub repo, which will then automatically sync it to our WordPress installation.

Doesn't that sound like an awesome concept? It certainly does, to me.<!--more-->
<h2>Some potential issues we might run into along the way:</h2>
<ul>
	<li>The page slug and the page title do not match. How will that be handled?</li>
	<li>There is no obvious way to include/upload images into a page through this process. That still has to be handled through WordPress</li>
	<li>People aren't going to understand HTML syntax; we may need to provide them with some sort of WYSIWYG HTML editor (the plugin does not appear to use MD syntax, even though it uses the MD file extension)</li>
	<li>People aren't going to understand how to use Git <em>(side note: If you push from a local source to the main remote repo, you then have to pull before doing anymore work)</em>.</li>
	<li>We will need to investigate the possibility of managing post meta data, especially choosing an appropriate Genesis Page Layout when creating a new page.</li>
</ul>
<h2>Some positive aspects of this include:</h2>
<ol>
	<li>People can edit their content from just about anywhere</li>
	<li>We can more easily handle potential content conflicts, merging or optionally discarding bits and pieces of content within a page</li>
	<li>Obviously, we can much more easily track who made what changes to a page, no matter which interface they use to make those changes</li>
	<li>Infinite revisions can be stored, and potentially reverted</li>
	<li>We have the potential to sync content more easily between production and staging sites (we would need to fork the repo to use it on a staging site)</li>
	<li>We can potentially make multiple changes/commits locally before pushing the finalized produt to the site/remote repo</li>
</ol>
<h2>Some things to investigate further</h2>
<ol>
	<li>Need to figure out how to properly manage custom post meta. While they plugin should automatically include "visible" (not prefixed by an underscore) meta data; it ignores all "hidden" meta data except for a few specific things.</li>
	<li>Need to look into the new features that allow you to choose specific branches of a repo so you can manage content on development/production sites separately and, theoretically, merge the branches when you're ready to push from development to production.</li>
	<li>Need to look more into the other options that are <a href="https://github.com/mAAdhaTTah/wordpress-github-sync/wiki/Customizing-WordPress-GitHub-Sync-with-Filters">available through filters in the plugin</a></li>
</ol>