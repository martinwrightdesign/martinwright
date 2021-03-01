---
title: Practicing what I preach and being more accessible
date: 2021-01-25 00:00:00
description: Having neglected accessibility for speed, I'm now retrofitting enhancements to this site, but first lets address my terrible lighthouse score
featured_image: '/images/accessibility.jpg'
---

As I mentioned in the [first post here]({% post_url 2020-09-22-a-new-start %}), this website was stiched together at speed to update what was an creaking old Wordpress site. Unfortunately, I didn't take my own advice and build without accessibility as a primary concern - now I'm working to address that. 

I started by wanting to add a dark mode, and out of curiosity ran a Lighthouse audit... 

### Just how bad is it? 
According to Lighthouse, it isn't great. 

![Poor Initial Lighthouse score](/images/initial-lighthouse.jpg)

I'm less concerned initially about the performance, a cursory glance spots some easy wins there. To be fair to me, some of them are a hold over from the theme I have based the site on, but I will aim to address them as soon as possible.

However, the accesibility score of 65 does raise some eyebrows!

An hour or so minor tweaks, and a more extensive than I had hoped dive into the slider plugin I am using and we now have a much better score. 

![Lighthouse accessibilty score improved to 97](/images/lighthouse-2.jpg)


### Now onto darkmode!
Able to now say that at least my site is pretty accessible, onto what I actually wanted to look at - adding a dark mode toggle. 

Researching the best methods for implimenting this I came across an article on the ever-useful CSS tricks. [Read the article.](https://css-tricks.com/a-complete-guide-to-dark-mode-on-the-web/) This exhaustive article really does cover everything you could need to know about implimenting a dark mode, including supporting the 'prefers-color-scheme' functionality.

So that's the next plan for this site, a user friendly toggle that respects the users presets. Lets see how that pans out!

