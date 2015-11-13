---
ID: 427
post_title: This Is An Awesome Page For You
author: cgrymala
post_date: 2015-11-13 11:41:11
post_excerpt: ""
layout: page
permalink: >
  http://umwwebmaster.staging.wpengine.com/this-is-an-awesome-page-for-you/
published: true
---
This is going to be the greatest page ever published, since it was created inside of Atom and then pushed to our GitHub repo, which will then automatically sync it to our WordPress installation.

Doesn't that sound like an awesome concept?

Some potential issues we might run into along the way:

* The page slug and the page title do not match. How will that be handled?
* There is no obvious way to include/upload images into a page through this process. That still has to be handled through WordPress
* People aren't going to understand Markdown syntax; it would be nice to find a full-featured Markdown editor somewhere along the line.
* People aren't going to understand how to use Git.
* We will need to investigate the possibility of managing post meta data, especially choosing an appropriate Genesis Page Layout when creating a new page.

Some positive aspects of this include:

1. People can edit their content from just about anywhere
1. We can more easily handle potential content conflicts, merging or optionally discarding bits and pieces of content within a page
1. Obviously, we can much more easily track who made what changes to a page, no matter which interface they use to make those changes
1. Infinite revisions can be stored, and potentially reverted
1. We have the potential to sync content more easily between production and staging sites (we would need to fork the repo to use it on a staging site)
1. We can potentially make multiple changes/commits locally before pushing the finalized produt to the site/remote repo
