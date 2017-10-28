---
layout: post
title: "The story of My SP"
image: /assets/images/mysp.jpg
color: \#9a3235
---

<p class="lead">A look at the design and development process of the My SP app. </p>

[My SP](/projects/mysp) was the first ever app I published on to an app store. I started work on the app around August 2013 while I was a student at Singapore Polytechnic. 

![Main page panorama control of the My SP app](/assets/images/mysp-flow.jpg)

At the time, I was using a Nokia Lumia 820 (which ran Windows Phone). Without an official SP Mobile app, my options for checking my timetable were either to try to navigate the student portal on a phone, or to use an old screenshot I had taken of it. 

## Reverse engineering

The first step was to work out if it's even possible to retrieve timetable and other data with a third-party app.

To find out how to retrieve timetable data, I installed the official SP Mobile app on an Android phone, with network traffic passed through [Fiddler](http://www.telerik.com/fiddler). I soon realised that the official app in 2013 sent basic `GET` requests for timetable data. This was the same for images (such as those used by SP Cam), but that's to be expected. 

This has since changed in later years -- the SP Mobile app now requires a login with student ID and password. However, the original endpoint I found continues to work.

## UI design

SP Mobile has a module-based navigation system, where the main landing page of the app contains a grid of icons, with each icon opening individual modules (such as Timetable, SP Cam, or Campus Map). [Here's a link to Android Play, with screenshots.](https://play.google.com/store/apps/details?id=org.sp.SPMobile)

Since the primary purpose of the My SP app is to provide timetable access, I opted to display the next two lessons above-the-fold, right on the main page. This eliminates the time spent drilling down to the timetable module, which was a common complaint with the official SP Mobile app.

![Design progression of the app](/assets/images/mysp-design.gif)

## A job half-done

Although I quickly published the app and followed up with a few bug fix releases, there were still some features that never made it. The app shipped without live tile support; I didn't manage to implement offline mode which displayed cached data; and finally the app was bodged together with rather sloppy coding. 

That said, I did manage to ship a working app albeit without those features. If I had worried about rewriting the code and structuring it better (as I almost did), it would have been likely that I would have abandoned this project before it was complete. 

## What's next?

There won't be any further updates to the app. No longer being a student meant that maintaining the app was hard without being able to test it out myself. 

The app will continue to remain available on the store for as long as Microsoft is willing to list it (It's a Windows Phone 7 Silverlight app, if I recall correctly), and while SP continues to serve timetable data on that old endpoint. I'll remove the app the moment it stops working. 
