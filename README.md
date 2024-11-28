# Lund Farm

This website is designed to showcase a wedding venue, Lund Farm and its services whilst providing users with a way of contacting the venue and finding relevant social media pages. 

## Visitor Goals

### Target Audience

- Engaged Couples looking for a wedding venue.

- Wedding planners looking for information about the venue.

- Wedding guests looking to familiarise themselves with the venue before attending a wedding there. 

## User Stories 

[Link to the relevant user stories GitHub project board](https://github.com/users/ElFalch/projects/2/views/1 "Lund farm user stories GitHub project board")


## Visual Design

### Wireframes

#### Updates to design since creating wireframes: 

- Included a button in the home page introduction section which links to the contact page, to allow for users to get in touch more easily. 

- Changed the photo grid in the gallery page to a carousel to allow for less scrolling, particularly in mobile and tablet viewports. 

- No image was incldued in the contact page to reduce drowding for a clearer presentation of the contact form. 

#### Mobile Wireframe

![alt text](https://github.com/ElFalch/lund-farm/blob/main/assets/images/wireframes/lund_farm_mobile_wireframe.png "Mobile wireframe")

#### Tablet Wireframe


![alt text](https://github.com/ElFalch/lund-farm/blob/main/assets/images/wireframes/lund_farm_tablet_wireframe.png "Tablet wireframe")

#### PC Wireframe

![alt text](https://github.com/ElFalch/lund-farm/blob/main/assets/images/wireframes/lund_farm_pc_wireframe.png "PC wireframe")


### Colours

The colours used reflect those in the main image on the home page and convey the cosy, inviting atmsophere of Lund Farm whilst providing enough contrast to be interesting and accessible. 

### Fonts 

The fonts used were chosen as they are rustic and relaxed, reflecting the atmosphere of the venue. Delius Swash Caps was used for the headings because the slightly curled letters add a formal touch and Lexend Exa was used for the body because of its clear, minimalistic appearance. 

### Icons 

Icons were taken from the ![alt text](https://fontawesome.com/v4/icons/ "FontAwsome") icon library. 

- A heart icon is used in the navigation bar brand, after the venue name. 

- Icons for Facebook, X (formerly Twitter), Instagram and YouTube are used in the footer as buttons linking to each of these sites. 

- An icon with two speech bubbles is used to hilight the button linking to the contact page on the home page. 

- An arrow icon is used in the Gallery page to direct people to the image carousel after reading instructions about how it works. 

### Images

Lots of images have been used across the site, so their size has been reduced as much as possible whilst maintining the high quality needed to attract users. 

- On the home page, a main image that reflects the colour scheme has been used in the header aswell as images for each of the services cards. 

- The gallery page consists of a carousel of attractive images of the venue. 

- On the thanks page, which users a taken to when they submit the contact form, an image has been used to fill empty space and provide some brighter colours. 


## Page Elements 

### All Pages

- Navbar: The Navbar provides links to the three main pages of the site and has the Lund Farm logo in its brand. The navbar links collapse down to a burger icon with a dropdown menu on smaller decies. 

- Footer: The Footer provides links to each of the venue's social media pages in the form of icons. 

### Home Page 

- A large image and small paragraph of text in the header draws the user in. A button at the bottom of this paragraph links to the contact page. 

- Bootstrap cards arranged in a responsive grid summarise the services the venue provides along with attractive images. 

### Gallery Page

- A Bootstrap image carousel displays several images whilst removing the need to scroll between images. 

- A paragraph of text above the carousel explains how the carousel works to suers. 

## Contact Page

- A Bootstrap form is used to collect user's email, name and message. 

- A submit button links to the thanks page. 

## Thanks Page 

- A paragraph thanking users for their submission and informing them that they will recieve a response as soon as possible at the top of the page. 

- A button linking back to the home page. 

- A large image filling the bottom of the page. 

### Testing 

## Validation 

- HTML was validated using ![alt text](https://validator.w3.org/ "W3C Markup Validator")
- CSS was validated using ![alt text](https://jigsaw.w3.org/css-validator/ "W3C CSS Validator")

## Attributions 

### Frameworks Used

- ![alt text](https://getbootstrap.com/docs/5.3/getting-started/introduction/ "Bootstrap 5") was used for basic elements and styles. 

### Libraries Used

- Fonts used were from ![alt text](https://fonts.google.com/ "Google Fonts")

- Icons used were from ![alt text](https://fontawesome.com/v4/icons/ "Font Awsome")

## Other tools used

- Favicons were generated by ![alt text](https://favicon.io/ "favicon.io")

- [alt text](https://autoprefixer.github.io "Autoprefixer") to add css prefixes required for consistency across browsers. 

### Images

- main-image.webp: ![Photo by Joel Paim from Pexels](https://www.pexels.com/photo/wedding-altar-set-up-2434255/)

- barn.webp: ![Photo by Jonathan Borba from Pexels](https://www.pexels.com/photo/beautiful-rustic-barn-wedding-venue-with-decor-29051754/)

- marquee.webp: ![Photo by Ollie Craig from Pexels](https://www.pexels.com/photo/aerial-view-of-a-vineyard-9596635/)

- buffet.webp: ![Photo by Danny Audiovisual from Pexels](https://www.pexels.com/photo/luxurious-brunch-buffet-with-pastries-and-flowers-28425149/)

- cottage.webp: ![Photo by Lina Kivaka from Pexels](https://www.pexels.com/photo/black-bicycle-parked-beside-white-wooden-chair-3639542/)

- party.webp: ![alt text](https://www.pexels.com/photo/the-newlyweds-and-wedding-guests-at-the-reception-outdoors-at-night-15964967/ "Photo by Danik Prihodko from Pexels")

- lambs.webp: ![alt text](https://www.pexels.com/photo/photo-of-lambs-sitting-on-the-grass-2156310/ "Photo by Lone Jensen from Pexels")

- reception: ![alt text](https://www.pexels.com/photo/dining-table-and-chairs-set-13788574/ "Photo by Rene Terp from Pexels")

- altar.webp: ![alt text](https://www.pexels.com/photo/wedding-altar-set-up-2434255/ "Photo by Joel Paim from Pexels")

- image used to create favicons:![alt text](https://github.com/twitter/twemoji/blob/master/assets/svg/1f33e.svg "tweemoji, copyright 2020 Twitter"). Licensed under ![alt text](https://github.com/twitter/twemoji/blob/master/assets/svg/1f33e.svg "CC-BY 4.0")

 ### Stack Overflow

- [Stack Overflow](https://stackoverflow.com/questions/37287153/how-to-get-images-in-bootstraps-card-to-be-the-same-height-width "Stack Overflow")


`.card-img {
    width: 100%;
    height: 300px;
    object-fit: cover;
}`

## Code Institute

- Code Institute Introduction to bootstrap Module 

 ` 
.sharp-corners,
.sharp-corners * { /* selects all elements that have a parent with sharp-corner class */
    border-radius: 0;
} ` 

- Code Institute Boardwalk Games Module 

