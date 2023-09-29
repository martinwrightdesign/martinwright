---
title: Post Completion services
subtitle: Digitising SDLT and AP1 with a first-to-market web app for property lawyers. 
date: 2019-07-17 00:00:00
description: The Post Completion service was the first of a series of modules available for the newly designed tmconvey platform, and tmgroup's first branch out beyond the core of the conveyancing transaction. Post completion is a service which registers a new home purchase with the Land Registry and then ensures all relevant tax is paid. 
featured_image: postcompletion-masthead.jpg
accent_color: '#ea4d57'
gallery_images:
  - postcompletion-masthead.jpg
  - postcompletion-masthead2.jpg
  - postcompletion-masthead3.jpg
---

**The Post completion service was the first of a series of modules available for the newly designed tmconvey platform, and tmgroup's first branch out beyond the core of the conveyancing transaction.  Post completion is a service which registers a new home purchase with the Land Registry and then ensures all relevant tax is paid.**

### Scope

Initially the requirement from the business was to develop a new digital SDLT service using a newly available API from the Land Registry.  Historically this was a task completed using a paper form, with supplementary additional forms required depending on the transaction particulars. 

The intention was to build upon the auto-complete functionality we had built with tmconvey to automate, streamline and reduce manual errors by digitizing this process. We would also pre-validate submissions to capture errors upfront, saving the users time in resubmissions. 

The project was to be developed to very tight deadlines in an effort to be first to market. 

> “I’ve been using tmgroup’s new Post-Completion service – with SDLT and AP1 submission – for about a month. It’s really user friendly especially as it has all of the features of existing services, and more. I also find it helpful that information is pulled through from my case and automatically pre-filled in my SDLT and AP1 forms, as this definitely saves time.”

##### Product Video

{% include post-components/video.html
	url = "https://www.youtube.com/embed/QqzFPD9vcd8"
	full_width = true
%}

### Approach
With such tight deadlines we were unable to spend the desired time in a discovery phase; interviewing users and understanding the problem to it's fullest. Unfortunately the limited time available had to be spent understanding the paper forms, the newly released API and the permutations of submission types.

I embarked on a series of clickable prototypes, initially to emulate the paper form closely. However we quickly discovered that the API didn't correspond directly with the paper form, and had additional dependencies and requirements that weren't present with the manual submission.  This ultimately proved more confusing for the users as they struggled to reconcile these difference. 

With that in mind, I approached it in a new way - leaving the older paper forms behind. Taking all the requirements of the new API and structuring it into a logical grouping of linear steps, each dealing with an aspect of the transaction in turn, I produced a new prototype. User testing on this was much more successful, with even non-specialist staff able to interpret the requirements and complete the form. 
![Screenshot of Step Functionality in SDLT](/images/projects/sdlt-steps-corner.jpg)

> “Submitting SDLT forms is much easier on tmconvey, as it pulls through information from the case such as the property address, which is good. I like the layout of the SDLT form too, which makes it easier for our fee earners and our clients to understand, so they can approve the information easily. ”

After the success of this testing, we produced the first iteration of the product and launched to a selected series of customers. The SDLT element was successful, however we were quickly asked 'What about AP1?' We'd discovered it was only part of the picture, customers required AP1 submissions to be handled too - we had only solved part of the problem for most customers.

##### Pivoting - We need to include AP1 Submissions

Realising to really solve our customer's pain points we quickly moved to tackle the AP1 element. While this wasn't initially scoped as part of the product, it afforded an opportunity to test something we'd conceived of as part of the tmconvey redesign; chaining optional modules together.

Fortunately at this stage, following the successful testing with SDLT we had an enthusiastic set of test customers, and access to users with that. 

Quickly producing XD prototypes based off a now established pattern from SDLT we were quickly able to validate the new service and start production in an aggressive week long sprint cycle. I worked one week ahead of the development team, validating the next phase with users before passing it on to production. 

![AP1 Screenshot](/images/projects/start-ap1.jpg)

> “By the time you get to the AP1 form, and have already completed your searches and your SDLT, it copies across the agent details, property address, and copies across the SDLT5 too – so you don’t have to scan and save.”

In addition to designing a discreet  and contained AP1 service, I looked to design a clear user flow taking customers from a completed case created in tmconvey, through our SDLT module into AP1. This flow would bring with it all the relevant case information, and pre-populate the following module reducing data entry and further minimising the risk of human error.  

### Lessons Learned

The project, while ultimately successful was not without challenges. Without a full discovery phase we missed a key element in the Post Completion phase - AP1 submission. 

The project has really hammered home the importance of fully understanding the problem you're aiming to solve, the importance of being able and willing to change direction as required and finally not just accepting the business requirement as the best approach.

> “Before using tmconvey’s Post-Completion services, we were visiting different websites and logging into HMRC and Land Registry separately. We were also printing off the paper AP1 form, before filling it out, scanning it and uploading it. It was all very time consuming, but now it’s so much easier. ”