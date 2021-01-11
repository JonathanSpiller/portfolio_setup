# Portfolio Project


In this project, you will build a portfolio site to showcase everything we have learned (and will continue to learn at Developers Institute).

This will be an ongoing project starting with plain HTML, CSS and the Bootstrap 4 framework.  As you progress through the next 2 weeks, you can add javascript and DOM manipulation to the project. Later you can make it a fully-fledged web app, incorporating a Database, Python via a Django backend and some more advanced concepts like asynchronous requests.  

At the end of this course, we will put our portfolios live!

**Don't Panic! We will learn what all of that means!**



# This project has 2 main goals:

1. To facilitate learning of new concepts. The best way to __really__ understand a concept is to use it in the real world. Building this portfolio site will allow you to practice everything you learn over the coming weeks.  Watch your portfolio site level up as your knowledge levels up!

2. To provide a showcase of what you can do.  At the end of this course, not only will you have learned to be Fullstack Developers. You will also have a github account full of exercises and projects.   In addition to that you will have a portfolio, live on the internet showcasing your work, links to your social media and github accounts and a good documentation and proof of your journey and skills as a programmer.

# Roadmap

Here are some optional ideas and a rough plan for this project:

**Week 1:** A responsive site using HTML and CSS. You can layout the site using Grid, Flexbox or a CSS framework (We learn Bootstrap 4. But feel free to look at other like Materialize,  Tailwind, etc.  [Here is a list of some great CSS frameworks.](https://www.mockplus.com/blog/post/css-framework) 

**Week 2 - 3:** Add some javascript. This could include some animations, or interaction with the user in response to clicks. A really nice idea would be to build a filter that allows the user to see only certain types of porojects. [Here is a great, simple example from w3shools.](https://www.w3schools.com/howto/howto_js_portfolio_filter.asp) 

**Week 6 - 10:** Add a django backend to your site. New projects can be added to the site with full __CRUD__ functionality. An admin backend and database can allow persistence of state changes.

**Ongoing:** Add some asynchronous request to your site.  A simple but good way to learn about asynchronous requests is to build a __Like__ button and add them to each project. This will also teach you some fundementals of HTTP request / response, JSON, Request Headers and Sessions.  Don't worry, we will cover it all!

# Lets Go!
**Remember: Be creative. The below sections are only ideas and suggestions. Feel free to do your own thing!**

# Setup

1. Clone or Download this repository to you local machine. It contains some sample images that you can use, as well as a screenshot of an example site you could build.  Grab what you need then delete the repo from your local machine. No need to keep it.
1. Create your own repository where you will build your portfolio. 

# Building the Site

Remember, you can modify your site however you feel. You can choose your own colors, or use standard ones.  Google around. There are some great portfolio sites out there to inspire you! 
The website does not have to work at this stage (links, buttons etc). It just has to look good with HTML and CSS. You can come back later and add functionality.

## Getting Started
1. Create a root folder for your project called "profile", or whatever you like, wherever you like, even the desktop is fine.
1. Copy the images folder into your new root folder. All the image files you need are available from the Setup step above. You can download more images as needed.
1. In the root folder, create two new files, index.html and main.css. 

## Setting up the Template

1. Choose a font for your site. You can find some good ones using the google fonts api.  Raleway is a nice one for this site, but you can choose any you like. You can include them in your css using:
    ```css
    @import url('https://fonts.googleapis.com/css?family=Raleway');
    
    html,h1,h2,h3,h4,h5,h6,a{
        font-family: "Raleway";
    }
    ```
1. Reset your template (google "css reset" if you don't know). 
1. Add the required parts to make it a proper HTML page.
Add semantic tags for the navbar, header, and multiple profile sections. 

## Navbar

1. Use the navbar provided by Bootstrap. Modify it for your needs.
* **Note** the navbar has class "fixed-top" which gives it an fixed position at the top of the page.

## Header

1. Set the header background-image. 
1. Make the background-attachment fixed so we can overlay things on top of it.
1. Make the background-size cover the whole div.
1. Set background-position to center
1. When writing on the header, remember to give the text an absolute position.
* **Note** The header should take 100% of the screen size. Remember how to do that in pure CSS?

### Overlay

1. You can make an overlay by placing `<div id="overlay"></div>` directly inside your header.
1. You can style similarly to https://www.w3schools.com/howto/howto_css_overlay.asp. Try make it white to fade out the background image.

## The Sections

1. Space them nicely
1. Keep things responsive by using the Bootstrap grid.
1. For the *Blog* section, use Bootstrap4 "Cards". They are prebuilt elements ready to use."
1. For the *Contact* section, use a form and the Bootstrap form controls.
1. You can add social media icons using one of Bootstraps recommended Icon Sets.

# ! Important !

1. Work hard!
1. Focus!
1. Help eachother!
1. Work in pairs to solve problems and figure things out. It's a great way to learn!
1. Ask for help! But first, give a few different solutions a good try.
1. Enjoy!
