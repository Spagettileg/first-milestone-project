# 1st Milestone project 

Welcome!

***
Link to the website (via GitHub Pages) – update address
https://first-milestone-project-spagettileg.c9users.io/index.html

Link to Cloud9 Development
https://ide.c9.io/spagettileg/first-milestone-project

***

### Introduction
A front-end website has been created and has been designed to promote the American rock and pop band "The Monkees". Therein, you will find the latest news of a 2019 world tour that includes details of dates, venues and location of the bands’ live performance concerts. For the ultimate fan experience, there is an opportunity to book the band for weddings, anniversaries, birthdays, etc. 
Fans can also access a discography that offers a full list of their albums, selection of audio tracks and a playable video promoting the latest ‘Good Times’ album that celebrates the bands existence over 5 decades.

***

### Prerequisite
This software has been designed to run on Chrome, Edge, Firefox, Safari, Opera & Internet Explorer.

***

### Design

##### Colour palette used:
Inspiration of the choice of colours originated from the ‘Good Times’(2016) record album cover. 

- #C43232 Red

- #6CB8AC Green

Background colour was selected upon review of The Monkees clothing. There are some instances where yellow was worn.  

- #f7eed4 Yellow

Booking tickets section of ‘HeyHey!’ webpage continues theme of a 1970’s colour scheme with a touch of psychedelia thrown in for good measure.

- #660066 Purple

- #ffe6ff Lilac

Lower footer set to dark grey to clearly show copyright and web-designer information.

- #525252 dark  grey

*** 

#### UXD Considerations
The website design encourages both new and existing fans to access the band's critically acclaimed music, video and narrative.  50 years of performing is celebrated in the website through announcing a 2019 world tour and allowing fans to easily navigate to choose and select a concert that’s right for them. The ticket order process allows for the user to tailor their ticketing requirements, via secure password control.  
Furthermore, fans can book an amazing personal experience to see the band live through completing a short, yet informative booking form.  
Imagery selected throughout the site design is biased towards what the band does best – having fun. 
The site has been created to ensure the user gets a non-complex, intuitive and enjoyable experience. It is hoped the fans feel closer to the band based upon the content therein. 

#### Wireframes
I have used Balsamiq to produce wireframe models. As I’m relatively inexperienced to web-design, I made a conscious decision to create mock up’s of the web-pages. This proved to be a master-stroke moment, as I could then secure a much improved physical visual design and apply my new found coding knowledge to this design.
I’ve included my .bmpr wireframe designs on GitHub.  The mock up design have evolved through the duration of my site build. The design changes were borne out of fully leveraging my coding skills coupled with upholding an effective UXD.  

*** 

### Features
#### index.html
Alert message created to notify user of link to quickly access ticket sales and concert bookings. The alert only appears on the home page.

Navbar (repeated on all pages) has been designed to include a clickable icon image that is  synonymous with the bands brand. The user will always return to the home page with. In addition, the navbar allows the user to navigate to ‘music’, ‘heyhey!’ and ‘events & tickets’ pages. A ‘hamburger’ design has been built to collapse the navbar for Mobile devices.

A full black and white image of the band is on show from the header through to the first container ‘hot news!’. An opaque-overlay helps soften the band image.  I was inspired by the design as a result of completing the bootstrap training and ‘Whiskey Drop’ coding exercise. The thought of scrolling the image creates a sense of something next.   

‘Hot News!’ is central to the home page. Users are notified up front of important information concerning the band. In addition, there is a ‘Good Times’ text link that navigates the user to the ‘music’ page where a video has been added to talk further on ‘Good Times’ and further link to 50 year band celebrations.  Summary news of 2019 world tour is supported by use of glythicons, sourced from bootstrap / font awesome.

Further news of a 2019 world tour appears on home page via a ‘bootstrap’ table design. The design has been further modified to include a clickable button to allow user to check availability of tickets via a navigation link through to ‘events & tickets’ page. All buttons are subject to .hover pseudo class that provides a status colour change to the user when their cursor is placed upon the selected button.

