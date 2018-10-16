---
ID: 1806
post_title: >
  Why Matrix is the most interesting
  messaging solution today
author: Mathias Renner
post_excerpt: 'You look for alternatives to Whatsapp, Telegram, Threema, Wire, Signal & Co? Recently I did some research about a viable alternative and found one: Matrix.'
layout: post
permalink: >
  https://bitleaf.de/2018/10/16/why-matrix-is-the-most-interesting-messaging-solution-today/
published: true
post_date: 2018-10-16 17:16:55
---
<!-- wp:paragraph -->
<p>You look for alternatives to Whatsapp, Telegram, Threema, Wire, Signal &amp; Co? Recently I did some research about a viable alternative and found one: Matrix.<br/></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>I'll explain my view such that everyone can understand it – including the ones who have zero knowledge about IT. Thus, I will simplify many technical concepts, which at some reduce the technical correctness. I rather have everyone, i.e. all the people, being able to follow my thoughts instead of just a small group of IT experts.<br/></p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>What distinguishes a good messaging app?</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>To me, a good messaging meets the following requirements:</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>100% <a href="https://en.wikipedia.org/wiki/Free_and_open-source_software#FLOSS">FLOSS</a>, i.e. free and open source software, equals to not proprietary".<br/></li><li><a href="http://End-to-end%20encryption">End-to-end encryption</a> for 1-to-1 chat as well as group chat, and regular security audits by third parties<br/></li><li>It should work reliably under common conditions, i.e. no messages losses even devices are sometimes not online.<br/></li><li>Simple to use for everyone, not only IT geeks<br/></li><li>Compatible messaging apps for users should exist for all common operating systems, i.e. at least Android, iOS, Windows, macOS and Linux</li><li><a href="https://en.wikipedia.org/wiki/Decentralization">Decentralized architecture</a>, i.e. the server components are geospatially highly distributed and their operators can be anyone. This is contrary to Whatsapp, which is operated by a single legal entity. Decentralization does substantially reduces the dependency and control from a single entity.<br/></li><li>Based on an open <a href="https://en.wikipedia.org/wiki/Specification_(technical_standard)">specification or standard</a>, such that new software pieces can be added as long they stick to the specification. This simplifies extending the software for developers.<br/></li><li>Active development with a large community of developers and users, i.e. many people contribute to that software and regularly maintain and improve it.<br/></li><li>No ads and no tracking by default. Ads most of the time require tracking, and tracking itself is a method to aggregate user data to eventually sell it.<br/></li><li>Anonymous user account possible. This supports freedom.<br/></li></ul>
<!-- /wp:list -->

<!-- wp:paragraph -->
<p>Other requirements like multi-language support are the result deducted of these requirements.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>Why are all these requirements so important?</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Is it really necessary? Fully FLOSS, decentralized, end-to-end encryption, no tracking... Why do some geeks like me make such high demands? In answered this question in <a href="https://bitleaf.de/2018/07/28/warum-jeder-etwas-zu-verbergen-hat/">this blog post:</a></p>
<!-- /wp:paragraph -->

<!-- wp:embed {"url":"https://bitleaf.de/2018/07/28/why-everyone-has-something-to-hide/","type":"wp-embed","providerNameSlug":"bitleaf-sustainable-it-solutions","className":"wp-has-aspect-ratio wp-embed-aspect-1-1"} -->
<figure class="wp-block-embed is-type-wp-embed is-provider-bitleaf-sustainable-it-solutions wp-has-aspect-ratio wp-embed-aspect-1-1"><div class="wp-block-embed__wrapper">
https://bitleaf.de/2018/07/28/why-everyone-has-something-to-hide/
</div></figure>
<!-- /wp:embed -->

<!-- wp:paragraph -->
<p>In summary, when you use Whatsapp or similar apps, you allow companies to understand you. How? Because the operator of Whatsapp (facebook Inc.) aggregates data about you. It's not FLOSS, so you can't do much about it. And it's not decentralized, but centralized. Thus, data of how you use Whatsapp is in the hands of a single company, facebook Inc. Thereby Facebook can create lots of knowledge about you.<br/>End-to-end-encryption? No hurdle, metadata has enough information to draw a very detailed picture of your personality. Besides, this encryption can be weakened. Remember, facebook Inc. has full control on the software!<br/><br/>Unfortunately, it's not only the software a company is in control of, but also its users. First, your data will be used to show ads. But next, knowing your personality and political interests and opinions, everyone of us can be manipulated without even recognizing it. Applied techniques are so subtle that your consciousness won't notice. I know, it sounds scary, but it let's face the reality.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>The following statement summarizes the argumentation:<br/></p>
<!-- /wp:paragraph -->

<!-- wp:quote -->
<blockquote class="wp-block-quote"><p>The influence of companies or institutions correlates with the amount of data they have on individuals. Large amounts of data make it possible to understand individuals so well that they become controllable. Thus, the freedom of individuals can be restricted when they release much of their data.</p><cite>Source: <a href="https://bitleaf.de/2018/07/28/why-everyone-has-something-to-hide/">this blog post</a></cite></blockquote>
<!-- /wp:quote -->

