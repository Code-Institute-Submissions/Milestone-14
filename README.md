CODE INSTITUTE MILESTONE1:A TRIBUTE TO THE MIGHTY NEIN
======================================================
***
This frontend site is a tongue-in-cheek webpage for the fictional group "The Mighty Nein". Originally from the Dungeons and Dragons game under [Geek and Sundry](https://geekandsundry.com/) – though now exclusively the property of [Critical Role](https://critrole.com/) – this fictional group of mercenaries (blades for hire) travel around the made-up world of Exandria, completing quests for coin.
This website exists under the pretence that the Mighty Nein are a real group available for hire, and, as such, provides some information about the members of the group (including links to character pages) as well as a contact form to enquire about hiring, links to social media, and an embedded video from their animated series, showing off some of their skills.

External User’s Goal:
---------------------
 * The site’s users are employers and potential employers of the Mighty Nein, who want to know more about the group and get in contact. 
 
Site Owner’s Goal:
------------------
 * The Mighty Nein are interested in attracting and maintaining clients, and gathering new quests

Features include:
-----------------
 * Showcase images of the group, and a video clip of their adventures
 * Publicise availability and event dates, alongside social media
 * Provide detail about specific members, with link to character information


UX
==
***
As a potential employer, I expect to get an quick impression about the group – with more in-depth information clearly accessible – to decide whether to hire them. 

As a fan of the Mighty Nein, I expect to find information about my favourite members, alongside ways of following their exploits.

Strategy
--------
As a group, the Mighty Nein is a goofy mixture of characters who are thrust into world-ending problems and a war between two nations. As such, I wanted to strike a balance between epic adventure and fun whimsy in the UI for this page; the Mighty Nein are very accomplished sellswords but are not always the most professional. For potential employers, the page 
needed to have a clear, easy-to-navigate layout, with information easily accessible, and the personality of the group conveyed. 

Scope
-----
For fans of the Mighty Nein, I wanted them to be able to find their favourite members quickly in an interactive carousel, alongside plenty of access points for more in-depth information. The about section and the short video clip enables employers to rapidly get a feel for the group, with a contact form should they wish to enquire about hiring the Mighty Nein.

Structure
---------
For the character carousel, I wanted a clear overview of the numerous characters, alongside specific links to their wikipages. I wanted both fans and employers to be able to get specific information within three clicks; one to get on to the website, one on the navigation bar to jump to whicherver section of interest, and one to interact with their area of choice - more character information, starting the video, following a social media link, or contacting the group.

Skeleton
--------
The initial wireframes were pen-on paper, and can be found as jpegs under the ‘wireframes’ folder of this project ([Mobile Sketch 1](./WireFrames/Mobile-Sketch-1.jpg) and [Mobile Sketch 2](./WireFrames/Mobile-Sketch-2.jpg), and [Website sketch 1](./WireFrames/Website-sketch-1.jpg) and [Website sketch 2](./WireFrames/Website-sketch-2.jpg) ). 

The secondary wireframes, created using Adobe XD, are in the same folder ([M9 Mobile](./WireFrames/M9-Mobile-Wireframe.jpg) and [Web wireframes](./WireFrames/M9-Web-Wireframe.jpg) ). 

Surface
-------
The deep blues and bright oranges were chosen to give a dynamic, exciting feel, and to fit with the group colours of the Mighty nein. 


FEATURES
========
***
There are 8 main components to this site;
    1. Navigation bar 
        : Allows user to navigate to sections of the page directly, without scrolling. Contains logo linking to the Critical Role official website.
    2. Parallax image 
        : Create a visual impact upon entering the page, including title and subtitle
    3. About section
        : This section gives users some overall information about the Mighty Nein, and why the user might want to hire them.
    4. Character Carousel - 
        : This interactive scrolling carousel gives more specific information (name and fighting class) about each of the members of the Mighty Nein, including providing links to : each character's wiki page.
    5. Video Link
        : Allows the user to watch a short introduction video displaying the Mighty Nein's skillsets.
    6. Contact form 
        : Allows the user to contact the Mighty Nein to hire or enquire for more information (at the moment, no backend).
    7. Social media links
        : Allows the user to find out more information about the Mighty Nein and follow them on various social media.
    8. Footer 
        : Provides upcoming live dates and extra contact information.


FEATURES LEFT TO IMPLEMENT
==========================
***
During the 
I would like to create character sheets that users can download attached each character card within the carousel, rather than linking users to the character wiki (an external site).
I would also like to implement an interactive timeline/ record of Mighty Nein victories, so that users can get a feel of the group's achievements thus far.
I would like to reinstate the parallax scrolling effect, with separate layers, to create perspective and a feeling of adventure.


TECHNOLOGIES USED
=================
***
[Adobe XD](https://www.adobe.com/products/xd.html) - wireframes
[Bootstrap](https://getbootstrap.com/) - framework
[JQuery] - this project uses Jquery to both simplify the DOM manipulation, and originally to allow the active scrolling status of the character carousel, though this was later replaced by Flickity's framework. 
[Popper.js] - as above
[Fontawesome] - for social media symbols
[Googlefonts]
[Flickity](https://flickity.metafizzy.co/) - library/ framework - used for responsive carousel, with multi-cell display
[SCSS/SASS](https://sass-lang.com/) and [CSS3 Compass](http://compass-style.org/) were used for the original attempt at creating a multi-layered parallax scrolling effect, as seen in previous versions of the site. Both technologies were removed when this scrolling effect was scrapped.




TESTING
=======
***
HTML has been validated through --> https://validator.w3.org/#validate_by_input --> with the result of ‘Document checking completed. No errors or warnings to show.’ i.e. with no errors found.
CSS has been validated through --> https://jigsaw.w3.org/css-validator/#validate_by_input --> with the result of ‘This document validates as CSS level 3 + SVG !’ i.e. with no errors found.
Cross-platform website functionality has been tested through --> https://www.responsinator.com/ , to check responsiveness to different screen sizes



In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


DEPLOYMENT
==========
***
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.


CREDITS
=======
***
Content
The text for the about section was written by myself. All other text content is externally linked.

Inspiration from Drew Ryan:
https://www.youtube.com/channel/UCtXGz0MBuqZUC8rmGddc07Q

Inspiration/tutorial for parallax from:
http://www.firewatchgame.com/
https://medium.com/@electerious/parallax-scrolling-with-js-controlled-css-variables-63cfe96820c7#.o1kkd4cte
https://basicscroll.electerious.com/
https://codepen.io/zabielski/pen/MyoBaY
https://codepen.io/scottkellum/pen/bHEcA
https://codepen.io/tribex/pen/mWNWdz
https://codepen.io/samdbeckham/pen/OPXPNp


Media:
The images used on this site were obtained from a variety of sources, and may be foound at:

Jester image:
https://pbs.twimg.com/profile_images/954040496544010241/bBcHcX7a.jpg
Yasha image:
https://vignette.wikia.nocookie.net/criticalrole/images/9/92/Yasha.jpg/revision/latest/scale-to-width-down/310?cb=20180116194508
Fjord image:
https://vignette.wikia.nocookie.net/criticalrole/images/2/24/Fjord.jpg/revision/latest?cb=20180116194444
Caleb image:
https://vignette.wikia.nocookie.net/criticalrole/images/9/92/Caleb_Widogast.jpg/revision/latest?cb=20180116194349
Caduceus image:
https://vignette.wikia.nocookie.net/criticalrole/images/7/78/Caduceus_portrait.jpg/revision/latest?cb=20180727064924&format=original
Mollymauk image:
https://vignette.wikia.nocookie.net/criticalrole/images/c/ce/Mollymauk.jpg/revision/latest/scale-to-width-down/310?cb=20180116194455
Beauregard image:
https://vignette.wikia.nocookie.net/criticalrole/images/3/3e/Beauregard.jpg/revision/latest/scale-to-width-down/310?cb=20180116194433
Nott image:
https://vignette.wikia.nocookie.net/criticalrole/images/d/dc/Nott.jpg/revision/latest?cb=20180116194408
M93 image:
https://i0.wp.com/www.nerdsandbeyond.com/wp-content/uploads/2019/06/Critical-Role-Pride-Article-4.jpg
M94 image:
https://vignette.wikia.nocookie.net/criticalrole/images/3/33/Campaign_2_official_art.png/revision/latest?cb=20180308124300

The parallax image (m-nein.jpg) can be found at:
http://hdqwalls.com/wallpapers/warriors-mighty-nein-minimalist-art-85.jpg
However, the individual layers (layer 0-5) were edited and created by myself, using a combination of Gimp (https://www.gimp.org/) and Paint 3D



