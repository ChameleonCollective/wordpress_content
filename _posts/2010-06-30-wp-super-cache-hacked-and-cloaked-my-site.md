---
ID: 1189
post_title: >
  WP Super Cache Hacked and Cloaked my
  Site!
author: Damion Parsons
post_excerpt: ""
layout: post
permalink: >
  https://chameleon.co/blog/2010/06/30/wp-super-cache-hacked-and-cloaked-my-site/
published: true
post_date: 2010-06-30 00:00:00
---
<strong>Classified as RANT!</strong>

<strong>Prequel</strong>: I noticed that some pages were taking too long to load ... I heard good things about WP Super Cache and I had tried it before, but it was messing up when toggling between web view and mobile view ... randomly providing web users the mobile view, and mobile users the web view ... I decided to give it another chance, tested, and it works ... speeded up the site drastically.

<strong>Chapter 1</strong>: A week goes by and I notice a drop in site traffic ... I analyze why and it's mainly organic traffic from Google

<img class="alignnone size-full wp-image-1195" title="Google Analytics TMTYL" src="https://takemetoyourleader.com/wp-content/uploads/2010/06/Google-Analytics-TMTYL.jpg" alt="" width="400" height="42" />

More specifically, % Change -42.81% ... ok, now I'm pissed... why all the sudden my search ranking dropped so much?!

<strong>Chapter 2</strong>: I perform a search for some of my main articles, such as <a title="Free Social Media Monitoring Tools" href="https://takemetoyourleader.com/2009/03/24/free-social-media-monitoring-tools/">Free Social Media Monitoring Tools</a>. Result?

<img class="alignnone size-full wp-image-1196" title="Google Search TMTYL" src="https://takemetoyourleader.com/wp-content/uploads/2010/06/Google-Search-TMTYL.jpg" alt="" width="561" height="211" />

Buy Meridia Pill? Reliable Online Drugstore? WTF?! Where did this come from? I obviously never put that there ... So I click through and it's my regular content ... but if I open the cached Google version, this is what I see:

<!--more-->

<img class="alignnone size-full wp-image-1197" title="Take Me To Your Leader Hacked" src="https://takemetoyourleader.com/wp-content/uploads/2010/06/TMTYL.jpg" alt="" width="550" height="226" />

My title, metatags, categories, links, headlines, all replaced with Meridia copy ... And the only change I've made in months is to activate the WP Super Cache plugin.

Hell, if I search buy meridia pill my site is #5 ... I hate this hack!

<img class="alignnone size-full wp-image-1198" title="wordpress hack" src="https://takemetoyourleader.com/wp-content/uploads/2010/06/wordpress-hack.jpg" alt="" width="550" height="432" />

if you search Google for wp meridia, you'll find other blogs suffering the same problem.

<strong>Chapter 3</strong>: I just disabled the WP Super Cache and I really hope this cloaking goes away soon and my site goes back to normal ... If  you're using the WP Super Cache plugin I suggest you check your ranking. If you know anything else about this hack, please let me know.

I'll keep you guys posted on what comes out of this.

Thanks for listening.

<strong>[Update 1]</strong>: Just did some digging around and it appears it wasn't WP Super Cache, it's actually Wordpress being hacked right at the same time I activated it ... Some reading <a href="https://techcocktail.com/home/2010/04/08/wordpress-hacked-virus-cloaks-search-engines/">here</a>, and <a href="https://www.christopherspenn.com/2010/04/07/find-the-latest-wordpress-hack/">here</a>. Anyone running WP suffered this hack? How did you solve it?

<strong>[Update 2]</strong>: WP recommends you install the WP Secure plugin

<strong>[Update 3]</strong>: You can use Google Webmaster tools (https://www.google.com/webmasters/tools/labs-googlebot-fetch-2) to fetch the site as Google. Still messed up!

<strong>[Update 4]</strong>: After some heavy database digging and following carefully instructions from this <a title="How to remove the wordpress cloaking hack" href="https://www.pearsonified.com/2010/04/wordpress-pharma-hack.php" target="_blank" rel="noopener noreferrer">blog</a>, I was able to get rid of the cloaking. I had to search within my WP_Options for a bunch of keys and delete them all ... really scary cuz I had no backup case I messed up ... but it turned out good ... Ran a few tests with the Google Webmaster tools googlebot fetch and it's finally returning the correct results.

Sorry WP Super Cache for not trusting you, but you really came at the wrong moment. I will enable the plugin again tomorrow once Google re-fetches all the new cleaned up content and keep checking for problems within the next few days. I corrected the hack, but did not close the door for it to happen again ... let's hope it stays like that.

<strong>[Update 5]</strong>: I cleaned it, but did not patch it. The problem keeps coming back. How do you block this thing?!

<strong>[Update 6]</strong>: Changed all passwords; hack persists. Installed WP Secure and WordPress exploit scanner ... run them, found nothing.

<strong>[Update 7]</strong>: I was hesitant to upgrade WP to 3.0 and all plugins in fear of something breaking and I was not going to have time to take care of it ... but @Brandon gave me that confidence as he had upgraded all his blogs ... status: running 3.0, upgraded all plugins, uninstalled all unused plugins ... so far so good. Everything is working great, no traces on hacks. Re-enabled WP Super Cache and it's working great. Thanks @Brandon for your time to help solve this issue.

<strong>[Update 8]</strong>: good morning, it's still happening! Can't get rid of this thing. So I installed WP Secure and locked down the entire installation ... no more access to wp-content or wp-includes ... wp-content broke my header rotator and my favico, but I added rewrite rules to work around it. The wp-includes broke the TinyMCE WYSIWYG editor in the backend, so I had to edit the htaccess file to allow access to wp-tinymce.php.