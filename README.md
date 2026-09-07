Amity Coding Club (ACC) Website

I developed a one-page website for the Amity Coding Club (ACC) to showcase the club, its activities, events, team members, achievements, and ways for students to connect with us.

The main idea was to make the website feel like a small web application rather than a collection of separate pages. Everything is present in a single HTML file, and I used JavaScript to show the section selected by the user without reloading the page.

Project Overview

The website contains sections such as:

Home
About
Events
Gallery
Team
Achievements
Podcasts
Join Us
Contact

Users can move between these sections using the navigation menu while the page stays loaded in the browser.

I also added features like:

A short intro animation when the website starts, with coding-related doodles and graphics.
A light/dark mode for changing the website's theme.
A hamburger menu for navigation, especially on smaller screens.
An interactive photo gallery, where users can open images in a larger view and move between them.
A responsive layout that adapts to different screen sizes.
A contact section with links to WhatsApp, Discord, Instagram, and LinkedIn.
A contact form for users who want to get in touch with the club.
Technologies Used

I built the project using basic web technologies:

HTML – I used HTML to create the structure and content of the website.

CSS – I used CSS for the overall design, layout, colors, responsive behaviour, and animations.

JavaScript – I used JavaScript for interactive features such as navigation, theme switching, the menu, intro animation, and gallery functionality.

I also used Google Fonts, mainly Fredoka and JetBrains Mono, to match the visual style of the website.

I didn't use frameworks such as React or Bootstrap. I built the website using plain HTML, CSS, and JavaScript.

The icons and some graphics are created directly in the code, and the images are also stored within the HTML file, so the project doesn't depend on multiple separate assets.

How the Website Works

I designed the website as a single-page application-like interface.

Instead of creating separate HTML files for About, Events, Team, etc., all the sections are present in the same HTML file. JavaScript controls which section is visible when the user selects something from the menu.

This makes navigation feel faster because the browser doesn't have to load a completely new page every time.

Design Approach

I initially designed the website with mobile users in mind and then added responsive styling for larger screens.

I tried to keep the design consistent throughout the website by reusing the same card and button styles across different sections.

I also organized the colors using CSS variables, so changing the theme doesn't require changing individual elements one by one.

I kept the animations relatively short so that they add some interaction without making the website feel slow or distracting.

Running the Project

There is no complicated setup required.

Since everything is contained in a single HTML file, the website can simply be opened by double-clicking:

acc-site.html

It can also be run using a local server for testing:

python3 -m http.server 8000

Then open:

http://localhost:8000/acc-site.html

There is no build process, package installation, or compilation required.

External Dependency

The only external dependency currently used is Google Fonts, which requires an internet connection to load the selected fonts.

Apart from that, the main website functionality is contained within the HTML file itself
