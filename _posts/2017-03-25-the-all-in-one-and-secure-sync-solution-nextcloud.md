---
ID: 1209
post_title: 'The all-in-one and secure sync solution: Nextcloud'
author: Mathias Renner
post_date: 2017-03-25 13:07:05
post_excerpt: ""
layout: post
permalink: >
  https://bitleaf.de/2017/03/25/the-all-in-one-and-secure-sync-solution-nextcloud/
published: true
---
Software that keeps your files, calendar, contacts and notes in sync across all your devices is one of the most used software type – for business as well as for private users. In this article I'll show one of the best-in-class sync solutions.

<!--more-->
<h3>High requirements: Open source, security, data sovereignty</h3>
When choosing a good sync software, I stick to my values of <em>sustainable IT as depicted </em><a href="https://bitleaf.de/home-english/#features">on the homepage next to this blog</a>. Most importantly, this implies:
<ul>
 	<li>Open source with the ability to host the software on your own server</li>
 	<li>High security on all layers (transport and storage)</li>
 	<li>Data sovereignty, i.e. full control over all data the software processes (esp. your business or personal data).</li>
</ul>
<p class="info-title">Proprietary sync services from Apple, Google, Microsoft, Dropbox etc. don't comply with several of these requirements because they incorporate security leaks intentionally. This has been shown by the leaked documents of Edward Snowden (<a href="https://www.eff.org/document/2013-06-06-wapo-prism">see one of the leaked documents as example here</a>).</p>

<h3 class="info-title">Found: Nextcloud</h3>
The software project "Nextcloud" (former: "OwnCloud") meets all the mentioned requirements. It has been <a href="https://nextcloud.com/wp-content/themes/next/assets/files/NCC_report_full.pdf">audited by an external security specialist</a> with very good results.

Nextcloud provides sync capabilities for all important types of files:
<ul>
 	<li>Text files, Images, Videos etc.</li>
 	<li>Calendar</li>
 	<li>Contacts</li>
 	<li>Notes</li>
</ul>
... and even browser bookmarks after adding the according app from the Nextcloud app store. As long as there is an app, you can extend Nextcloud's capabilities to your needs.
<h3>Sync across all your devices</h3>
Nextcloud syncs your data across your Desktop, Smartphone, and server:
<ul>
 	<li>If you take a picture with your phone and then go to your computer, it will be there.</li>
 	<li>If you create a calendar event on your computer, it will be synced to your phone.</li>
 	<li>If you lost your phone - don't worry about your data! Your data is still on the server and on your Desktop.</li>
</ul>
<h3>All-in-one, but not best-in-all</h3>
As it is often the case with software that tries to provide many different features at once, not all features of Nextcloud are reliable. Noticeable is its file sync component, which in my experience sometimes causes errors (this is also reflected by <a href="https://github.com/nextcloud/server/issues?utf8=%E2%9C%93&amp;q=is%3Aissue+sync+error">corresponding bugs on GitHub.com</a>). If you look for a rock-solid file sync solution, I highly recommend <a href="https://www.seafile.com/en/home/">Seafile</a>, which – in contrast – focuses on file sync only.

Luckily, all other components of Nextcloud such as calendar or contact sync work very well. So if you won't use Nextcloud for thousands of files, it does a good job for most of the basic sync tasks many people need. If you're sure that you'll never use file sync, you could also stick to <a href="http://sabre.io/baikal/">Baikal</a>, which focuses on calendar, contact &amp; note sync only.

In contrast to Baikal or Seafile, Nextcloud's community is much larger and therefore its support in e.g. software that simplifies installing Nextcloud on a server is higher as well. For instance, the popular installer Softaculous only contains Nextcloud instead of Baikal or Seafile. Softaculous simplifies the way to install Nextcloud on a server a lot, so this fact is especially interesting for those who are no IT geeks.
<h3>Installation and usage</h3>
Nextcloud can be installed on a server that is owned by you (requirement of data sovereignty). If you don't have an own server, you have two options:
<ul>
 	<li>get a server package, which starts at 55 Cents per month (<a href="https://wircon-int.net/aff.php?aff=171">at Wint.Global</a>, <span style="text-decoration: underline;">and even includes an own domain and email address!)</span></li>
 	<li>get a Nextcloud account on a foreign server.</li>
</ul>
I recommend getting an own server package since many Nextcloud accounts are provided in a non-secure environment.

After you've setup Nextcloud on a server, download Nextcloud's sync apps to your computer and your phone, which then can connect to the Nextcloud on your server. Afterwards, enjoy your own and secure sync infrastructure!

To eventually gain a high level of security, it's required to setup SSL and check if the server environment is secure. If you need help during any of the setup and configuration, <a href="https://bitleaf.de/home-english/#contact">you can always request my professional help</a>, of course.
<h3>Proceed with secure chat messaging</h3>
Nextcloud does not offer secure chat messaging. If you want to chat with your friends and business contacts on a higher security and privacy level than with any of the claimed "secure" messengers such as <em>What'sapp</em>, <em>Telegram,</em> <em>TextSecure or</em> <em>Threema,</em> have a look at at XMPP in <a href="https://bitleaf.de/2016/11/28/setup-a-whatsapp-like-chat-messaging-that-respects-your-privacy-in-just-10-minutes/">this blog article</a>. It's super easy to setup – it's just up to you to leverage it!

&nbsp;