<!-- wp:paragraph -->
<p>I'd be glad if you are now interested in trying to understand the background for my statement in the other blog post :-)<br/></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>All in all, a messaging app, which meets the requirements stated above at least reduces the probability that user data gets in the hand of powerful entities. <br/></p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>My preferred solution: Matrix and its ecosystem</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p><a href="https://matrix.org">Matrix</a> is the solution I currently prefer because it meets all the requirements stated above. Matrix is actually just a <a href="https://matrix.org/docs/guides/faq.html">standard</a> that can be used to exchange messages. Thus you need a messaging app called "<a href="https://matrix.org/docs/projects/client/riot.html">Riot</a>" on your computer or phone to type and send messages, similar to Whatsapp. Evenly important: Riot is simple enough to use, even if not as simple as Whatsapp.<br/></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>In addition you need a server component in the cloud. The server component holds all data of the messaging app, i.e. your contacts, chat history etc. Beginners should use the default server component provided by matrix.org. Advanced users should use a server <a href="https://www.hello-matrix.net/public_servers.php">of this list</a>  or host an own server. An advantage of Matrix compared to e.g. <a href="https://de.wikipedia.org/wiki/XMPP">XMPP</a> is the simple setup of the server component, which is mentioned <a href="https://www.kuketz-blog.de/messenger-matrix-das-xmpp-fuer-hobby-admins/">here</a>.<br/></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>I am happy that also governments, here: the French government, has chosen Matrix as secure communication app:</p>
<!-- /wp:paragraph -->

<!-- wp:quote -->
<blockquote class="wp-block-quote"><p>France confirms that Matrix (and Riot) is the basis for their upcoming secure communication app for official government use, and will be 100% FOSS! Exciting times :D</p><cite>Source: <a href="https://twitter.com/matrixdotorg/status/989514267408912385?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E989514267408912385&amp;ref_url=https%3A%2F%2Fbitleaf.de%2F2018%2F10%2F16%2Fwhy-matrix-is-the-most-interesting-messaging-solution-today%2F">Twitter tweet</a></cite></blockquote>
<!-- /wp:quote -->

<!-- wp:heading {"level":3} -->
<h3>Why Matrix, not….<br/></h3>
<!-- /wp:heading -->

<!-- wp:list -->
<ul><li><a href="https://briarproject.org/">Briar</a>: FLOSS, decentralized (<a href="https://en.wikipedia.org/wiki/Peer-to-peer">peer-to-peer</a>), supports only text messages (no pictures), only Android support.</li><li><a href="https://delta.chat/">Delta Chat</a>: FLOSS, decentralized, feature-wise limited (based on email), only Android support.</li><li><a href="https://de.wikipedia.org/wiki/Telegram_Messenger">Telegram</a>: server component is not FLOSS, not decentralized.</li><li><a href="https://de.wikipedia.org/wiki/Threema">Threema</a>: not FLOSS, not decentralized.</li><li><a href="https://de.wikipedia.org/wiki/KakaoTalk">KakaoTalk</a>: not FLOSS, not decentralized.<br/></li><li><a href="https://ring.cx/">Ring</a>: FLOSS, decentralized (<a href="https://en.wikipedia.org/wiki/Peer-to-Peer">peer-to-peer</a>), no group chats.</li><li><a href="https://signal.org/">Signal</a>: FLOSS, not decentralized.</li><li><a href="https://silence.im/">Silence</a>: FLOSS, not decentralized. uses SMS/MMS-Service, bound to phone number</li><li><a href="https://wiki.ubuntuusers.de/Tox/">TOX</a>: FLOSS, decentralized (<a href="https://en.wikipedia.org/wiki/Peer-to-Peer">peer-to-peer</a>), no group chat on Android.<br/></li><li><a href="https://de.wikipedia.org/wiki/WhatsApp">WhatsApp</a>: not FLOSS, not decentralized.<br/></li><li><a href="https://de.wikipedia.org/wiki/XMPP">XMPP</a> (= the protocol with e.g. Conversations or ChatSecure as client app): FLOSS, decentralized, not reliable (message losses)</li><li><a href="https://allo.google.com/">Google Allo</a>: not FLOSS, not decentralized.<br/></li><li><a href="https://de.wikipedia.org/wiki/IMessage">iMessage</a>: not FLOSS, not decentralized.<br/></li><li><a href="https://www.messenger.com/">Facebook Messenger</a>: not FLOSS, not decentralized.<br/></li><li><a href="https://wire.com/">Wire</a>: FLOSS, not decentralized.</li><li><a href="https://get.hike.in/">Hike</a>: not FLOSS, not decentralized.<br/></li><li><a href="https://hangouts.google.com/">Google Hangouts</a>: not FLOSS, not decentralized.<br/></li></ul>
<!-- /wp:list -->

<!-- wp:paragraph {"fontSize":"regular"} -->
<p class="has-regular-font-size">This nice list has been initially created by Roland Hummel under license CC BY-SA and published <a href="https://www.kuketz-blog.de/messenger-matrix-das-xmpp-fuer-hobby-admins/">here</a>. I translated it to English and added some more messengers.<br/></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"fontSize":"regular"} -->
<p class="has-regular-font-size">If you'd like to compare some of the more interesting messengers in detail, look at the comparison matrix <a href="https://wiki.piratenpartei.de/Datei:Messengermatrix.pdf">here</a>. Kudos to user <em>eska</em> for this nice work!</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":1813,"linkDestination":"custom"} -->
<figure class="wp-block-image"><a href="https://wiki.piratenpartei.de/Datei:Messengermatrix.pdf"><img src="https://bitleaf.de/wp-content/uploads/2018/10/messenger-apps-comparison-matrix.png" alt="" class="wp-image-1813"/></a><figcaption>Comparison of several messaging apps, created by <em>eska</em></figcaption></figure>
<!-- /wp:image -->

<!-- wp:heading {"level":3} -->
<h3>How can I use Matrix?<br/></h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p><a href="https://bitleaf.de/2018/10/15/how-to-use-riot-and-matrix/">This blog post</a> explains everything how to get started.<br/></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>I am happy to receive your thoughts and experience about Matrix! Please use the comments below for a discussion.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Licence of this article: <a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA</a> <br/></p>
<!-- /wp:paragraph -->