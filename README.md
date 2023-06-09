# Star Trek Museum - Project 1

The Star Trek Museum is an imaged museum detailing the exhibitions available for fans of the franchise.

 ((( Add an image of the finished site here on https://ui.dev/amiresponsive )))

((( Add a link to the live site here upon completion )))

(( If you want to add optional [shields.io](https://shields.io) badges to your README, I like to add them to this section. ))

---

## CONTENTS

* [User Experience](#user-experience-ux)
  * [User Stories](#user-stories)
    * [New Users](#new-users)
    * [Experienced Users](#experienced-users)

* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
    * [Homepage](#homepage)
    * [Page: Star Trek Crews](#page-star-trek-crews) 
    * [Exhibition: Starships](#exhibition-starships)
  * [Wireframes](#wireframes)
    * [Homepage](#homepage) 
    * [Crews](#crews)
    * [Starships](#starships)
    * [Contact](#contact)
    * [404](#404)

* [Features](#features)
  * [General Features on Each Page](#general-features-on-each-page)
  * [Future Implementations](#future-implementations)
  * [Accessibility](#accessibility)

* [Technologies Used](#technologies-used)
  * [Languages](#languages)
  * [Programs](#programs)

* [Deployment & Local Development](#deployment--local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)

* [Testing](#testing)

* [Credits](#credits)
  * [Code Used](#code-used)
  * [Content](#content)
  * [Media](#media)
  * [Acknowledgments](#acknowledgments)

---

## User Experience (UX)

### User Stories

#### New Users:

The landing page will more geared towards new visitors and / or those new to Star Trek and wanting to know more. There will be clean and inviting information on what the visitor can expect to experience by visiting the museum by following the CTAS / links provided, as well as an image from each of the exhibitions to cultivate curiosity to learn more.

#### Experienced Users:

By experienced users I mean those that have visited the museum before and / or are fans of the Trek franchise and need less guidance on the page.

The other areas of the site will start with a short blurb about what the visitor will find on this page, followed by a couple of images from the museum alongside a short text. The idea is to pique the visitor's interest so they want to visit the museum. 

* Both pages will have short pieces of text, so as to help the visitor digest the information without being overwhelmed.

* Too many images can slow the loading of the webpage, so I will be limiting to one per paragraph/section.

* Each page will have a CTA that leads to the "how to get here" page to help steer traffic towards visiting the museum.

## Design

### Colour Scheme

The colour scheme is pre-determined with a variety of colours, I shall try to pick a few main colours from this large list that will be both UX/accessibility friendly but making the page look as Trek as possible.

This large colour palette is the LCARS (or Library Computer Access/Retrieval System) is the operating system used on most Trek series so any visitor familiar with the franchise will instantly recognise it. The challenge will be to make it as friendly for non Trek visitors/take into account any accessibility needs.

![Star Trek LCARS colour palette with 36 colours](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/7e55be12-cb5d-401b-af81-684157848bd2)

### Typography

Doing some research I discovered a Tweet that Mike Okuda, the graphic designer who created the LCARS theme, said that the Swiss 911 font was chosen although he preferred Helvetica Ultra Compressed.

![Tweet from Mike Okuda confirming the use of Swiss 911 font for LCARS](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/cb0853e5-fc06-4231-8475-72f2edb41fdf)

I had a look at these two fonts and agree that the Helvetica looks better as it is not as thick as Swiss 911, but the letters are very close together which is how they are on the LCARS system but for the sake of accessibility and UX I think they should have more spacing between them.

Seeing as this is not a regular font most people will have on their computers, I researched what Google Font could be a suitable alternative and have decided to use Antonio. This will ensure the page has a proper Trek feel to it without people needing special font packages installed. 

Taking a look at the example LCARS screen below, I decided 700 weight could be good for main titles, while 400 works nicely in sizes 48px for headings, and 21px and 16px for paragraphs/other text.

![Example of an LCARS interface from the Engineering department](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/a09ada33-4557-49cb-8dd7-ee63be9d79c1)

![Antonio font 700 weight, size 48 pixels](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/d9d344b4-3ca1-4135-91ad-b16f012e73f2)
![Antonio font 400 weight, size 48 pixels](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/fd5c89d1-e2d4-4d7c-901c-08a4d6ffc062)
![Antonio font 400 weight, size 21 pixels](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/10b38372-9863-4938-9d09-e90d9170ab71)
![Antonio font 400 weight, size 16 pixels](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/4c4369ac-8636-4c15-9d85-1eedcf87f84f)

### Imagery

During my research I came across a favicon of a Star Trek badge that I plan on using on each page: <img src="https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/65ab9634-8241-4687-b2b9-5a961057c6be" width="50px" height="50px" alt="Pixelated favicon of a gold and white Star Trek badge">

#### Homepage

![Star Trek Pride selection of starships with various pride flags](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/58808344-6591-4ad4-ac8b-6b0f8a1f4f09)

#### Page: Star Trek Crews

This page will have 3 of the many different Trek crews due to time constraints, so I went researching to find 3 images as similar to oneanother as possible. Luckily through [IMDB](https://www.imdb.com/ "IMDB main page") each of the 3 Trek pages have identical crew artwork which will help improve the UX/UI of the page. On this page, there is the possibility to link the other pages onto here. (in the blurb for one crew there could be links to the starship exhibition)

![Crew of Star Trek: Voyager](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/409700fe-f0f5-4b30-b586-c03bed0e67cf)
![Crew of Star Trek: Deep Space Nine](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/5ca328ed-7bd0-4127-8187-b7fdd2f44571)
![Crew of Star Trek: The Next Generation](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/cb21d4d4-a48c-4b91-95c5-96c3b93fd4f7)

#### Exhibition: Starships

Similar to the crews page there will be details on the ship exhibition at the museum:

![Starship Voyager](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/10d119f9-8701-4bb0-92e0-74f25b9ce214)
![Space station Deep Space Nine](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/0405c7d2-a51e-4d1a-bdc6-ff5c95315814)
![Starship Enterprise](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/ef29e226-c432-4d76-97c2-6f910d7c47c7)

After speaking with my mentor I discovered that webp formats would improve the loading time and overall performance of my page, I went back and converted my images from png/jpg.

### Wireframes

My wireframes accidentally went rather hi-fi because I wanted to see how the background images and the strong LCARS colour scheme was going to work, but I finished the estimated design for desktop, tablet and mobile for the homepage, crew exhibition, starship exhibition, contact page and  404 error page.

#### Homepage

![Homepage wireframe design](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/5811ad4a-bfd6-44db-91be-8d49feb09a0a)

#### Crews

![Crew page wireframe design](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/b213d5b8-7778-444e-bacc-3d87006f21da)

#### Starships

![Starships wireframe design](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/04201ee9-356b-4702-84f0-a781976a3058)

#### Contact

![Contact page wireframe design](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/da2f7882-beec-4049-afba-d6a5edcf6c03)

#### 404

![404 page wireframe design](https://github.com/emmy-codes/Star-Trek-Museum/assets/70635859/d7632cb9-2617-4df9-91f5-f78e99276f74)

## Features

My site comprises of 4 pages:

The homepage, welcoming the user to the main page for the Star Trek Museum, introducing them to the project and informing them of what they can expect when visiting the museum. An image helps to break up the text portion to make it easier for the user to view the content without getting overwhelmed.

Beneath the introductory text are 3 buttons leading to the different sections of the site as a sort of CTA.

The Crews of Star Trek page showcases the 3 Treks that will be available for viewing along with an image of each crew.

The Starships page features the large scale replica models available for viewing at the museum.

The get in touch page has the phone, address and email for contact, along with a form for those who prefer, and a map (to a fake/incorrect address).

The 404 page (not counted in the 4 page site) has an image/gif of Captain Picard facepalming with a button link to get back to the homepage.

### General features on each page

Each page has the same header and nav bar, and the same footer with the (fake) socials available. The desktop version has the navigation bar in the form of links on the top right corner, whereas the mobile versions have a hamburger menu with a dropdown containing the same links.

The tabs have a favicon of the Star Trek comms badge mentioned in the ### Imagery section which is designed to fit well on Chrome, android and apple mobiles.

(( I then like to add a screenshot of each page of the site here, i use [amiresponsive](https://ui.dev/amiresponsive) which allows me to grab an image of the site as it would be displayed on mobile, tablet and desktop, this helps to show the responsiveness of the site.))

### Future Implementations

In the future I would like to have the background as a twinkling star scene, but without JavaScript that would be an excessively tedious manual positioning of dozens of stars.

I would also like to have the site look more like LCARS panels in order to appeal more to Trekkies, but shaping those panels would require more time and practice as of now.

### Accessibility

Some accessibility plans I have once I'm coding:

* Aria labels on any media links
* Semantic HTML for ease of screen readers (thus avoiding div soup)
* Descriptive alt text on any imagery
* Adequate spacing on typography to ensure readability
* Being mindful of colour contrast

Have you used icons and added aria-labels to enable screen readers to understand these?
Have you ensured your site meets the minimum contrast requirements?
Have you chosen fonts that are dyslexia/accessible friendly?

Code Institute have an amazing channel for all things accessibility (a11y-accessibility) I would highly recommend joining this channel as it contains a wealth of information about accessibility and what we can do as developers to be more inclusive.

## Technologies Used

#### Languages

HTML, CSS

#### Programs

[Github](https://github.com/) for uploading my code and having a place to create my live site via Github Pages.

[Balsamiq](https://balsamiq.com/) for my wireframe designs.

[Google Fonts](https://fonts.google.com/) for finding a replacement font that everyone would have access to.

[Convertico.co](https://convertio.co/) for converting images to webp.

[PicResize](https://picresize.com/) for resizing images.

[Squoosh](https://squoosh.app/) for resizing images for my ReadMe.

## Deployment & Local Development

👩🏻‍💻 View an example of a completed Deployment & Local Development section [here](https://github.com/kera-cudmore/TheQuizArms#Deployment)

### Deployment

Include instructions here on how to deploy your project. For your first project you will most likely be using GitHub Pages.

### Local Development

The local development section gives instructions on how someone else could make a copy of your project to play with on their local machine. This section will get more complex in the later projects, and can be a great reference to yourself if you forget how to do this.

#### How to Fork

Place instructions on how to fork your project here.

#### How to Clone

Place instructions on how to clone your project here.

## Testing

Start as you mean to go on - and get used to writing a TESTING.md file from the very first project!

Testing requirements aren't massive for your first project, however if you start using a TESTING.md file from your first project you will thank yourself later when completing your later projects, which will contain much more information.
  
Use this part of the README to link to your TESTING.md file - you can view the example TESTING.md file [here](milestone1-testing.md)

## Credits

### Code Used

Thankyou to ![MDN form guide](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form) for guiding me through making a form for my site

I have taken inspiration and hexcode from [The LCARS](https://www.thelcars.com/). Whilst this site has a library for use, I only wanted to take what I could from looking at the page as I didn't want to output more than I could create on my own.

### Content

I am planning to use ![OpenAI](https://chat.openai.com/) to create most of the text for me so I can focus my time on practicing with the code.

###  Media

The crew images are sourced from [IMDB](https://www.imdb.com/)
The starships are from ![PNGfind](https://www.pngfind.com/freepng/star-trek/)


###  Acknowledgments

Thank you to my partner for his insight on media queries and guidance on the best practices for writing instructions on forking and cloning, as well as assistance for helping me adjust my site responsiveness to be less of a headache in the future (specifically: he helped me change my panel sizings from vh to % as well as using the newly implemented dvh to the body, which will apparently future proof my code as well as improve ease of responsive design).

Thank you to my classmates on Slack for assisting when I had questions regarding HTML
