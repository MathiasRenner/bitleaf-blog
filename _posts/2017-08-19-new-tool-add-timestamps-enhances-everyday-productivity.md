---
ID: 1325
post_title: 'New tool &#8222;Add timestamp to files&#8220; enhances productivity in KDE &#038; Dolphin'
author: Mathias Renner
post_excerpt: ""
layout: post
permalink: >
  https://bitleaf.de/2017/08/19/new-tool-add-timestamps-enhances-everyday-productivity/
published: true
post_date: 2017-08-19 15:06:27
---
Today, I am proud to share a new open source tool that I just created: It adds timestamps to files. Yes, simply, but mighty!

<!--more-->

This piece of software lets the standard file manager of KDE, i.e. Dolphin, add timestamps to files. If you look for this functionality in GNOME with its default file manager Nautilus, see <a href="https://bitleaf.de/2018/05/01/new-tool-add-timestamp-to-files-enhances-productivity-in-gnome-nautilus/">this blog post</a>.

It's as simply as it sounds: Say you have a file <strong>my-file.pdf</strong>, the tool adds a timestamp in front of the file name and produces: <strong>2017-08-19-my-file.pdf</strong>. To do so, you just right click on a file and choose which timestamp you prefer:

<img class="size-full wp-image-1329 aligncenter" src="https://bitleaf.de/wp-content/uploads/2017/08/2017-08-19-add-timestamp-v0-2.png" alt="" width="351" height="103" />

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
<h3>How can I use it?</h3>
Well, everyone that uses Linux and the Dolphin file manager (included e.g. in the KDE desktop environment) can just download and install it. You find <a href="https://github.com/bitleaf/kde5-dolphin-service-menu-add-timestamp">installation instructions here</a>, and community feedback as well as usage statistics should appear in the <a href="https://store.kde.org/p/1187645/">KDE store</a> (hopefully soon).
<h3>My first KDE contribution – please provide feedback!</h3>
I am especially happy to have contributed to the KDE community that very much matches my own ideals about free and open software. I am very happy to get your feedback and see how to improve this little tool.

In the future of Linux desktop environments, we'll probably see only two major ones: GNOME and KDE – so I expect to help quite a few people with this simple but handy tool. Enjoy!