Footer (repeated on all pages) includes social media links and fonts (glythicons) secured from bootstrap / font awesome. The links are wired to the bands’ respective social media sites. Again, the .hover pseudo class has been used to provide a background colour change (yellow to red) and font colour change too.  The lower footing allows for both copyright and web designer information.    

#### music.html
A video download ‘Good Times’ via you tube has been added at the start of this page. HTML iframe syntax used in conjunction with height & width settings. This approach was a preferred choice compared to an mp4 file that I struggled to work with, mainly due to the 16Mb file size.  The next section of the page is dedicated to the bands’ sample music where the user can access upto 4 music tracks with supporting audio control bars. The sample tracks are aligned to the originating album covers.

A discography completes the last section of the page, built in JS Bootstrap carousel. Both a timeline and corresponding band album covers gives the user a sense of scope and understanding of the music produced by the band. A minimal design was created by removing page indicator numbers and manual controls to ensure automated reviewing of the bands’ 15 images and narrative.

#### hey hey!.html
This page is designed to introduce the user to the band members, understand their background and to share some humour with a random selection of quotes.

A full colour image of the band is on show from the header through to the first container ‘background story’. I believe the image shown captures great energy from the band and I wanted this energy to transfer to the user as a means becoming more interested in the page content. The background story provides an insight to how the band came together and notable milestones throughout years of performing.

A carousel is positioned in the last section of this page, offering the user the opportunity to view more images of the band, introduction to band members and share band member quotes too.  The nine image slides are timed to fade (5 seconds) and auto change to the next scheduled slide. 

#### Events & Tickets.html
This page is designed to help the user view ticket availability, book tickets and book the band.

Another full colour image of the band is displayed showing a spirit of celebration and precedes the ‘Book Tickets’ section. To book tickets, the user will have been steered from the home page or directly clicked into this web-page. A modal has been added to each concert booking button to help the user by requesting their email and number of tickets required. Password security and a tick box requesting user permission to share their email address provides an essential user assurance.

The user can scroll to end of page to take up an opportunity to book the band for a private event i.e. wedding, anniversary, birthday, etc. A button has been created in conjunction with a modal to help the user complete a booking enquiry form. The form request name, email, preferred booking date, type of event and any special instructions. A tick box has been added to request user permission to share their email address. Again, providing an essential user assurance. No password required here, as we’re dealing with a user booking enquiry and not a formal booking. The latter would represent an additional build in web-design.

***
### Features left to implement
-	Add conditional formatting to password data entry in modal design
-	Create links from band’s albums in music.html to itunes, serving to increase commercial capability of web-site design 
-	Add television media material in addition to existing video and audio media
-	Add a x4 band member ‘image ribbon’ as part of header that is replicated on all pages and animate via hover.css
-	Build a link for ticket orders and band bookings to an external server
-	Add a web hit counter to understand popularity of web-site
-	Create a fans feedback function to help promote continuous improvement of UXD (User Experience Design) for user enjoyment and UCD (User Centred Design) to create great products 
***
### Technologies Used

#### HTML5 
HTML5 was used to create basic structure
#### CSS3 
Cascading Style Sheets provided support with formatting, positioning, coloring and styling
#### Bootstrap - https://www.bootstrapcdn.com/
Bootstrap 3.3.7 is used to create frameworks of a mobile-first design, it was used for navigation and page grid layout in the website.
#### JQuery - https://jquery.com/
JQuery is added to the site to assist the implementation of JavaScript and Bootstrap.
#### Google Fonts - https://fonts.google.com/
Google fonts are used to create an impact to the web-design and uphold a styling theme.

•	'Bangers, cursive': Used for headings

•	'Crimson Text', serif’: Used for the form, page paragraphs and buttons
#### Font Awesome - https://www.bootstrapcdn.com/fontawesome/
Font Awesome is used to add social links font (images) to the website. These fonts were Facebook, Instagram, Twitter, YouTube and Spotify.
#### Git & GitHub - https://github.com/
Git is used as a command line tool to support version control, through moving files to a staging area prior to adding to a local repository. For safe storage and to allow other users to view my deployed website, all relevant files were then pushed from Git to GitHub. 

***

