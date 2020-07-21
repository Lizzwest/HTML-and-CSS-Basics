# CSS Basics

Below is the CSS file for my HTML document. It adds the *style* to my page.

## What do CSS and HTML have in common?

 They use the same identifiers! 
 Wait, they what? 
    
 Let's break that down. The *tags*, *class names* and *id's* we used in our *html* will be used once again in our *css*. So if I want to give my entire *body*, say, a background of blue, I would use that tag *inside* my CSS and give it a color of blue! Still confused? Let's see what it looks like below!

 ```css
 body{
    background: blue;

}
 ```

 Ta-dah! A blue page! We just created our first *style* for our document! But you know, this blue page is a little... boring. It also doesn't show me my container or my squares! Lets add some color to each of them so we can see them! We are also gonna give them some sizing, so we can tell them apart!

 ```css
 }
.container{
    height: 900px;
    width:  900px;
    background: black;
}


#rOne{
height: 200px;
width: 200px;
background: red;
margin: 10px;
padding: 10px;


}

#rTwo{
    height: 200px;
    width: 200px;
    background: orange;
    margin: 10px;
    padding: 10px;
   
}
#rThree{
    height: 200px;
width: 200px;
background: yellow;
margin: 10px;
padding: 10px;

}
 
 ```

 Our page now has three bright squares(our *square id's*), on top of one black square(our *container class*) sitting inside our big blue background(our *body tag*).

 With me so far? Great! But I am sure you are wondering.... *what is padding and margin?*??

 Let's get into some TRBL! No, not trouble, TRBL. It's and acronym. It stands for Top, Right, Bottom and Left. Basically, this means:

 - We can style individual spacing around each element through our margin, padding and our border. 
 - To do this, we put values for each side we can to add space to. You can do this a couple of ways. You can also do one size after your padding, margin or border to give it equal space on it's sides.

 ##  Let's get our circles in the center of the page! But how?

 Lets add some position, and display to our boxes!

 ## Centering our squares

 ```css

#rOne{
height: 150px;
width: 150px;
background: red;
margin: 50px;
padding: 50px;
display: inline-block;
position: relative;


}
 ```

 So, looking at our squares, they are in the center of our screen! We used *position: absolute* on our parent element, our container and added *position: relative* to our squares by ID. We also gave the squares a *display: inline-block* to get them shifted into the center.


 This is Just a brief summary of some basic CSS kknowledge, based off my html file. I will continue to update these as I dive into more advanced CSS.