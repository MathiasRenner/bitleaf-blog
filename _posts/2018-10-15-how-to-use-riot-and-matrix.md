---
ID: 1760
post_title: >
  How to use the messenger app Riot in the
  Matrix fediverse
author: Mathias Renner
post_excerpt: >
  This is a documentation about how to get
  started using the messenger app Riot,
  which uses the Matrix protocol.
layout: post
permalink: >
  https://bitleaf.de/2018/10/15/how-to-use-riot-and-matrix/
published: true
post_date: 2018-10-15 13:48:31
---
<!-- wp:paragraph -->
<p>This is a documentation about how to get started using the messenger app Riot, which uses the Matrix protocol. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Why? First, because I think that <strong>Riot with Matrix is the "best" messaging solution for eveyone available today</strong>. Please see this blog post to reat more about what I mean by "best". Second, because I couldn't find a good user guide. <strong>This article should help everyone, not only IT geeks</strong> to simply start in the fediverse of Riot and Matrix.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>I am very happy to receive feedback for improvments. Please get in touch with me by using the comments at the bottom of the article or create a Github issue or pull request using the link at the end of this article.<br/></p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>
<strong>First,
create an account</strong></h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>1. Let's download the messaging app "Riot" on the device of your choice. Go to <a href="https://riot.im/">https://riot.im/</a> and download Riot for your operating system.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>2. Install Riot and start it. After startup it should look like this:</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":1761,"align":"center","width":501,"height":665} -->
<div class="wp-block-image"><figure class="aligncenter is-resized"><img src="https://bitleaf.de/wp-content/uploads/2018/10/riot-start.png" alt="" class="wp-image-1761" width="501" height="665"/></figure></div>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>3. Create an account by clicking on <strong>"Create an account</strong>" below the large "sign in" button and fill out the fields. Note that only a user name and password is mandatory. However, I recommend to provide your email address to allow password recovery.<br/>More advanced users should user a custom server, of course. In this article, I focus on the easiest way for beginners.<br/></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>4. If you provided an email address, <strong>go to your inbox</strong> and follow the instructions in the email you just received from Matrix.org</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>5. Close Riot and open it again such that you see the login masks. <strong>Type in your new credentials</strong> in the corresponding fields. Before you click "sign in", select "custom server" below the "sign in" button. It should look like this:</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":1762,"align":"center"} -->
<div class="wp-block-image"><figure class="aligncenter"><img src="https://bitleaf.de/wp-content/uploads/2018/10/identity-server-correct.png" alt="" class="wp-image-1762"/></figure></div>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>Now, make sure that the upper field holds "https://matrix.org/". Next, delete the content of the second field such that the field is just empty. "identity server" is a feature that you shouldn't use for privacy reasons. It also adds only little value.<br/></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>6. Login clicking on the "sign in" button. This may take up to 30 seconds. Afterwards, it should look like this:</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":1763} -->
<figure class="wp-block-image"><img src="https://bitleaf.de/wp-content/uploads/2018/10/riot-full-scree.png" alt="" class="wp-image-1763"/></figure>
<!-- /wp:image -->

<!-- wp:heading -->
<h2>Now let‘s start messaging!</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>
1.
First, you need a contact you‘d like to chat with. So ask a friend
to join :-) If you found a chat partner, click on the symbol on the
bottom left of the Riot window to start a new chat:</p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":1767,"align":"center"} -->
<div class="wp-block-image"><figure class="aligncenter"><img src="https://bitleaf.de/wp-content/uploads/2018/10/start-chat-arrow.png" alt="" class="wp-image-1767"/></figure></div>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>2. A new windows opens up. Here, you are asked to put in some ID to find your chat partner. For that a "Matrix-ID" is the best option to use. Your partner‘s and your own Matrix-ID has always the following format "#username:matrix.org". For example, if you registered your account with name "bigfanofmatrix", your Matrix-ID is "#bigfanofmatrix:matrix.org".</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Thus put in the Matrix-ID of your chat partner. Then click "start chat". It might take up to 30 seconds until the chat is initialized. Then you‘ll be able to start chatting to your partner!</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>3. Congrats! You now can start to communicating with a messenger that respects your provacy! Next, you can install Riot on more of your devices. Again, go to <a href="https://riot.im/">https://riot.im/</a>, download Riot for your operating system and log in with your new credentials. That‘s it!</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>
<strong>Let‘s
add encryption!</strong></h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>1. Until now, your conversation is unencrypted. Activate it by clicking on the gear button on the top right in the Riot app:<br/></p>
<!-- /wp:paragraph -->

<!-- wp:image {"id":1782,"align":"center","width":318,"height":220} -->
<div class="wp-block-image"><figure class="aligncenter is-resized"><img src="https://bitleaf.de/wp-content/uploads/2018/10/settings-arrow.png" alt="" class="wp-image-1782" width="318" height="220"/></figure></div>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>This should open the settings page. In the top half of that page, check the box saying "Enable encryption (warning: cannot be disabled again!)". Afterwards, click on "save" in the top right corner.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>2. Next, write a text message to your partner from all devices you've Riot installed on, and ask your partner to do the same from all of his devices.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>3. Some of the messages might not be readable or include warning. In this case should see a yellow sign with and exclamation mark next to your and/or your partner‘s messages. Click on it, which opens a new window. In that new window click on the button "verify..." at the bottom right. Finally, click on "I verify that the keys match" and close the window with "OK“.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>4. If the encryption is working properly, you should see a closed locker next to your recent chat messages. If you still see the yellow sign, just repeat step 2 and 3 until you see the locker as well.<br/>If you click on the yellow sign and do not have an option to verify keys – also repeat step 3 and 4 and also restart the app Riot. Sometimes this helps :-)</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Congrats! Welcome in the fediverse of open, free and secure messaging!</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>
<strong>There‘s
more to come!</strong></h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>
If
you‘ve followed the setup steps in this article, you‘ve probably
noticed, that the Riot is not all the time as user friendly as
mainsteam apps like Whatsapp or Telegram are. To
me, all in all these issues are minor compared to the features I get:
a reliable and secure messenger.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Luckily, the usability will be improved soon. In February of 2018, the project got an investment of $5 M, which should result in several improvements on the project. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Now, please spread the word and let everyone else participate in a more open, free and secure future!<br/></p>
<!-- /wp:paragraph -->