# MS1-project

  <a href="#purpose">Purpose</a> •
  <a href="#wireframe">Wireframe</a> •
  <a href="#license">License</a> •
  <a href="#ux">UX</a> •
  <a href="#features">Features</a> •
  <a href="#technologies used">Technologies Used</a> •
  <a href="#testing">Testing</a> •
  <a href="#deployment">Deployment</a> •
  <a href="#credits">Credits</a>

>Insert a picture of all devices with the screens showing different pages, then delete all this gaff in the box.
>These files should themselves either be included as a pdf file in the project itself (in an 
>separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

## Purpose of the Project
This is a basic 3 page website for a jiu jitsu academy, displaying it's outline, classes and contact details. It features; 
a jumbotron; scrolling, enlarging and fading pictures; data entry overlays; and icons with links to outside sources.

This website was created as my first milestone project (after study of HTML5 and CSS3) while completing a diploma in 
fullstack development. For the purpose of showcasing HTML and CSS abilities a website is the best media.  Over time, more 
pages and parts can be added to present new skills learned.

## Wireframe
The mockup was created in <a href="(https://www.figma.com/file/RZ6ACWWZjSS0PmnffgtA9j/Elemental-Academy?node-id=1%3A12)
">Figma</a> with prototyping.

It is hosted on <a href="(https://github.com/CheriGore)">GitHub Pages</a> and the repository is on <a href="
(https://github.com/CheriGore/MS1-project)">GitHub</a>.

<br>

## License
The project is shared for use with 21the GNU General Public License v3
-This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License 
as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

<br>

## UX
### USERS
This website is primarily created for driving new business to the jiu jitsu academy. Users are likely to be people
refered to the site or local people interested in joining the academy. Other users may be current students checking the 
schedule, people interested in knowing more about jiu jitsu or anyone wishing to check the validity of training or contact 
the academy.

The main purposes for users will be:
* To find basic information (ethos, media links, services, facilities), schedule and required contacts
* To sign up for a free class
* To sign up to the mailing list
* For interested students of coding who may peruse the pages and study the source code for comparison or further learning
* For other jiu jitsu academies to check out the academy
* For peers with similar skills that may be directed to these pages to help test and advise on their suitability and function
* For testers with varying skills that can advise of UX and personal preferences

### USER STORIES
As a prospective student, I want to find out the price so I can check it's within my budget.
As a prospective student, I want to sign up for a free class so I can have a go.
As a prospective student, I want to find out the style/ethos so that can decide if its the right place for me.
As a prospective student, I want to check the class schedule so that I can see if I attend.

As a parent, I want to research local martial arts clubs so that I can find the best fit for my child.
As a parent, I want to find out the style/ethos so that can decide if its the right place for my family.
As a parent, I want to contact the academy so that I can discuss my child's needs.

As a student, I want to view the schedule so that I remember what time my class starts.
As a student, I want to lookup my teachers details so that can contact them.
As a student, I want to sign up for the mailing list so that I can read the latest news.

As a x, I want to x so that x.
As a x, I want to x so that x.

### DESIGN
All pages will include a static navigation panel at the top and a static panel footer with media links and webmaster details:
* The first page (index aka home) will welcome the public and provide an overview of the academy's ethos and services
* The second page (juijitsu) will give information about the academy's services and schedule
* The third page (contact) will list the location, academy details and all the parties involved with their contact details

The overall look shall be clean, clear and professional. Highlighting colours will mainly be green and blue with a dash 
of purple. The colour scheme consists of:
* Backgrounds white #FFFFFF
* Font colors black or white #000000 #FFFFFF
* Font color hover purple #84639A
* Button color green #8FD175
* Button color blue #3296DF
* Opaque backgrounds grey #F2F2F2
* Font type Headers - PT Sans, Bold
* Font type Paragraphs - PT Sans, Normal

### Benefits
* A clean, clear, easy-to-use interface
* Clear navigation to access the other pages
* Signup to a free class or mailing list
* Display of photos and expectations
* Green and blue colouring to make it appear natural and have a healthy appeal
* Links to social media

<br>

## Features
The left and right margins are 64px for all pages.  Colors, font and sizes are as per the design section of this document.

### Header for all
There is the EA icon on the left and written navigation links to all three of the pages in from the right.
Under the currently view page is a 5px line to determine the viewed page. This moves as each of the three pages are 
viewed. For mobiles the icon stays, but the written navigation is replaced with a menu button which opens the 'menu' overlay.

### Menu overlay
Written navigation aligned vertically, split by a 1x grey line, listing the three pages and also 
FREE CLASS, which opens the 'signup' overlay.

### Signup overlay
An X top right to close the overlay (cancel). Under this a 240x422px green box with white text inside "Enjoy a free class!".  
Under this "Please select the class you wish to attend:" with a drop box of class selection (Jiu jitsu, warrior women, 
personal training, nutricion, private lessons, other). Under this half sections with folowing free field entries: Name 
(52 character limit), age (1-105 limit), email (must contain characters@somthing.somthing) and phone number (number string 
at least 11 characters).  Also half span, links to documents that should open overlays, but for this project it should be 
imagined as there are other examples.  Documents listed vertically - LIABILITY STATEMENT, SOCIAL MEDIA STATEMENT and RULES 
AND REGULATIONS.  To the right, a tick box and then agreement statement.  Under this a green box with white writing SUBMIT 
button.

### Footer for all
A blue background taking up the whole span left to right. Four sections, left aligned. Headers PT Sans Medium black, 
writing below white and hover is purple.  Sections MY ACCOUNT has Sign in and Register, HELP has FAQ, ABOUT has Our story,
Location and Media, LEGAL STUFF has Liaility Statement, Social Media Statement and Rules and Regulations.  Under these, 
medium header FOLLOW, and under four black icons with the url link to Facebook, Instagram, Twitter and LinkedIn.

### Home page
Header and footer as above.  Welcome section in two halves.  Left half is hero image of black in samari and the words 
Health, Fitness & Lifestyle written to it's right staggered vertically one word per line.  Under this a space for green 
wording to change exery 2 seconds - Holistic, support, 753 code, nutricion, defence.  The right half contains a jumbotron 
with hero image that enlarges slightly on arrival.  The button is green background, white outline and writing "Sign up for 
a free class". 

Welcome text section has a H2 and three Paragraphs of body text outlining the basic details of the academy.

Testimonials section has four cards with each a picture and a name and quote below.

Join section has a two halves, a header to the left asking "Join the mailing list for more info!" and in the right half, a 
text box above a blue background button with white writing "JOIN MAILING LIST" which opens the 'Mailing list overlay'.

### Mailing list overlay
An X top right to close the overlay (cancel). Under this a 240x422px blue box with white text inside "Sign up to our mailing 
list!".  Under this "Get the latest information on our services and news in the jiu jitsu world".  Under this two half 
sections with folowing free field entries: Name (52 character limit) and email (must contain characters@somthing.somthing).  
Underneath, a tick box and then agreement statement.  Under this a blue box with white writing SUBMIT button.

### Jiu Jitsu page
Header and footer as above.  
A full span jumbotron with group training picture and the green sign up button from 'home' page.

A two halves section with H2 and writing in left section and staff team picture on the right.

A schedule section with grey Opaque background, a H2, H3 and four cards containing a picture, header and writing detailing 
the class schedules and finishing with a green button with white writing "Free Class".

A full span strip of five photos.

A facilities section with H2, below a H3, below a list and below four photos.

### Contacts page
Header and footer as above.  A two halves section with left half background green and right grey opaque.  Within these, 
three horizontal sections. The first has a form with white H2 "Get in touch!", containing three free form fields below of
name, email (input restraints as prevoius) and a larger free form message box with a black SUBMIT button below.  The 
middle section houses H2 hearders of Address, Call us and Opening hours with the details in body text below each.  The
section to the right has a picture of the map of the academy location.

the meet the team section has four cards with each a picture with a name, description of services, contact details and 
social media icons with links below.


### Features Left to Implement
* A shop
* Online booking and payment for guests and new applicants
* Direct access to a student portal featuring booking, payment, activity log and discounts/offers
* A scoreboard or table for in-house competitions and challenges
* Automated news upload from other jiu jitsu sites
* A link to a jiu jitsu game
* Dark/Light mode

### Suggested Features
Future development could see more useful items such as:
* More social media integration such as video chat, discord group or a Twitch account
* Space allocated to students for their own personal showcases

<br>

## Technologies Used
* <a href="(https://figma.com)">Figma</a> to make a mockup with prototyping
* <a href="(https://github.com)">GitHub</a> to host and share the project
* <a href="(https://gitpod.io)">GitPod</a> to write the code and push to GitHub
* <a href="(https://HTML5.com)">HTML5</a> the main coding language to build web pages 
* <a href="(https://CSS3.com)">CSS3</a> to stylise the pages

<br>

## Testing
>In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the 
>site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure 
>that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their 
>goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, 
link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. 
A particularly useful form for describing your testing process is 
via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you 
haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

<br>

## Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages 
or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, 
if any, including:
* Different values for environment variables (Heroku Config Vars)?
* Different configuration files?
* Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

<br>

## Credits

### Content
* The readme.md file draft was copied from a <a href="(https://github.com/Code-Institute-Solutions/readme-template/blob/master/README.md#your-projects-name)">GitHub README template</a>
* Guidance and inspiration for readme.md creation was obtained on the <a href="(https://github.com/Pattern-Projects/oireachtas-ifd-project/blob/master/README.md)">Oireachtas Viewer</a> website

### Media
The photos used in this site were obtained from:
* Personal library, as we practise jiu jitsu
>* 
>* 

### Acknowledgements
I received inspiration for this project from:
* My Original learning project Love Running
* Strangely, another website for another company called Elemental Academy
* The Valente Brothers website for ideas on content
>**if used** [W3 Schools] glowing text (https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_glowing_text)