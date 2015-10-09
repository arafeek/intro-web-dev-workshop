# Intro to Web Development
---

### Preamble
This guide introduces basic web development concepts to people with little to no previous programming or design experience.


###Contents
[Setup](#setup)  
* [Windows](#windows)
* [OSX / Linux](#osx)

[HTML](#html)  
* [What is HTML?](#what-is-html)
* [Basic Web Page](#basic-html)
[CSS](#css)  
* [What is CSS?](#what-is-css)
* [How CSS Works](#how-css-works)
* [Basic CSS](#basic-css)
* [Flexbox](#flexbox)
[Putting it all together](#all-together)  
[Show the world!](#heroku)

[Additional Resources](#additional-resources)

### Setup

**1) Install a text editor**
There are lots of different editors to chose from, below are some of the ones I like:
* [Sublime Text 3](http://www.sublimetext.com/3)
  * Unlimited free trial (or you can buy the lisence for $70)
  *  A vast array of plugins and packages built by the community make ST3 extremely
    customizable
* [Atom](https://atom.io/)
  * Completely open source (and free!)
  * Highly customizable
  * Great for web development
* [VS Code](https://www.visualstudio.com/en-us/products/code-vs.aspx)
  * Multi-platform text editor / IDE by Microsoft
  * Based off Visual Studio
  * Lots of features right out the box
  * Great for all round editor for web and otherwise
* Vim
  * If you're using vim, you probably don't need any further explanation
* Emacs
  * See above comment about vim
* [Notepad++](https://notepad-plus-plus.org/)
  * Not the prettiest editor, but it'll get the job done
  * Completely free
* Notepad (Windows) / TextEdit (Mac OSX)
  * Do yourself a favor and don't use these for any kind of development...please

### Introduction

#### So what are we _really_ looking at when we view a webpage?
On a daily basis, we probably sift through hundreds of web pages. Some of us probably
skim over more than that (looking at you, redditors). This is all well and good,
but what's really going on here? What magic is at work on these websites, and more importantly,
how can we harness these arcane skills to start making our own websites?

#### A peek behind the curtain
Basically, a simple website can be thought of as a series of "pages" held together by a series
of "links". You might be thinking, "Duh..that's why we call them web pages", but let's really
think about this for a second. What is a web page really?  

(maybe insert an image here)  

Lets take a step back for a second and look at our computers in front of us. Generally,
you have a word editor (Microsoft office, Open Office, Libre Office) that you use to open
word files (.doc, .docx, etc..). Using this, we can think of web pages as the file format of the browser,
only instead of it opening files on your machine, it receives the files over the internet when you
click a link or do a search or type something into the URL bar.  

Okay, great, so there are files we get and our browser lets us view them, but what type of files are they?
I'm glad you asked! Welcome to the wonderful world of [HTML](#html) friend.

### HTML 

HTML stands for "**H**yper **T**ext **M**arkup **L**anguage". In layman's terms, it is a 
plain text language used to tell the browser how to render certain **elements**.

**Elements** Can be thought of the building blocks of the web page. Everything is an element.
Some examples are:
* Links
* Headings
* List items (like these!)

Atomic elements like those mentioned above can then be used to construct complex elements like:
* Navigation bars
* Menus
* The sky's the limit!

### Basic Structure

```html
<!DOCTYPE html>
<html>
  <head>
    <!--- [1] -->
    <title>Example page</title>
  </head>
  <body>
    <!-- [2] -->
    <h1>Hey there!</h1>
    <!-- [3] -->
  </body>
</html>
```



