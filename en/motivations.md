---
layout: page
title: Motivations
---

The following describes several slow moving thought processes that resulted in the creation of Regolith Linux.

<p align="center"> *** </p>


In 2016 Apple released a new version of their "pro" laptop line without function keys.  Replacing the keys was a small LCD screen designed to provide dynamic functionality depending on the application.  As one who writes software, I rely heavily on function keys for my day-to-day work.  It seemed like an obvious mistake and I assumed Apple would provide updated high performance models with the function keys.  This hasn't happened, and so instead I bought the fastest version of the computer that came with physical function keys.  Ultimately, the machine proved too underpowered for my needs and the keyboard in general caused me many typos, taxing my productivity.  It occurred to me then; that the price I'd paid a decade earlier, in switching to a Mac had been a mistake.  I was locked to a single hardware and operating system vendor.  Apple clearly does not consider me and my type in their focus groups when designing "pro" computers.  I was stuck in a dead-end product line, and would have to do a lot of learning and adapting of a different system to dig my way out.  At this time I began to look at Linux distributions and Linux friendly hardware in earnest, resolved to not allow this to happen again.  As Linux comes in many variations, and runs on hardware from a large variety of manufacturers, it seemed like a good bet.  But, there was a lot of ground to cover...

<p align="center"> *** </p>

When working in teams that write software, it is common for me to visit coworkers at their desks to work together. Sometimes I'd notice the inefficiency of their interactions with their computers. With many windows layered over each other, hand continually moving from keyboard to mouse, and big desktop widgets and gizmos that crowded their screens, I found it strange that they would work daily in such a manner.  In an effort to gain productivity, I remove as much of the desktop stuff (such as the dock) as possible when setting up a new computer.  I realized that frequent window switching, resizing, and organizing took a significant amount of time.  Additionally, when switching between programs, I'd often lose my train of thought due to some random thing popping up or my inability to find the right window instantaneously.  Some success was had in customizing the Mac's UI, but I still found myself spending a lot of time micromanaging my computer.  Around this time I recalled a colleague many years ago showing me his work setup with a strange thing called a "tiling window manager".  At the time I thought of it as a nerdy fad...too esoteric for real work.  At this point I looked back into the state of affairs of tiling window managers, to see if they still existed.  They do!  And happily they are the perfect antidote for the clutter and inefficiency of the modern "desktop UI".  But, I found that often these components needed to be compiled from source and looked pretty ugly by default...  

<p align="center"> *** </p>

A year or so back, I discovered that YouTube.com hosts a vast array of content for computer nerds such as myself.  Having cut my teeth on programming in the 80's with computers such as the Commodore 64 and Amiga 500, I found many videos of these old machines still in use.  In recalling these times from my childhood and in watching the vidoes, it came to me that the playfulness and accessibility of computers has been lost to layers of sophistication and advertisements.  Some of it is useful (switching between languages, configuring monitors), and some of it is not (oversized, if beautiful, icons to launch applications you may never use, notifications, things bouncing, jumping, and curving off of the screen).  Simply loading a terminal on modern computers takes several clicks, and is typically a poor experience out of the box.  Earlier computers often booted right into a programming environment.  Nothing to fuss with, just get to business!  I wanted to bring this simplicity back to my daily compute.

<p align="center"> *** </p>

When researching tiling window managers, an initial reaction I had was that they are generally pretty ugly out of the box. Often they are designed by people who care less about aesthetics than they do pure functionality.  Of course, it is not difficult to configure these systems to be more pleasant to look at.  For example, I would often visit [Reddit](https://www.reddit.com/r/unixporn/) topics with screenshots of "riced" desktops which often featured systems with tiling window managers.  It fascinated me that so many would spend so much time to make amazing, clean, and elegant computing interfaces.  I was hooked.  However, there I had a problem with "ricing": it's all about personal customization.  People would create amazing interfaces, but always custom to their specific system.  I wanted to have a consistent experience on my home PC as well as what I use at the office.  I wanted to be able to update in one place and have all my systems just get the update.  There is a simple way of achieving this; by using a package system.  And so I decided that my rice needed to be packaged so that I could just install easily and consistently.  My day job at the time would allow me to use Linux at work, as long as it was Ubuntu.  So, I learned how to package my riced configurations as Ubuntu packages.    

<p align="center"> *** </p>

In summary, the functional regression of the Macintosh for professional work lead me to realize that the value of "it just works" was less than the value of being able to control the interface of my computer as I desired.  The innovative desktop ricing community taught me that beautiful and efficient computer interfaces can be created by anyone, and that by packaging my customizations in Ubuntu, I could in essence have my cake and eat it to.