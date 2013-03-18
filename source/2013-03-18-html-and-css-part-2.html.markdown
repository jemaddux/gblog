---
title: HTML and CSS Part 2
date: 2013-03-18 15:14 -06:00
tags:
---

The second part of HTML and CSS started to get into how to use CSS to beautify our pages. Boxes (or divs) and forms were my two favorite techniques in the second part of the book because of their usefulness. The divs allow a designer to segment off parts of the page to easily create an overall feel and design for the page. For example you can use them to create a sidebar of links and serperate it from the content of a page like so:

<img src="/images/before.png" style="border: 5px solid black">
       
The page starts with the unordered lists and the paragraphs that display one on top of another. When you wrap the list and articles with divs and use a bit of css you can order them.        


```

  <style>
  #menu{
    width: 25%;
    float: left;
  }
  #article{
    width: 70%;
    float: right;
  }
  </style>

  <div id="menu">
  <ul>
    <li><a href="">Link 1</a></li>
    <li><a href="">Link 2</a></li>
    <li><a href="">Link 3</a></li>
    <li><a href="">Link 4</a></li>
  <ul>
  </div>

  <div id="article">
    <h3>An Article on Bacon</h3>
    
    <p>Bacon ipsum dolor sit amet capicola salami 
      ham hock, meatball boudin biltong pastrami etc....</p>
  </div>

```

With this bit of code the page changes and the divs get out of each others way.    

<img src="/images/after.png" style="border: 5px solid black">

You can also use the divs to draw some silly shapes like a target.

<img src="/images/target.png" style="border: 5px solid black">

With this code:

```
  <style>
    #black{
      background-color: black;
      padding: 15px;
      border-radius: 50%;
    }
    #blue{
      background-color: blue;
      padding: 15px;
      border-radius: 50%;
    }
  </style>

  <div id="black"><div id="blue"><div id="black">
  <div id="blue"><div id="black"><div id="blue">
  <div id="black"><div id="blue"><div id="black">
  <div id="blue"></div></div></div></div></div>
  </div></div></div></div></div>

```

The forms are also extremely usefull because they allow you to take in information from your visitor and use it in some way. For instance we can setup a simple login with a small amount of code.      

```

  <form path="/login" method="post">  
    <label for="username">Username:</label>
    <input type="text" name="username" />
    <label for="password">Password:</label> 
    <input type="password" name="password" />
    <input type="submit" value="Login" id="login" />
  </form>

```



<br><br><br><br><br><br>









