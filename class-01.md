## Reading Day: 01

## Responsive Web Design and Floats

As we worked on our 201 final project I could anticipate that responsive web design would be in our future soon. And here we are! I taught myself **RWD** about 4 years ago when I was redesigning a site for a company I worked for. From what I could remember Google was not going to list a site unless it was responsive.

## What it is
Responsive design is the practice of building a site that responds to size screens. A desktop is different from a tablet which is different than a cell phone. A successful RWD makes a site look correct on all devices. 

## Three Main Components
There are 3 main components:
1. Flexible Layouts
1. Media Queries
1. Flexibel Media

**Flexible Layouts** is the practice of building a website layout with a flexible grid capable of resizing. The grids are built using relative length units most commonly percentages and ems.
Flexible layouts do not use fixed measurements such as pixels or inches because website layouts need to adapt to different size screens.

## Media Queries
Media Queries provide the ability to specify different styles for individual browser and device circumstances. Media Queries can also block content; say if there were an animation meant for a full screen and viewing it on a mobile device is too confusing, the query would block unnecessary downloading.  

## Logical Operators
Logical Operators are used in media queries to help build expressions. There are three different logical operators:
1. and
2. not
3. only 

**and** allows an extra condition to be added. **not** negates the query.
[and](images/and.jpeg)

## Media Features
One of the most common media features is using the **Height and Width** which help build responsive websites on desktops and mobile devices. Other media features include: Aspect and Pixel ratios and identifying available output colors.

## Designs and Breakpoints
When building a responsive website it should adjust to different viewport sizes, regardless of the device. **Breakpoints** allow you to change to a certain media size. It will change a screen size when a website size gets adjusted and starts to look "wonky" or broken.

## Mobile First
I remember hearing the prediction 5 years ago that the future of web access would be on mobile devices. I thought it was a ridiculous idea. Ha, how I was wrong!

**Mobile First** is the belief that the user is on a mobile device and viewing on a smaller screen. This design approach is for mobile users in mind. Media queries also point to specific CSS for styling mobile devices. 

## Viewport Height and Width
For best layout results it is recommended that 'device-width' and 'device-height' values are used. This allows the website to be sized properly and to follow any qualifying media queries. 

## Flexible Media
An important aspect of responsive design includes having media (images, videos) be scalable. One way to make media scalable is by using the max-width property with a value of 100%. Max-width is not a solution for sizing all media types though. It doesn't work specifically with embedded media and iframes. 

The solution with sizing embedded images, the element needs to be absolutely positioned in the parent element. The parent needs to have a width of 100% so it will scale based on the width of the viewport. Padding is then given to the bottom of the parent element, the same aspect ratio of the video. 

This is especially interesting to me as in the past I've struggled getting embedded media to size and caused huge frustration. This article is helpful and a great resource.

# Floats
A **Float** is a CSS positioning property which allows you to position something on the left or right hand size of whatever box it is placed inside of. It is incredibly helpful for page layouts. Float removes the absolute positioning of the flow and there are four valid values of the float property. 3 of them I've used before. 
- float: left;
- float: right;
- float: none;
- float: inherent;

**Float: none** is a default and ensures an element will not float. **Float: inherent** is a property I've yet to use. Using this property will assume the float value from the elements parent element. 

## Clearing Floats
Clearing a float ensures that floats do not occur. **Clear Both** clears floats coming from either direction. Left or Right can be used to clear a float specifically on either side.

I had another 'A-ha' moment that took me back 4 years ago when I was positioning divs and repeatedly using floats. The issue I was having was that the parent div would collapse. It didn't make any sense... until reading this article. What I didn't do was to clear each float.

Okay, I got really interested in clearing floats using the following methods:

- The Empty Div Method
<div style="clear: both;"></div>
- The Overflow Method
- Easy Clearing Method

The following is the 'Easy Clearing Method'. Okay, I think I'll get a tattoo of this so I don't forget:

.clearfix:after { 
   content: "."; 
   visibility: hidden; 
   display: block; 
   height: 0; 
   clear: both;
}
OMG... Life would be easier if there was no Internet Explorer. That is my short rant. Just reading about it's limitations brought up some past issues I've dealt with.

## Flexbox
Okay this is going to be my next tattoo: 

.container {
  display: flex; /* or inline-flex */
}

Flexbox is just damn cool. We used it on our 201 final and it's like a positioning magic wand.

## CSS Floats Explained by an Escalator
I especially liked the visual representation of people on an escalator to explain float left and float right. Using float can get confusing if you don't clear the floats as I mentioned earlier in my personal experiences with parent elements collapsing from not clearing.


[<== Back to Table of Contents](index.md)