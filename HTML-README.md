# HTML Basics

Below I will be going over some basics in my HTML file and how to use them with some basic CSS. For this demonstration, I will be using multi colored squares.

## The HTML Boilerplate

The boilerplate is your starting point for any project using HTML.

It looks like this:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

Alright, let's break that down, shall we?

### What does our boilerplate say?
 - It declares that our document will be written using *html*.
 - It declares the *html* is written in english.
 - Our *head* tag is the brains of the operation and it contains the behind the scenes info. It talks to your browser for you to make sure it understands your code
 - Our link to our stylesheet tells our document we have a file we will be using to give our document some styling. 
 - Our *title* tag is what will appear at the top of the page in the *browser* not in the document.
 - Our *body* tag is the content. This is all the info we want to convey through our *html*.

 **Important to Note**
 *Almost* all tags need an opening and a closing tag. The closing tag has a */* before the name of the tag, inside the *<>*. Self-closing and empty tags don't require a closing tag.

 Alright, our document has begun! But we don't have anything on the page yet...

 Time for some *divs*!

 Let's add in a *div* with a *class* of *container* for us to put our code in.

 **Class and ID are two ways to give a basic tag in your *html* (such as div) an identifier to make it easier to style with your *CSS*.**

 *Inside* that div, let's put three more. We are going to give the three *div's* a class of *square*.

 Alright, let's see what we have!

 ## Adding in our *div's*
 ```html
 <body>
    <div class="container">
        <div class="square" id= "rOne"></div>
        <div class="square" id= "rTwo"></div>
        <div class="square" id= "rThree"></div>
    </div>
</body>
 ```

 Looking good! Our *class* names make these *square div's* easy to manipulate as a group.
 Our individual *id's* allow us to manipulate each square on its own.


This is just a basic set up for a small document as a demo. Check out the *CSS* readme.md to add some style to your page!




