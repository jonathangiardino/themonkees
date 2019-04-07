
# The Monkees - Official Website 

Stream One Project: User-Centric Frontend Development - Code Institute 
This is an offical music-band website for old and new fans.

The website highlights the most popular band's tracks, their next live shows as well as a video clip showing the band in action.
Furthermore it advertises that the band is available for live shows on demand and it has links to all social networks and a form to get in touch with the band management directly.

## Demo
A live demo can be found [here](https://jonathangiardino.github.io/themonkees/).


## UX
### User needs / Business objectives
- Audio clips available
- Video Clips available
- Gigs list
- Contact form to request events performances 
- About me for brief intro to new fans
- Social networks

### Scope - Functional and content specification
- Songs available for listening with cover
- Video of a performance 
- Concerts list
- Linking to Social networks integrated
- All in one scrolling page to maintain focus on one page and content

### Structure
Buttons available are the Navbar buttons which send you yo the different sections of the scrolling page, therefore the user never leaves the page and has all the contents available all the time.The rest ion the clickable buttons are the the links to concerts and the call to action in the top right corner and the form. Adding a Modal only for the form completion.

### Skeleton
- Navbar
- Home Picture of the Band with logo
- Songs
- Video + About us
- Gig list
- Form
- Footer

### Wireframes / Surface
I have composed [these wireframes](https://github.com/jonathangiardino/themonkees/tree/master/wireframes) before starting the project based on UX strategy above.

## Technologies
1. HTML
2. CSS
3. Bootstrap (4.3.X)


## Features
This site uses buttons, Navbar and grid list features from Bootstrap and an extra Modal Javascript function for the modal.
The navbar is transparent in order not top disturb the UX while scrolling.
All the buttons have hovering color change, the home page is completely transparent including a photo of the band fixed and the official logo.
I have coloured the buttons in red following the original band color logo.



## Testing
All links (Social networks, Live shows Get tickets buttons)  will open in a new tab using 'target="_blank"'.
By clicking on the links in the navbar, you will be brought to the relative section.
When brought to the form the *Get in touch* button brings up a Modal form to request info, which works perfectly on mobile as well.
This site was tested across multiple browsers (Chrome, Safari, FireFox) and on multiple mobile devices (iPhone 6, 7, 6 Plus) to ensure compatibility and responsiveness. 

During the testing phase, I realized that the Background image was too blurred and did not make sense to leave it there hence on mobile, then I decided to make the home page black using a media query.
I used media queries for the mobile version also for centering *h2* and resizing the music players in the music section as the title did not look right and the music player overlapped.
Furthermore I used media queries for iPad as the about us section re-sized responsively for iPads and the video was to on top and there was too much empty space in the section.

After further review with my mentor I have noticed that images and media did not have absoulte paths and some of the media did not show hence I had to 
change the paths and then all worked perfectly.

Furthermore, since is a one-scroll page website, whenever clicking on one of the links in the Navbar there was no transition and ypu'd be taken to each section very quickly. 
Hence I added the attribute *scroll-behaviour: smooth;* to **html** and now the transition from the navbar links is smoother.
However this attribute does not work on **Safari, Edge and Explorer**, but it works on **Chrome, Firefox and Opera.**

After some research I realized there is no way to make the smooth scroll work without using a script but since is pout of scope for this project I thought I'd just mention it here.

I have validated the HTML code on [W3C Markup Validator](https://validator.w3.org/) and CSS code on [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) and fixed all the errors shown.


## Deployment
This site is hosted using GitHub pages, deployed directly from the [master branch](https://github.com/jonathangiardino/themonkees).
Clicking on [Settings](https://github.com/jonathangiardino/themonkees/settings), and scrolling down to the section GitHub pages, I have selected
as source *Master Branch* and deployed my work [here](https://jonathangiardino.github.io/themonkees/)

## Credits
- icon-navbar, gigs and social from Fontawesome
- Logo Monkees source [here](https://www.kisspng.com/png-the-monkees-logo-pantages-theatre-musical-ensemble-1123111/)

### Content
All content in the "About Me" section are taken from [Wikipedia](https://en.wikipedia.org/wiki/The_Monkees)

### Media
All photos and videos were given by Code institute for educational purposes except for the logo which was downloaded from [here](https://www.kisspng.com/png-the-monkees-logo-pantages-theatre-musical-ensemble-1123111/)


**This is for educational use.** 