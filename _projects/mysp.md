---
layout: project-page

title: My SP app
subtitle: App development (Windows Phone)

image: /assets/images/mysp.jpg
color: 9a3235

year: 2013-10

infobox: 
    - title: Type
      content: |-
        App Development
    - title: Date
      content: 2013
    - title: Technology
      content: |-
        Windows Phone app
        (C# + XAML)
    - title: Download
      content: |-
        <a href="#download">Download</a>

description: My SP is a unofficial Windows Phone 8 app that provides Singapore Polytechnic students with quick access to their timetables and more.
---

My SP was developed around 2013 for Windows Phones users to access student information. It provides a quick peek of the next two lessons right on the main page, with access to the full student timetable and other tools, including SP Cam and the campus map.

![Image of the app](/assets/images/mysp.jpg)

At the time, an official Android and an iPhone app was available, along with a student web portal which was not mobile-friendly. 

## Development

My SP was developed as a native Windows Phone app and written in C#. 

As a public API was not available, Fiddler was used to inspect the network traffic of the official SP Mobile Android app and to figure out the endpoints for each feature. 

## Design and User Experience

My SP is designed for convenience and follows Windows Phone design principles. 

![Main page panorama control of the My SP app](/assets/images/mysp-flow.jpg)

The app loads into the main page with a Panorama, showing the next two lessons above-the-fold. A tap or swipe provides access to additional features, such as the full weekly timetable, and other tools such as SP Cam (which shows camera images of common gathering spots to show crowd levels) and the campus map. 

----- 

## Download

<p class="info warning">Please note that this app is no longer being maintained and updated. </p>

* [{% include icons/external-link.svg %} **Download** from the Windows Store](http://www.windowsphone.com/s?appid=369bb9b2-081e-4b51-a92b-80a783f484bb)
* [My blog post about the design and development process](/posts/about-mysp/)
 
## Feature list

* **Timetable**: Shows your next classes and browse your weekly timetable.
* **SP Cam**: view traffic at food courts, SPICE service desks, and more.
* **SP Library Mobile**: quick access to the mobile SP Library website
* **Campus Map**: view a map of the SP campus, and locate facilities and buildings.

## Privacy policy and data use

This privacy policy was last updated 28 August 2013. If there are differences between copies of this policy, the one located here applies.

My SP only stores your student admission number (or admin number), which you provide through the Settings page. This information is stored locally on your device. It is only used when communicating with SP's servers, when retrieving your timetable.

When you uninstall the application, all information stored by the app on your device will be deleted.
