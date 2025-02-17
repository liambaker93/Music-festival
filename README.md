# Through The Trees - Music Festival 

Welcome to the README for the Through The Trees music festival website.

Visit the deployed site: [Through The Trees](https://liambaker93.github.io/Music-festival/index.html)

I wanted to create a site that could showcase similar kinds of content in different ways showcase what I've learnt so far regarding using HTML and CSS together to code a responsive, visually appealing website.

## Table of Contents

1. [Rationale](#rationale)
2. [User Stories](#user-stories)
3. [Wireframes](#wireframes)
    - [Desktop Wireframes](#desktop-wireframes)
    - [Phone Wireframes](#phone-wireframes)
4. [Styling](#styling)
    - [Fonts](#fonts)
    - [Colors](#colours)
5. [Testing](#testing)
    - [Code Validation](#code-validation)
    - [Bugs Found](#bugs-found)

## Rationale

This project is designed to showcase the different aspects to a music festival that a user may come to expect, with the goal of allowing the user to quickly and easily submit a request to get a ticket. 

I wanted to make sure that the user was never far away from being able to see the key information that they may feel they need, with their eyeline being drawn towards the main features they need to see. An example of this would be the artists page needing to clearly showcase the headlining acts for both days, and the support acts being supplementary pieces below the main events.

Being able to point the user towards relevant social links was also important to me, hence the inclusion of spotify as a social link as I felt this gave the page some brand cohesion.

One limitation of the project currently was that I imagined there being an audio element to the page, direct spotify links to playlists / specific songs by the artists. Having these would've made the site feel more feature complete as the user would be able to get a better sample of what to expect from the festival. As well as that, not having menus created for the food vendors meant that the links to the menus had to be creative. I opted to have a popup open that alerts the user to the promise of an update in the future regarding the food but, to maintain interest and retention, they can follow links to the social account of the festival and be updated when those elements go live. 

I commented on that modal to allow any future developers of the code to know where the modal is and how it's currently being used, with the idea that specific ones would be created for each food vendor, all four of them currently using the same modal for simplicity.

As it currently stands it's quite a simple site, however it has all the pieces in it to get a small, independent festival ready to showcase exactly what they're all about to any potential music fans in the future. 

## User Stories

- "I don't go to many festivals but particularly want to see one artist and want the flexibility
to go just to see them."

- "I'm a regular festival goer and want to see the variety of artists I can watch, different
timings, and see what food options there are for me."

- "I'm a food vendor and want to be able to sign up to bring  my business to the festival, so will
need a way to contact the organisers."

## Wireframes

### Desktop Wireframes

Going into the wireframing process, I had quite a good idea already of how I wanted the pages to look. 

I knew that I wanted the main call to action button to be the book now button which would remain consistent throughout all the pages.

Specifically with the homepage I wanted to have a carousel of images that would show off the vibe of the festival, with a text box next to it giving a brief description for the user to understand a little about the festival itself. If the description sounded appealing then the aim is for the user to be guided to the Artists page to see who's playing...

![Homepage Desktop Wireframe](./readme/images/wireframes/home-page-desktop.webp)

With the Artists page, I wanted to use cards to showcase the two main headlining acts, one for Saturday and one for Sunday, and then have a row of cards beneath to show other artists performing. This would give the user the chance to see if anyone they know is performing which would then push them to want to book their tickets to come to the festival.

![Artist page Desktop Wireframe](./readme/images/wireframes/artists-page-desktop.webp)

The Food page was a page I wanted to add to help round out the idea that this was a festival with more to it than just music, and had some actual thought put into it. In terms of layout design, I wanted it to resemble the artists page closely, however I didn't want to give the impression of 'headliner' food options, so opted to have all the cards be the same size and layout.

![Food page Desktop Wireframe](./readme/images/wireframes/food-page-desktop.webp)

The final page is the main booking page. On this page I wanted to give the user the option of which dates they wanted to attend as well as the number of tickets they want to order. To make the page more engaging, I planned on putting a carousel of images behind the booking form to liven the page up.

![Booking page Desktop Wireframe](./readme/images/wireframes/booking-page-desktop.webp)

- - -

### Phone Wireframes

The phone designs were designed to just be smaller versions of the main pages, taking away some content where it wouldn't make sense to have on a smaller screen, for example the carousel of images behind the booking form on the booking page. 

![Homepage Phone Wireframe](./readme/images/wireframes/bookingpage-phone.PNG) ![Artist page Phone Wireframe](./readme/images/wireframes/artistpage-phone.PNG) ![Food page Phone Wireframe](./readme/images/wireframes/foodpage-phone.PNG) ![Booking page phone wireframe](./readme/images/wireframes/bookingpage-phone.PNG)

- - -

## Styling

### Fonts

The first font I found on google fonts was 'Almendra'.

Almendra is the font I've used for all headings in elements.

![Almendra Font](./readme/images/fonts%20and%20colours/almendra-font.webp)

The next font I found which became the 'secondary-font' variable was 'Raleway'.

![Raleway Font](./readme/images/fonts%20and%20colours/raleway.webp)



### Colours

I used coolors to find the colours I wanted. I knew I wanted to go for a forestry, earthy palette due to it being an outdoor music festival, so I went through the site until I found colours that I felt complimented each other.

![Coolors palette](./readme/images/fonts%20and%20colours/festival-color-palette.png)

I then found that when creating the hero image on the homepage, that using the shamrock green as the main font colour looked too dark and the contrast was terrible.

Below is coolor's contrast checker result for the primary font colour against the main background colour of the hero-image: 

![Hero image original text colour contrast](./readme/images/fonts%20and%20colours/hero-heading-first-colour.PNG)

Below is the updated colour contrast after using devtools to find the right amount of text-shadow to highlight the text and brighten the colour:

![Hero image updated text colour contrast](./readme/images/fonts%20and%20colours/hero-heading-second-colour.PNG)

And below is how the final header looks: 

![Hero image with text overlay](./readme/images/fonts%20and%20colours/hero-heading.PNG)

- - -

## Testing

Go to [TESTING.md](TESTING.md) for all the testing I completed.

### Code Validation

One of the common info boxes I had show up during the validation process was 'trailing slashes on void elements'. Self closing elements had slashes ahead of the closing tags which the validator flagged as being unneeded so I went through the code on all the pages to eliminate these. 

![Original validation attempt on the homepage](./readme/images/testing/html-validation.PNG)

One warning that was suggested by the validator was having a section which had no heading underneath it. The following is the validator comment, and below is the content displayed on the site:

![Homepage booking modal validation comments](./readme/images/testing/index-booking-validation.PNG)

![Homepage booking modal content](./readme/images/testing/index-booking-validation-content.PNG)

I then added a H5 element above the table in the modal, to highlight what the box was for which would help with the user experience when it's clicked on. The following is the code I added, and below is the final result of the content:

![Homepage booking modal code fix](./readme/images/testing/index-booking-validation-fix.PNG)

![Homepage booking modal content after fix](./readme/images/testing/index-booking-validation-fix-content.PNG)

The homepage validation also included a comment relating to the same modal which referred to the 'Full Weekend' ticket option being a placeholder, and the selection by default. It suggested it as a warning rather than an error, which I assume is because it may be bad practice to automatically have the user directed to a selection that could end up being the wrong one if they're not paying attention. 

I wanted the content of the information box to lead the user into specifically clicking that link to book that ticket type, however I opted to change it to keep in line with best practices on the web.

![Homepage booking modal ticket type selection validation result](./readme/images/testing/index-validation-placeholder.PNG)

![Homepage booking modal ticket type code fix](./readme/images/testing/index-booking-validation-fix.PNG)

![Homepage booking modal ticket type content after fix](./readme/images/testing/index-booking-validation-fix-content.PNG)

The final validation results can be found [here](./TESTING.md/#w3c-validator)

### Bugs found

| No | Bug | Solution
| -- | ---- | ------ |
| 1 | Logo in navbar wasn't appearing | I had changed the filepath for the logo as I needed to take a capital out of the name to keep in named traditionally. Fixing the file path then brought back the logo. |
| 2 | Artist page had a horizontal scroll bar. | This was due to the main content of the page not being wrapped in it's own div element with a col class to keep it within bootstrap's defined width. |
| 3 | Footer wasn't reaching full width of the page | The footer was kept in a container class which was unneeded, and once removed pushed the footer as wide as the screen size. |
| 4 | On the booking page, the toggle button for the nav bar wasn't working when pressed. | I simply had not added the javascript for bootstrap to the bottom of the body. |
| 5 | After placing my logo into my navbar, when looking on a smaller screen size, it jumped to the right side of the nav and the toggle button jumped to the left | I had to move the placing in the html of the logo to be before the toggle not after, as this was causing the elements to swap places |

- - -

## Deployment & Local Development

### Deployment

The site has been deployed using GitHub Pages - [Through The Trees](https://liambaker93.github.io/through-the-trees/index.html)

To Deploy the site using GitHub Pages:

1. Login or signup to [GitHub](https://github.com/)
2. Follow the link to the repository for this project: [liambaker93/through-the-trees](https://github.com/liambaker93/through-the-trees)
3. Click the Settings button
4. Select pages from the navigation menu on the left side
5. Using the source dropdown, select main branch and press save.
6. The site is now being deployed, note that it may take a few minutes before the site goes live.

### Local Development

#### How to Fork

To fork the repository:

1. Login or signup to [GitHub](https://github.com/)
2. Follow the link to the repository for this project: [liambaker93/through-the-trees](https://github.com/liambaker93/through-the-trees)
3. Click the Fork button above the about section.

To clone the repository:



## References (Fonts, bootstrap etc)

### Education Tools

[Digital Ocean helped with troubleshooting issues relating to image sizing within cards](https://www.digitalocean.com/community/tutorials/css-cropping-images-object-fit)

### Design Tools

[Used Google Fonts for fonts](https://fonts.google.com/)

[Used Coolors to generate colour schemes](https://coolors.co/)

[Used Balsamiq for wireframing](https://balsamiq.com/)

### Images

[Used Pexels for stock images](https://pexels.com)

<!--Photos for homepage carousel-->

#### Homepage Images

[Photo by Brett Sayles](https://www.pexels.com/photo/woman-playing-guitar-while-singing-beside-man-playing-bass-guitar-near-microphone-1309240/)

[Photo by Brett Sayles](https://www.pexels.com/photo/woman-playing-guitar-while-singing-beside-man-playing-bass-guitar-near-microphone-1309240/)

[Photo by Jonathan Borba](https://www.pexels.com/photo/view-of-a-concert-with-fireworks-3563173/)

[Photo by Wendy Wei](https://www.pexels.com/photo/photo-of-crowd-during-concert-1190295/)

[Photo by Sebastian Ervi](https://www.pexels.com/photo/silhouette-of-people-in-front-of-stage-1763067/)

[Photo by Sebastian Ervi](https://www.pexels.com/photo/people-in-concert-1763075/)

#### Artists Page Images

<!--Photos for artists cards-->

[Photo by Clam Lo](https://www.pexels.com/photo/photo-of-man-playing-guitar-3469692/)

[Photo by Aleksandr Neplokhov](https://www.pexels.com/photo/band-playing-at-the-street-2601189/)

[Photo by Wendy Wei](https://www.pexels.com/photo/woman-playing-electric-guitar-1864641/)

[Photo by Cottonbro Studio](https://www.pexels.com/photo/man-playing-saxophone-5650950/)

[Photo by Pixabay](https://www.pexels.com/photo/group-of-four-men-rock-band-210887/)

[Photo by Luis Quintero](https://www.pexels.com/photo/woman-singing-on-stage-2091375/)

<!--Photos for Food cards-->

#### Food Page Images

[Photos for the food cards were generated using Google Gemini](gemini.google.com)

