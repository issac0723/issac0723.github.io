---
layout: page
title: Sleep Tracker in Ionic
description: A basic sleep tracker for monitoring sleep data
img: assets/img/sleep-tracker.png
importance: 2
category: Course Project
---

**Description**: User Interaction Software individual project. A mobile app by developing a tool for tracking sleep and sleepiness in Ionic.   
**Duration**: March 2022 (1 week)  
**Tool**: IntelliJ IDEA. Built with Ionic, Bootstrap and Angular.  
**Link**: [A demo runs on Android device](https://www.youtube.com/watch?v=k2e3UpI_WqI).

My app is designed with the specific purpose of enabling users to quickly record their sleep data and conveniently visualize it. My goal was to simplify the data-logging process by minimizing the number of required inputs and reducing any obstacles to data entry.  

<br>
My code is compatible with both iOS and Android systems, it is predominantly designed in line with the Android design style. Therefore, in the [demo](https://www.youtube.com/watch?v=k2e3UpI_WqI), I only present the Android interface to showcase the design and user experience accurately.


  <div class="row">
      <div class="col-sm mt-3 mt-md-0">
          {% include figure.html path="assets/img/sleeptracker.png" title="example image" class="img-fluid rounded z-depth-1" %}
      </div>
  </div>
  <div class="caption">
      Sleep Tracker UI interface.
  </div>


#### __Features__
- The The ability to log overnight sleep.  
- The ability to log sleepiness during the day.  
- The ability to view these two categories of logged data.  
- Storing data locally or in a database.  

<br>
#### __Design principles__
In order to create this app, I have incorporated the principles of strong mobile design to ensure its effectiveness and user-friendliness.
- A helpful initial view - three selections on log and view data.  
- The “uh-oh” button - be able to back out of the current page.  
-  Error prevention - toaster message to remind the user of missing/invalid input.  
- Follow platform conventions.  
  *    Android, the back button and a uniform dark theme with a purple-ish-blue header are always available.

<br>
  <div class="row">
      <div class="col-sm mt-3 mt-md-0">
          {% include figure.html path="assets/img/logdata.png" title="example image" class="img-fluid rounded z-depth-1" %}
      </div>
  </div>
  <div class="caption">
      Log Overnight Sleep. Log Sleepiness During the Day.
  </div>

  <div class="row">
      <div class="col-sm mt-3 mt-md-0">
          {% include figure.html path="assets/img/viewdata.png" title="example image" class="img-fluid rounded z-depth-1" %}
      </div>
  </div>
  <div class="caption">
      View Logged Data. Track sleepiness level.
  </div>

*Note: As per the class policy, I am not permitted to upload my code on GitHub. :zzz:	Sleep well :)
