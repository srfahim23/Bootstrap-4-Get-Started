# Bootstrap-4-Get-Started
# What is Boostrap?
Boostrap is a free front-end framework for faster and easier web development

Boostrap includes HTML and CSS based design templates for typography, forms, buttons, tables, navigation, modals, image carousels and many other, as well as optional Javascript Plugins

Boostrap also give you the ability to easily crate responsive designs

# What is Responsive Web Design?
Responsive web design is about creating web sites which automatically adjust themeselves to look good on all devices, from small phones to large desktops.

Boostrap 4 Example

    <div class"jumbotron text-center">
        <h1>My First Boostrap Page</h1>
        <p>Resize this responsive page to see the effect!</p>
    </div>    

    <div class="container">
      <div class="row">
        <div class="col-sm-4">
            <h3>Column 1</h3>
            <p>Lorem ipsum dolor..</p>
        </div>    
            <h3>Column 2</h3>
            <p>Lorem ipsum dolor..</p>
        </div>    

        <div class="col-sm-4">
            <h3>Column 3</h3>
            <p>Lorem ipsum dolor..</p>
        </div>      
       </div> 
    </idv>  

Note: Including all of link just require for boostrap:

     <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
  <script src="https://cdn.jsdelivr.net/npm/jquery@3.6.3/dist/jquery.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>

# Boostrap Versions
This tutorial follows Boostrap 4, which was released in 2018, as an upgrade to Boostrap 3, with new components, faster stylesheetc, more responsiveness, etc.

Boostrap 5(releases 2021) is the newwest version of Boostrap; It supports the latest, stable releases of all major browsers and platforms. However,Internet Explorer 11 and down is not supported.

The main differences between Boostrap 5 and Boostrap 3 & 4, is that Boostrap 5 has swhitched to Javascript instead of jQuery.

Note: Boostrap 3 and Boostrap 4 is still supported by the team for critical bugfixes and documentation changed, and it is perfectly safe to continue to use them. However, new features will NOT be added to them.

# Why Use Boostrap?
Advantages of Boostrap:

. Easy to use: Anybody with just besic knowledge of HTML and CSS can start using Boostrap 

. Responsive features: Boostrap's responsive CSS adjusts to phones, tablets, and desktops

. Mobile-first approach: In Boostrap, mobile-first styles are part of the core framwork

. Browser compatibility: Boostrap 4 is compatible with all modern browsers (Chrome, Firefox, Internet Explorer 10+, Edge, Safari, and Opera)

# Where to Get Boostrap 4?
There are two ways to start using Boostrap 4 on your own web site 

You can:

Including Boostrap 4 from a CDN
Download Boostrap 4 from getboostrap.com 

# Boostrap 4 CDN
If ou don't want to download and host Boostrap 4 yourself, you can include it from a CDN (Content Delivery Network).

jDelivr provides CDN support for Boostrap's CSS and Javascript. You must also include jQuery:

jsDelivr:

    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">

    <!-- jQuery library -->
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.6.3/dist/jquery.slim.min.js"></script>

    <!-- Popper JS -->
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>

    <!-- Latest compiled JavaScript -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>

# One advantage of using the Boostrap 4 CDN:
Many users already have downloaded Boostrap 4 from jsDelivr when visting another site. AS a result, it will be loaded from cache when they visit your site, which leads to faster loading time. Also, most CDN's will make sure that once a user requests a file from it, it will be served from the server closest to them, which also leads to faster loading time.


# jQuery and Popper?
Boostrap 4 uses jQuery and Popper.js for Javascript components (like modals, tooltips, popovers etc). However, if you just use the CSS part of Boostrap, you don't need them.

Note:



    Closable alerts
    Buttons and checkboxes/radio buttons for toggling states
    Carousel for slides, controls, and indicators
    Collapse for toggling content
    Dropdowns (also requires Popper.js for perfect positioning)
    Modals (open and close)
    Navbar (for collapsible menus)
    Tooltips and popovers (also requires Popper.js for perfect positioning)
    Scrollspy for scroll behavior and navigation updates


# Downloading Boostrap 4
If you want to download and host Boostrap 4 yourself, go to https://getbootstrap.com/, and follow the instructions there.

# Create First Web Page With Boostrap 4
1. Add the HTML5 doctype

Boostrap 4 uses HTML elements and CSS properties that require the HTML5 doctype.

Always include the HTML5 doctype at the beginning of the page, along with the lang attribute and the correct charecter set:

    <!DOCTYPE html>
    <html lang="en">
        <head>
            <meta charset="utf-8">
        </head>    
    </html>    

2.Boostrap 4 is mobile-first
Boostrap 4 is designed to be responsive to mobile devices. Mobile-frist style are part of the core framwork.

To ensure proper rendering and touch zooming, add the following <meta> tag inside the <head> element:

    <meta name="viewpoert" content="width=device-width, initial-scale=1">

The width-device-width part sets the width of the page to fllow the screen-width of the device (which will very depending on the device).

The initial-scale=1 part sets the intial zoom level when the page is first loaded by the browser.

3.Containers

Boostrap 4 also requires a containing element to wrap site contents.

There are two container classes to choose from:

1.The .container class provides a responsive fixed width container

2. The .container-fluid class provide a full width container, spanning the entire width of the viewport

# Two Besic Boostrap 4 pages
The following examples shows the code for a besic Boostrap 4 page (with a responsive fixed width container):

Container example

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <title>Bootstrap Example</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.6.3/dist/jquery.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body>
  
    <div class="container">
    <h1>My First Bootstrap Page</h1>
    <p>This part is inside a .container class.</p> 
    <p>The .container class provides a responsive fixed width container.</p>           
    </div>

    </body>
    </html>

The following example shows the code for a besic Boostrap 4 page (with a full width container):

Container Fluid Example

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <title>Bootstrap Example</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
     <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
     <script src="https://cdn.jsdelivr.net/npm/jquery@3.6.3/dist/jquery.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body>
  
    <div class="container-fluid">
     <h1>My First Bootstrap Page</h1>
    <p>This part is inside a .container-fluid class.</p>
    <p>The .container-fluid class provides a full width container, spanning the entire width of the viewport.</p>           
    </div>

    </body>
    </html>
