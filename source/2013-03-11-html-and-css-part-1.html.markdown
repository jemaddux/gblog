---
title: HTML and CSS Part 1
date: 2013-03-11 15:36 -06:00
tags:
---

The thing that I have found to be the most fun with HTML has been embedding videos into webpages. Being able to do this on your own webpage may seem a bit silly since we have YouTube and can embed videos from there without having to use our own bandwidth on videos, it is still nice to have the option to have the video on your own page if you want. Doing it that way can keep YouTube from pulling people off of your site by offering them funny cat videos instead of whatever video you are trying to serve up next for them. You can embed videos like this:     
      
```html

  <video poster="images/puppy.jpg" width="400" 
    height="320" preload controls loop>
    <source src="video/puppy.mp4" 
      type='video/mp4;codecs="avc1.42E01E, mp4a.40.2"' />
    <source src="video/puppy.webm" 
      type='video/webm;codecs="vp8, vorbis"' />
    <p>A video of a puppy playing in the snow</p>
  </video>       
```
      

I was suprised to see that they talked about how to insert Flash videos on your site (as I think of it as a dead technology since Apple has been doing their best to kill it). I guess people still use it for video ads.       

For your entertainment here is a video of a laughing baby (which I got from YouTube.com since I don't want to use my bandwidth on it).     

<iframe width="560" height="315" src="http://www.youtube.com/embed/RP4abiHdQpc" frameborder="0" allowfullscreen></iframe>       
        


                    

