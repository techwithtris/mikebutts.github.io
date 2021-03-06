---
title: Codepen 101
date: 2017-03-21 11:43:00 -05:00
categories:
- tutorials
tags:
- tutorial
- beginner
author: Tris
layout: post
---

[Codepen.io](https://codepen.io) is a revolutionary web IDE. What that essentially means is that you can code a webpage, complete with CSS and Javascript, all in your browser, without having to install anything. How cool is that?

Beyond that, the coolest thing about Codepen is its ability to show you what your code does. When you, say, change the background color, the preview automatically refreshes and shows you the changes. It's super great for understanding the effects of your own code.

However, working on [30 Days, 30 Sites](http://www.subscribepage.com/30days30sites) has brought to light a bitter reality: the true powers of Codepen have not yet been realized by a lot of people. A lot of you have been asking for help because your code works locally, but not on Codepen.

Codepen can be hard to wrestle with. Here's a little tutorial on how to use Codepen. We'll be building a really simple webpage, with minimal HTML, CSS and JavaScript.

## TL;DR:
### Steps to creating a new webpage:
1. [Creating the pen](#step-1)
2. [Hack away](#step-2) in the HTML, CSS, and JS editors
3. [Save and rename](#step-3) your pen
(optional)4. Add your new pen to a [collection](#step-4)

# Terminology
Now, before we begin, let's make some things clear:

## Pens
What's a pen? It's basically Codepen's fancy word for a webpage. Codepen calls "projects" full fledged websites that can contain data files, multiple assets, and multiple HTML files, etc.

## Editors
[codewindows.PNG](/uploads/codewindows.PNG)

Editors are surrounded by the blue squares. There are 3 different editors: one for HTML, one for CSS, and the other one is - you guessed it - for JavaScript.

You know how we'd put HTML, CSS, and JS code in different files? This is the same concept. Instead of files, we put them in their own editors.

## Settings 
The little gear buttons surrounded by the brown boxes are where your settings live. Here's what you can do with the settings: 
### HTML
[html.PNG](/uploads/html.PNG)
    * Use a preprocessor - if you want to use HAML, Pug, etc, this is where you tell Codepen! Then, there's literally nothing else to do - just code in the preprocessor language you chose.  
    * Add a class to HTML - sometimes you need to add styling to your HTML tag. Here's where you put it.  
    * Put stuff in the <head> - Codepen is set up so that you won't need to add your <head>, <meta>, <link>, and <script> tags in the HTML editor. Just add the <meta> stuff in the settings, and the <link> and <script> links in the CSS or JavaScript settings.  

### CSS
[css.PNG](/uploads/css.PNG)
    * Preprocessors - so SASS, LESS, that kind of good stuff. Our e-mails in [30 Days, 30 Sites](http://www.subscribepage.com/30days30sites) actually links to great places where you can learn how to work with preprocessors
    * CSS Base and Vendor Prefixing selections
    * Add external CSS - here's where you paste the CDN links of the CSS you want to use. For example, I imported the Bootstrap and MDBootstrap CDNs here. So there's no need for you to use a <link> tag in the HTML editor!  
    Click the Quick Add to view a dropdown of some of the most popular CSS links like Bootstrap and Foundation, so you  don't have to manually copy-and-paste them.

### JavaScript
[js.PNG](/uploads/js.PNG)
    * Use a preprocessor like Babel or Coffeescript
    * Add external JS files like JQuery, Angular, and Vue. Use the Quick Add dropdown to quickly add some of the more popular frameworks.

### Behaviour  
 - deals with the behavior of this current pen.
    * Code indentation - basically how many spaces would appear if you pressed "tab"
    * Autosave - Codepen saves your code every once in a while. Toggle to turn it on or off.
    * Auto-updating preview - Codepen automatically reads your new code and then displays them in the preview every time you stop typing.  
    Toggle to turn this on or off. You want to turn this off if you're working on the pen for a long time, because Codepen can get flaky if you don't - it's a browser cache thing.
---
# Step 1
## Create a pen
[home.PNG](/uploads/home.PNG)
Click the nice little "Create" button on the top right corner of the page, then click "New Pen". You'll be met with a blank slate.

# Step 2
## Where the code goes
Here's an example of how you can begin working in the code editors.
[codeexample-ddcefa.PNG](/uploads/codeexample-ddcefa.PNG)
As you can see, there's no need for <head> or <body> tags in the HTML section. 

### Imports
I had previously imported Bootstrap and Jquery. There's no need for us to actually copy and paste Bootstrap code. What you see are the customization I'm making to the original CSS code. 

We'll be making a tutorial specifically geared at using Bootstrap with Codepen a little later on, so make sure you subscribe.

### Pre processors 
The CSS code editor has "(scss)" next to it because I opted to use the SCSS preprocessor in the settings page mentioned earlier.

# Step 3
## Save
[save.PNG](/uploads/save.PNG)
Even though you have Autosave on, it's still good practice to manually click the "Save" button before you exit the window. You can find the button in the navigation bar, towards the right of the screen.

## Rename
[rename.PNG](/uploads/rename.PNG)
If you click save without renaming your pen, Codepen generates a random set of numbers and letters as the default name, shown above. 

You can change this by clicking the little pen next to the set of random characters. Remember to hit "Save" one more time - just in case.

Name your pen so that it's easy for people to find your pen. If you're making a webpage for the [30 Days, 30 Sites](http://www.subscribepage.com/30days30sites) challenge, for example, name it something like: 30Days30Sites Day 1: xxx

# Step 4
## Collections
Since this tutorial was geared towards the [30 Days, 30 Sites](http://www.subscribepage.com/30days30sites) peeps, Collections will be especially useful for you. 

Collections are basically a tool to organize your pens. You can have many collections for all kinds of different purposes. So in our context, we can make a collection to store all 30 of our sites, so it's easier for people to find.

### Add to a collection
When you're done with your pen, you can add it to a collection. 
[collection1.PNG](/uploads/collection1.PNG)
Click the "Add to Collection" dropdown at the bottom left corner of your screen. 
[collections2.PNG](/uploads/collections2.PNG)

### Create a collection
If you haven't made a collection yet, you can make one by clicking the "Create new collection & add" option. A pop up will appear. In this example, you can fill it in like this. After you're done, click the green "Create" button.
[collections3.PNG](/uploads/collections3.PNG)
So the next time you create a pen for the challenge, you can add it directly to the collection, which will show up in the dropdown menu (no need to create it again!)

Quick tip: You can also add the same pen to different collections!

---

# That's a wrap for the basics, folks!
So far, you've learned:
* How to create a new pen
* How to import external assets (CSS, JS)
* How to use preprocessors
* How to change the behaviour of your pen (stop it from auto refreshing, turn on autosave, etc)
* How to save your pen
* How to rename your pen
* How to create a collection
* How to add your pen to a collection

That's a whole dang lot! Now, usually, if you're facing problems like dropdowns not working, site being not responsive, it's usually because you didn't import your CSS and JavaScript correctly. Remember to put the CDN links in the [CSS](#css) and [JavaScript](#javascript) settings respectively, **not** in the HTML code editor.

Let us know if you need any more help! 

Remember to stay tuned for the next edition of Codepen 101, where we will walk you through the process of coding a webpage using a framework like Bootstrap.

See ya!

Love,
Tris