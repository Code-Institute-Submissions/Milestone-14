CODE INSTITUTE MILESTONE 1: 
===========================
A TRIBUTE TO THE MIGHTY NEIN
----------------------------
>This frontend site is a tongue-in-cheek webpage for the fictional group "The Mighty Nein". Originally from the Dungeons and Dragons game under [Geek and Sundry](https://geekandsundry.com/) – though now exclusively the property of [Critical Role](https://critrole.com/) – this fictional group of mercenaries (blades for hire) travel around the made-up world of Exandria, completing quests for coin.
>This website exists under the pretence that the Mighty Nein are a real group available for hire, and, as such, provides some information about the members of the group (including links to character pages) as well as a contact form to enquire about hiring, links to social media, and an embedded video from their animated series, showing off some of their skills.

### External User’s Goal: ###

 * The site’s users are employers and potential employers of the Mighty Nein, who want to know more about the group and get in contact. 
 
### Site Owner’s Goal: ###

 * The Mighty Nein are interested in attracting and maintaining clients, and gathering new quests

### Features include: ###

 * Showcase images of the group, and a video clip of their adventures
 * Publicise availability and event dates, alongside social media
 * Provide detail about specific members, with link to character information

DEMO
----
A live demo of the site can be found [here](https://rhombencephalon.github.io/Milestone-1/) (GitHub Pages). 


UX
--

As a potential employer, I expect to get an quick impression about the group – with more in-depth information clearly accessible – to decide whether to hire them. 

As a fan of the Mighty Nein, I expect to find information about my favourite members, alongside ways of following their exploits.

### Strategy ###

As a group, the Mighty Nein is a goofy mixture of characters who are thrust into world-ending problems and a war between two nations. As such, I wanted to strike a balance between epic adventure and fun whimsy in the UI for this page; the Mighty Nein are very accomplished sellswords but are not always the most professional. For potential employers, the page 
needed to have a clear, easy-to-navigate layout, with information easily accessible, and the personality of the group conveyed. 

### Scope ###

For fans of the Mighty Nein, I wanted them to be able to find their favourite members quickly in an interactive carousel, alongside plenty of access points for more in-depth information. The about section and the short video clip enables employers to rapidly get a feel for the group, with a contact form should they wish to enquire about hiring the Mighty Nein.

### Structure ###

For the character carousel, I wanted a clear overview of the numerous characters, alongside specific links to their wikipages. I wanted both fans and employers to be able to get specific information within three clicks; one to get on to the website, one on the navigation bar to jump to whicherver section of interest, and one to interact with their area of choice - more character information, starting the video, following a social media link, or contacting the group.

### Skeleton ###

The initial wireframes were pen-on paper, and can be found as jpegs under the ‘wireframes’ folder of this project ([Mobile Sketch 1](./WireFrames/Mobile-Sketch-1.jpg) and [Mobile Sketch 2](./WireFrames/Mobile-Sketch-2.jpg), and [Website sketch 1](./WireFrames/Website-sketch-1.jpg) and [Website sketch 2](./WireFrames/Website-sketch-2.jpg) ). 

The secondary wireframes, created using Adobe XD, are in the same folder ([M9 Mobile](./WireFrames/M9-Mobile-Wireframe.jpg) and [Web wireframes](./WireFrames/M9-Web-Wireframe.jpg) ). 

### Surface ###

The deep blues and bright oranges were chosen to give a dynamic, exciting feel, and to fit with the group colours of the Mighty nein. 


FEATURES
--------
There are 8 main components to this site:

1. Navigation bar 
    * Allows user to navigate to sections of the page directly, without scrolling. Contains logo linking to the Critical Role official website.
    
2. Parallax image 
    * Create a visual impact upon entering the page, including title and subtitle.
    
3. About section
    * This section gives users some overall information about the Mighty Nein, and why the user might want to hire them.
    
4. Character Carousel 
    * This interactive scrolling carousel gives more specific information (name and fighting class) about each of the members of the Mighty Nein, including providing links to : each character's wiki page.
    
5. Video Link
    * Allows the user to watch a short introduction video displaying the Mighty Nein's skillsets.
    
6. Contact form 
    * Allows the user to contact the Mighty Nein to hire or enquire for more information (at the moment, no backend).
    
7. Social media links
    * Allows the user to find out more information about the Mighty Nein and follow them on various social media.
    
8. Footer 
    * Provides upcoming live dates and extra contact information.


FEATURES LEFT TO IMPLEMENT
--------------------------
The first and most obvious addition would be to ensure full functionality of the contact form, including a user message upon successful form submission.

During the inital creation of this site, I tried my hand at using a combination of SCSS/SASS and CSS3 Compass to create a layered parallex scrolling effect inspired by the [Firewatch game website](http://www.firewatchgame.com/). While I managed to create a function single page with this effect, I ran into some trouble when getting the layers to act responsively across differing screen sizes, so I decided to strip this effect. As such, I would like to reinstate this effect - using javascript this time, instead of relying purely on CSS effects. 

I would also like to create character sheets that users can download attached each character card within the carousel, rather than linking users to the character wiki (an external site). Finally, I'd like to implement an interactive timeline/ record of Mighty Nein victories, so that users can get a feel of the group's achievements thus far.


TECHNOLOGIES USED
-----------------
[Adobe XD](https://www.adobe.com/products/xd.html) 
    --> this was used to develop coloured wireframes

[Bootstrap](https://getbootstrap.com/) 
    --> front-end component library used for DOM and framework

[JQuery](https://jquery.com/)
    --> simplify DOM manipulation, and originally to allow the active scrolling status of the character carousel, though this was later replaced by Flickity's framework. 
    
[Fontawesome](https://fontawesome.com/)
    --> for social media symbols
    
[Googlefonts](https://fonts.google.com/)
    --> for cross-page font styling
    
[Flickity](https://flickity.metafizzy.co/)
    --> library - used for responsive carousel, with multi-cell display. Inner carousel cards reliant on bootstrap styling.
    
[SCSS/SASS](https://sass-lang.com/) and [CSS3 Compass](http://compass-style.org/) were used for the original attempt at creating a multi-layered parallax scrolling effect, as seen in previous versions of the site. Both technologies were removed when this scrolling effect was scrapped.

TESTING
-------
### Automated Code Testing ###

The HTML of [Index.html](./index.html) was auto-checked through [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input). By inputting the file, and running the check, I confirmed that the HTML was clear of any basic errors, getting the result of ‘Document checking completed. No errors or warnings to show.’

The CSS of [style.css](./assets/css/style.css)  was auto-checked through [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input). As with the HTML, I confirmed that the css stylesheet was clear of any basic errors by inputting the file into the automated system and running the check. The resulthere was ‘This document validates as CSS level 3 + SVG !’ i.e. with no errors found.

I used [Responsinator](https://www.responsinator.com/) to check cross-platform website functionality, confirming that my break points/ media queries functioned correctly and responsively across different screen sizes. A screencapture of this may be found in the test-results folder as [responsive.mp4](./Test-Results/responsive.mp4)

### Manual User Story Testing ###

All of the clickable links take the user to the correct corresponding webpage, using the target_blank attribute to open these links in a new tab. 

The sub-heading "seekers of adventure. And Coin. And Donuts. And Shiny Things. And Educational Stuff", is set to be hidden on smaller screen sizes, as is the image of the mighty nein in the about section. This is to make the site experience less cluttered when using e.g. mobile.  

Carousel:
Use the navbar to jump to the "Character" section
Try to scroll using edge buttons, verify that horizontal scrolling occurs
Try to scroll using navigation dots, verify that horizontal scrolling occurs
Try to scroll using click and drag, horizontal scrolling occurs
Try to follow embedded character link, verify this link opens the character wiki in a new tab 


Video:
Use the navbar to jump to the "Watch us in Action" section
Try to play video, verify this starts the video on mute
Try to change volume, verify volume control functions normally
Try to change video to fullscreen and back, verify this does not affect playback


Contact form:
Use the navbar to jump to the "Contact" section
Try to submit empty form, verify error appears in required fields
Try to submit form with invalid email, verify email-specific error message is generated
Try to submit with all valid input types, recieve no error messages

I had some issues with bootstrap's autopadding, so overrode this is my own stylesheet.


DEPLOYMENT
----------

This site is hosted on GitHub pages, deployed directly from the master branch. The GitHub hosted live site auto-updates according to new repository pushes. By cloning the code on the GitHub pages, you can also run it locally on your machine.


CREDITS
-------
### Content ###

The text for the about section was written by myself. All other text content is externally linked.

Inspiration for basic webpage layout from [***Drew Ryan***](https://www.youtube.com/channel/UCtXGz0MBuqZUC8rmGddc07Q). Code for all sections of the page significantly modified; the inspiration was largely stylistic, and has drastically changed across versioning. 

Implementation of flickity was drawn from flickity documentation, found on the flickity [website](https://flickity.metafizzy.co/)

Styling for iframe inspired by [embed responsively](https://embedresponsively.com/), though largely modified


### Media: ###

Official critical role art is done by Ari ([@ornerine](https://twitter.com/ornerine)), and may be found at:

**Jester image:**

https://pbs.twimg.com/profile_images/954040496544010241/bBcHcX7a.jpg

**Yasha image:**

https://vignette.wikia.nocookie.net/criticalrole/images/9/92/Yasha.jpg/revision/latest/scale-to-width-down/310?cb=20180116194508

**Fjord image:**

https://vignette.wikia.nocookie.net/criticalrole/images/2/24/Fjord.jpg/revision/latest?cb=20180116194444

**Caleb image:**

https://vignette.wikia.nocookie.net/criticalrole/images/9/92/Caleb_Widogast.jpg/revision/latest?cb=20180116194349

**Caduceus image:**

https://vignette.wikia.nocookie.net/criticalrole/images/7/78/Caduceus_portrait.jpg/revision/latest?cb=20180727064924&format=original

**Mollymauk image:**

https://vignette.wikia.nocookie.net/criticalrole/images/c/ce/Mollymauk.jpg/revision/latest/scale-to-width-down/310?cb=20180116194455

**Beauregard image:**

https://vignette.wikia.nocookie.net/criticalrole/images/3/3e/Beauregard.jpg/revision/latest/scale-to-width-down/310?cb=20180116194433

**Nott image:**

https://vignette.wikia.nocookie.net/criticalrole/images/d/dc/Nott.jpg/revision/latest?cb=20180116194408

**Keg image:**

https://vignette.wikia.nocookie.net/criticalrole/images/3/3d/Keg_portrait_by_Ari.jpg/revision/latest?cb=20180713210444

**Nila image:**

https://geekandsundry.com/wp-content/uploads/2018/07/sumaleeportrait.png

**Reani image:**

https://vignette.wikia.nocookie.net/criticalrole/images/0/08/Reani_-_Official_Art_Portrait.jpg/revision/latest?cb=20190812205713

**Shakäste image:**

https://media-waterdeep.cursecdn.com/attachments/3/464/shakaste.jpg

**Twiggy image:**

https://vignette.wikia.nocookie.net/criticalrole/images/7/7e/Twiggy_Portrait_by_Ari.jpg/revision/latest?cb=20181214042136

**M99 image:**

https://vignette.wikia.nocookie.net/criticalrole/images/9/9c/Mighy_Nein_by_Ariana_Orner.png/revision/latest?cb=20190906065232

**Logo image:**

https://thelongshotist.com/wp-content/uploads/2017/09/CriticalRole_Logo.png

**Parallax image (BBG):**

http://hdqwalls.com/wallpapers/warriors-mighty-nein-minimalist-art-85.jpg


THIS SITE IS FOR EDUCATIONAL PURPOSES ONLY
==========================================
