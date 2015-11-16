---
ID: 427
post_title: This Is An Awesome Page For You
author:
  - 'a:1:{i:0;s:8:"cgrymala";}'
post_date:
  - 'a:1:{i:0;s:19:"2015-11-13 11:41:11";}'
post_excerpt:
  - 'a:1:{i:0;s:0:"";}'
layout: page
permalink:
  - 'a:1:{i:0;s:33:"/this-is-an-awesome-page-for-you/";}'
published: true
---
[caption id="attachment_428" align="alignright" width="225"]<img class="size-medium wp-image-428" src="http://umwwebmaster.staging.wpengine.com/wp-content/uploads/2015/11/5589665399_5d67bc6484_o-225x300.jpg" alt="" width="225" height="300" /> Adding a happy little photo to the awesome page. After all, everything is awesome![/caption]

This is going to be the greatest page ever published, since it was created inside of Atom and then pushed to our GitHub repo, which will then automatically sync it to our WordPress installation.

Doesn't that sound like an awesome concept?
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