### Testing
A user testing matrix has been produced in MS Excel, but saved as .png to visualize here on GitHub. It outlines the various tests I made to ensure the site renders consistently across different platforms, and that each functionality behaves as intended.
#### Compatibility
User testing mobile and desktop configurations was conducted on the following web browsers.  
•	Chrome
•	Edge
•	Firefox
•	Safari
•	Opera
•	Internet Explorer
#### Test Observations
-	Responsiveness issues on mobile devices occurred in heyhey.html file for carousel images with varying height. Matter was fixed with support from my mentor
	
    - Added x3 breakpoints (320px, 768px & 1200px)
    - Meta tag in header required changing. Initial meta tag was leveraged from CSS training module:
     
-   Image height variance was remedied through use of height: auto and width reduced to 300px from 320px to allow for some padding
-   Further testing confirmed poor responsiveness on devices greater than 1200px. One further @media query (>1201px) was added to CSS file to counter this issue   
-   Carousel images on music.html were re-sized (refer to ‘Credits – Content’ below) to 300px x 300px to support a good responsiveness test
-   Edge : Emulator tool unreliable, so manual check on responsiveness showed no issues
-   Safari : Background images on index.html, heyhey.html and eventsandtickets.html pages scrolled rather than stay fixed to allow latter containers to scroll over the same images 
-   Opera : Hover functions on buttons does not work (all pages) and click required to find audio bar on video clip (music.html)
-   IE : Scrolling of web pages not providing smooth viewing for user. Emulation options were limited and offered poor viewing experience

***

### Deployment
A link to GitHub covering my deployed version of the website is located at the top of this document.

***

### Credits
#### Content
The Monkees 2019 touring date for US, New Zealand and Australia - Ticketmaster

All images used optimised file size via http://www.jpeg-optimizer.com/

The Monkees’ background story – Wikipedia

Carousel code copied and reworked to support own heyhey.html & CSS code - https://www.w3schools.com

Social media hex colour codes - www.codeofcolors.com

#### Media
##### Project Assets
All audio sounds – Code Institute
-	Clarksville.mp3
-	DaydreamBeliever.mp3
-	ImABeliever.mp3
-	SteppingStone.mp3

##### Images – Code Institute
-	dj.jpg
-	mn.jpg
-	md.jpg
-	pt.jpg
-	monkees.jpg

#### Assets

Singles covers:
-	Last Train to Clarksville – discogs.com
-	Daydream Believer – discogs.com	
-	I’m a Believer – discogs.com
-	Stepping Stone – 45cat.com 

themonkeeslogo.jpg – pinterest.com

Album covers - https://www.allmusic.com
-	20th Anniversary Tour 1986.jpg
-	Birds Bees & Monkees 1968.jpg
-	Changes 1970.jpg
-	Concert in Japan 1996.jpg
-	Good Times 2016.jpg
-	Head 1968.jpg
-	Headquarters 1967.jpg
-	Instant Replay 1969.jpg
-	Justus 1996.jpg
-	Live Summer Tour 2002.jpg
-	More of The Monkees 1967.jpg
-	PAC&J Ltd 1967.jpg
-	Pool it 1987.jpg
-	The Monkees 1966.jpg
-	The Monkees Present 1969.jpg 

‘Good Times’ video – You Tube - https://youtu.be/T5Q_FbVf0Cs

Heyhey.jpg – fanpop.com

Celebration.jpg – wallpapercave.com

Eventsandtickets.jpg – abcnews.go.com

***

### Acknowledgements 
Theo Despoudis (Mentor) - For his guidance with the process of delivering my project and reminders for keeping the code simple, yet effective. 

Slack Community and the following experts to keep me honest.
- @Eventyred_Mentor – Simen Daehlin
- @Shane Muirhead – Shane Muirhead
- @Abonello_Lead – Anthony Bonello
- @JoWings_Lead – Joke Heyndels
- @Spence_Mentor – Spencer Barribal

Michael Park (Code Institute Tutor) – For his support and guidance on responsive web design.

Special thanks to Matt Rudge, Timmy O'Mahony & Brian O'Grady (all Code Institute) for their time, training delivery and generating good confidence to coding.

