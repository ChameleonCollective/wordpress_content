---
ID: 1288
post_title: Value of marketing bookmarklet?
author: Damion Parsons
post_excerpt: ""
layout: post
permalink: >
  https://chameleon.co/blog/2011/03/02/value-of-marketing-bookmarklet/
published: true
post_date: 2011-03-02 00:00:00
---
<img class="alignleft size-full wp-image-1587" style="margin-right: 10px; margin-bottom: 10px;" title="m&amp;m super heroes digital invasion game" src="https://takemetoyourleader.com/wp-content/uploads/2011/03/mm-super-heroes-digital-invasion-game.jpg" alt="" width="300" height="232" />The Digital Buzz blog <a title="Digital Buzz Blog M&amp;M Internet Invasion Game" href="https://www.digitalbuzzblog.com/mms-internet-invasion-game-space-heroes-bookmarklet-app" target="_blank" rel="noopener noreferrer">posted today</a> a new campaign by M&amp;M called <a title="M&amp;M Internet Invasion Game" href="https://www.m-ms.dk/spaceheroes/" target="_blank" rel="noopener noreferrer">M&amp;M’s Internet Invasion Game</a>. The game was "developed" by <a title="BBDO Denmark" href="https://www.bbdo.dk/" target="_blank" rel="noopener noreferrer">BBDO Denmark</a>, and there are tons of learnings we could get out of this.

1. The M&amp;M's Space Heroes is actually a straight up copy of the <a title="Kick Ass Bookmarklet" href="https://erkie.github.com/" target="_blank" rel="noopener noreferrer">Kick Ass bookmarklet</a> by Erik Andersson, also covered by <a title="Kick Ass Bookmarklet / Asteroids / Wired" href="https://www.wired.com/epicenter/2010/09/kick-ass-bookmarklet-turns-the-web-into-asteroids/" target="_blank" rel="noopener noreferrer">Wired</a> among other respectable publications. BBDO's <a title="BBDO Space Invasion Super Heroes Game" href="https://m-ms.dk/invaders/js/spaceship.js" target="_blank" rel="noopener noreferrer">code</a> acknowledges it was inspired by it, though it's just a copy with new graphics. This is a smart move by BBDO, taking into account they probably did not spend more than a day on development of the microsite and new graphic assets, and charged M&amp;M a substantial margin for coming up with the idea. The code was open source has an Apache 2 license, granting anyone full rights to copy, modify, and distribute for any commercial use, thus BBDO didn't do anything illegal, it was actually smart -- not creative, but smart.<!--more-->

2. Deployment strategy: the code was not optimized, minified, or even deployed to a CDN. I would have expected an agency dealing with Mars food to be a little more thoughtful of brand performance.

3. Tracking. Perhaps the most important point I'd like to make. Due to the fact that bookmarklets are simply plain JavaScript code that runs on a browser, it makes it a little less trivial to track, but far from impossible. Technically speaking, they could have modified the code to add pixel images, a JavaScript timer to update it every few seconds, and could have gathered full analytics tracking total games, unique games, geo-location of players, time spent on site, top referrers, etc.

You should always use a simple rule of thumb: if you can't measure it, don't do it.

It is not hard to predict that Mars will ask BBDO how many people played this game? How much time they've spent? What's the most popular site where it was played? How many people shared it? How many people talked about it? ... and most likely they won't get any answers.

So what's the moral of the story?
<ul>
 	<li>It's hard to come up with purely innovative ideas and you should always welcome creative mash-ups and different uses of existing experiences (full copycat perhaps not so much).</li>
 	<li>No matter what you do, always try to improve based on previous cycles, add value, enhance the experience, bring something unique to the table.</li>
 	<li>Always, but always, track and measure results.</li>
</ul>