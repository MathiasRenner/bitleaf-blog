---
ID: 1432
post_title: 'Tool &#8222;Add timestamp to files&#8220; enhances productivity in GNOME &#038; Nautilus'
author: Mathias Renner
post_excerpt: ""
layout: post
permalink: >
  https://bitleaf.de/2018/05/01/new-tool-add-timestamp-to-files-enhances-productivity-in-gnome-nautilus/
published: true
post_date: 2018-05-01 23:19:08
---
I am proud to share a new open source tool: It adds timestamps to files in the Nautilus file manager.<!--more-->

Recently, I <a href="https://bitleaf.de/2017/08/19/new-tool-add-timestamps-enhances-everyday-productivity/">published a tool with similar features</a> for the default file manager in KDE, i.e. Dolphin. Now, this piece of software lets the standard file manager of GNOME, i.e. Nautilus, add timestamps to files.
<h3>How does it work?</h3>
It's as simply as it sounds: Say you have a file <strong>my-file.pdf</strong>, the tool adds a timestamp in front of the file name and produces: <strong>2017-08-19-my-file.pdf</strong>. To do so, you just right click on a file and choose which timestamp you prefer:

<img class="aligncenter wp-image-1433 size-full" src="https://bitleaf.de/wp-content/uploads/2018/05/screenshot.png" alt="" width="739" height="498" />

Merely by that, it saves me lots of time in my everyday productivity – and I guess it helps many other people, too.
<h3>Why should I add timestamps to files?</h3>
To me, timestamps in file names are useful for two reasons:
<ul>
 	<li><strong>They easily communicate how old the information in the containing file is – in an easy to grasp manner</strong>, without having to take a look at the timestamp column in your file manager. That often requires to scroll to the right.</li>
 	<li><strong>They are transparent to any IT system:</strong> If you share the file via email, hard drive or the cloud, the timestamp in the filename will show up and persist in <strong>any</strong> IT system. However, if you open it in the web interface of a cloud service (e.g. Dropbox, Nextcloud etc.) or on another operating system, sometimes the timestamp shown there either changed, is displayed in a different format or is not displayed at all. The timestamps in the file name and its format persists.
They persist also if you move the file or restore a file from a backup, sometimes the timestamp of the file ("last modified") changes. If you think of images you took some years ago, they won't appear in your photo software as taken some years ago, but taken today. This happend to me a few times – annoying.</li>
</ul>
Of course, timestamps are not useful for all type of files. Files that are changed very often rather should go with a version control system or document management system etc.
Roughly, I recommend timestamps in file names for archived files (images, videos etc.) or files that are updated and shared just a few times.
<h3>How to use?</h3>
Well, everyone that uses Linux and the Nautilus file manager can just download and install it. You find <a href="https://github.com/bitleaf/nautilus-script-add-timestamp-to-files">installation instructions here</a>. Enjoy!