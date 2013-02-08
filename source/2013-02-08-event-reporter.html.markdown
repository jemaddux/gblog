---
title: Event Reporter
date: 2013-02-08 09:05 -07:00
tags:
---

Another week and another project done. This week we made a program which was an extension and improvement Event Manager and is called Event Reporter. Event Manager had been a program to take a CSV file of people who attended a political rally and generate thank you emails for each of them. With Event Reporter we had to write a program for a much bigger CSV file of event attendees which could execute searches on them and then print those searches out to the screen or to a file. 

To start the program I decided to break it down into the basic parts which I decided were a queue method which would hold all the data and perform operations on it, a help method to display help commands and a controller which bossed the other two classes around. I started off with the controller mostly because I had no idea where to start with creating the queue method. It was mostly case statements which control which methods are called when the user types in commands like "find first_name John", "queue print" or "help". It was fairly easy and only took an hour or so to get in good shape. After that I wrote out the Help methods because I still hadn't had any brainwaves on how to do the queue class. 

So after avoiding it for around three hours I only had the queue class to write but I still didn't know where a good place to start would be so I just dived in and tried to write a load file that would load the CSV data to a multidimensional array. The next day, after spending several hours working on it, I still didn't have much working for me so I decided to work on a smaller dataset that I created in a completely different program just to wrap my head around it. I wrote out a smaller program and after playing with it for only an hour or so I had a working queue variable that was a series of hashes that represented each attendee inside of an array which was the whole file. That was the key. Once I had that I still had to spend several hours implementing features and debugging the program but I had a solid base to work from that let me build the program without chaning much.

As for next time I code a program I will change a few things and keep a few things the same. I will not start with the easiest part of the program first because once I had the queue done I had to go back and fix all the easy stuff to work with it anyway (which took more time than it had to write it in the first place). I will take bigger problems and play around with them on a smaller scale when possible so that I can get a hang of them before implementing lots of code that later needs to be rewritten. 

Here is a link to the code (which I have since refactored quite a bit).

https://github.com/jemaddux/Event_Reporter

-John Maddux