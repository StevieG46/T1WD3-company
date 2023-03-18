# Coder Academy - Portfolio

## Overview
This a portfolio website for displaying the services that Coder Academy provides. This is in development phase and we will kepp on adding those features in this readme that we add on the website.

## Components

### Header
Header has logo and name of the company along with the navigation bar. Here is the code for the header we have:
```html
<header>
        <div class="logo-name">
            <a href="./index.html">
                <img src="./images/logo.png" alt="Coder Academy Logo">
            </a>
            <p class="name">
                <span class="coder-text">Coder</span>
                <span class="academy-text">Academy</span>
            </p>
        </div>
        <nav class="nav-items">
            <a href="./pages/about.html">About</a>
            <a href="./pages/services.html">Services</a>
            <a href="./pages/contact.html">Contact</a>
        </nav>
    </header>
```


### Footer
Footer has social media links, cpontact number and address. Here is the code that we have:
```html
<footer>
        <div class="social-media">
            <a href=""><i class="fa-brands fa-github"></i></a>
            <a href=""><i class="fa-brands fa-linkedin"></i></a>
            <a href=""><i class="fa-brands fa-square-instagram"></i></a>
        </div>
        <div class="info">
            <p>Contact: 0404040404</p>
            <p>Adfress: 1 Street St, Suburb</p>
        </div>

    </footer>
```
## Pages

### Home
Home page, for now, jsut displays some lorem ipsum text.
Here is the code that we have used:
```html
<main>
        <section>
            <div class="jumbotron">
                <img src="./images/jumbotron.jpg">
            </div>
            <div class="details">
                <p>
                    Lorem Ipsum text
                </p>
            </div>
        </section>
    </main>
```
### Services
Services Pages list services we provide

### Contact Page 
Contact Page can be used to contact the company

### About Page
About page is about us.

### Styling
Services page displaya the list of services that we provide. 


### Components
These will contain the styling of indiviudal components which are as following at the moment:
- Header
- Footer

### Defaults
This will contain the default variables such as colors, breakpoints, etc.

### Pages
This will contain the styling of each indiviudal html pages.

