# Lund Farm

This website is designed to showcase a wedding venue, Lund Farm and its services whilst providing users with a way of contacting the venue and finding relevant social media pages. 

## Table of Contents

1. <details open>
    <summary><a href="#ux">UX</a></summary>

    <ul>
    <li><details>
    <summary><a href="#goals">Goals</a></summary>

    - [Visitor Goals](#visitor-goals)
    - [User Stories](#user-stories)

    </details></li>

    <li><details>
    <summary><a href="#visual-design">Visual Design</a></summary>

    - [Wireframes](#wireframes)
    - [Colours](#colours)
    - [Fonts](#fonts)
    - [Icons](#icons)
    - [Images](#images)

      </details></li>

    </ul>

</details>

2. <details open>
    <summary><a href="#page-elements">Page Elements</a></summary>

    <ul>
    <li>

    - [All Pages](#all-pages)
    - [Index Page](#index-page)
    - [Gallery Page](#gallery-page)
    - [Contact Page](#contact-page)
    - [Thanks Page](#thanks-page)
    - [404 Page](#404-page)
    </li>

    </ul>
    </details>


3. <details open>
    <summary><a href="#testing">Testing</a></summary>

    <ul>

    <li><details>
    <summary><a href="#validation">Validation</a></summary> 

    - [HTML Validation](#html-validation)
    - [CSS Validation](#css-validation)

    </details></li>

    <li><details>
    <summary><a href="#automated-testing">Automated Testing</a></summary>

    - [Lighthouse Testing](#lighthouse-testing)
    - [Wave Accessibility Testing](#wave-accessibility-testing)

    </details></li>

    </li>
</ul>
</details>

4. <details open>
    <summary><a href="#deployment">Deployment</a></summary>
    <ul>
    <li>

    - [Cloning the GitHub Repository using Gitpod](#cloning-the-github-repository-using-gitpod)
    - [Deploying Your Repository to GitHub Pages](#deploying-your-repository-to-github-pages)

    </li>
</ul>

</details>

5. <details open>
    <summary><a href="#attributions">Attributions</a></summary>

    <ul>

    <li>

    - [Frameworks Used](#frameworks-used)
    - [Libraries Used](#libraries-used)
    - [Other Tools Used](#other-tools-used)
    - [Images](#images)
    - [Code From External Sources](#code-from-external-sources)

</li>

</ul>

</details>

----

# UX

## Goals

### Target Audience

- Engaged Couples looking for a wedding venue.

- Wedding planners looking for information about the venue.

- Wedding guests looking to familiarise themselves with the venue before attending a wedding there. 

### User Stories 

The GitHub project board containing Lund Farm user stories can be found [here](https://github.com/users/ElFalch/projects/2/views/1).

- These user stories include some future ideas for the project (labelled as "wont-have" in the project board). 

## Visual Design

### Wireframes

#### Updates to design since creating wireframes: 

- Included a button in the home page introduction section which links to the contact page, to allow for users to get in touch more easily. 

- Changed the photo grid in the gallery page to a carousel to allow for less scrolling, particularly in mobile and tablet viewports. 

- No image was incldued in the contact page to reduce drowding for a clearer presentation of the contact form. 

#### Mobile Wireframe

![Mobile wireframe](https://github.com/ElFalch/lund-farm/blob/main/assets/images/wireframes/lund_farm_mobile_wireframe.png "Mobile wireframe")

#### Tablet Wireframe


![Tablet wireframe](https://github.com/ElFalch/lund-farm/blob/main/assets/images/wireframes/lund_farm_tablet_wireframe.png "Tablet wireframe")

#### PC Wireframe

![PC wireframe](https://github.com/ElFalch/lund-farm/blob/main/assets/images/wireframes/lund_farm_pc_wireframe.png "PC wireframe")


### Colours

![Lund Farm colour palette](https://github.com/ElFalch/lund-farm/blob/main/assets/images/colour-palette/lund-farm.png "Lund Farm colour palette")

The colours used reflect those in the home page main image and convey the cosy, inviting atmsophere of Lund Farm whilst providing enough contrast to be eye-catching and accessible. This increases the likelihood that target users access all aspects of the website and will have a pleasant experience when doing so, increasing the use of the website and business services. 

### Fonts 

The fonts used were chosen as they are rustic and relaxed, reflecting the atmosphere of the venue so that user's impressions of the site and busiess are further improved. Delius Swash Caps was used for the headings because the slightly curled letters add a formal touch, signposting each section of the site to increase ease of navigation for users. Lexend Exa was used for the body because of its clear appearance, so that users are more likely to read all of the information provided. 

### Icons 

Icons were taken from the [FontAwsome](https://fontawesome.com/v4/icons/) icon library. 

- A heart icon is used in the navigation bar brand, reflecting Lund Farm's services at a first-impression level, so that target users are encouraged to use the site and business at a greater level. 

- Icons for Facebook, X (formerly Twitter), Instagram and YouTube are used in the footer as buttons linking to each of these sites, improving the visibility of these links so that more users follow them. 

- An icon with two speech bubbles is used to highlight the button linking to the contact page on the home page, making this button appear more inviting so that more users are encouraged to click it. 

- An arrow icon is used in the gallery page to direct people to the image carousel after reading instructions about how it works, increasing the number of times the carousel images are viewed. 

- A pencil icon is used in the contact page to highlight the message about filling the form out, increasing the number of times the contact form is successfully submitted. 

### Images

Several images have been used across the site, so their size has been reduced as much as possible whilst maintining the high quality needed to attract users. 

- On the home page, a main image that reflects the colour scheme has been used in the header aswell as images for each of the services cards. This reduces the time needed for users to get a first impression of the services provided by the business, increasing the use of services by target users. 

- The gallery page includes a carousel of attractive images of the venue, further conveying the servies provided by the business for users who are interested. 

- On the thanks page, which users are taken to when they submit the contact form, an image has been used to fill empty space and provide some brighter colours and a friendly touch, increasing the impact of the page by and a personal touch, so that users feel certain their message is valued. 

- On the  404 page, which users are taken to when they search for a page which doesn't exist, an image has been used to fill empty space and provide some brighter colours and a friendly touch, so that users are encouraged to visit the page they are directed to (home page). 


# Page Elements 

## All Pages

- Navbar: The navbar provides links to the three main pages of the site and has the Lund Farm logo in its brand. The navbar links collapse down to a burger icon with a dropdown menu on smaller decies. 

- Footer: The footer provides links to each of the venue's social media pages in the form of icons. 

## Home Page 

- Header: A large image, small paragraph of text and a button that links to the contact page. 

- Bootstrap cards arranged in a responsive grid: Summarise the services the venue provides along with attractive images. 

## Gallery Page

- Bootstrap image carousel: displays several images whilst removing the need to scroll between images. 

- Paragraph of text above the carousel: explains how the carousel works.

## Contact Page

- Bootstrap form: collects email, name and message information

- Submit button: links to the thanks page. 

## Thanks Page 

- Paragraph thanking users for their submission and informing them that they will recieve a response as soon as possible at the top of the page. 

- Button: linking back to the home page. 

- Large image: filling space at the bottom of the page. 


## 404 Page 

- Paragraph explaining that unfortunately, the page they are looking can't be found. 

- Button: linking back to the home page. 

- Large image: filling space at the bottom of the page. 


# Testing 

## Validation

### HTML Validation

The HTML for each page was validated used the [W3C Markup Validator](https://validator.w3.org/). No errors or warnings were found for any of the pages. 

| Page          | Result                                                                                                                                                |   
| ------------- |:-----------------------------------------------------------------------------------------------------------------------------------------------------:| 
| index.html    |![Index Page HTML validation](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/validation-images/html-validation-images/index-html-validation.png)    | 
| gallery.html  |![Gallery Page HTML validation](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/validation-images/html-validation-images/gallery-html-validation.png)  |
| contact.html  |![Contact Page HTML validation](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/validation-images/html-validation-images/contact-html-validation.png)  | 
| thanks.html   |![Thanks Page HTML validation](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/validation-images/html-validation-images/thanks-html-validation.png)   |
| 404.html      |![404 Page HTML validation](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/validation-images/html-validation-images/404-html-validation.png)      | 

### CSS Validation 

The CSS stylesheet was validated using [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

| Summary         | Result                                                                                                                                                |   
| --------------- |:-----------------------------------------------------------------------------------------------------------------------------------------------------:| 
| No errors found |![Lund farm CSS validation](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/validation-images/css-validation-images/lund-farm-css-no-errors.png)   | 
| Warnings are the result of Google fonts and css prefixes being used and do not present any issues |![](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/validation-images/css-validation-images/lund-farm-css-warnings.png)|

## Automated Testing

### Lighthouse Testing

- Automated testing of the deployed site for performance, accessibility and best practises was conducted using the [Lighthouse tool](https://developer.chrome.com/docs/lighthouse) within Chrome DevTools.  

#### Lighthouse Report Summaries

The total score for performance for each of the pages ranged from 73% to 99 %. The total score for accessibility and best practices was 100% for each of the pages. 

| Page          | Lighthouse Report Summary                                                                                                                             |   
| ------------- |:-----------------------------------------------------------------------------------------------------------------------------------------------------:| 
| index.html    |![Index Page Lighthouse Report Summary](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/lighthouse-testing/index-lighthouse-summary.png)                       | 
| gallery.html  |![Gallery Page Lighthouse Report Summary](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/lighthouse-testing/gallery-lighthouse-summary.png)                     |
| contact.html  |![Contact Page Lighthouse Report Summary](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/lighthouse-testing/contact-lighthouse-summary.png)                     | 
| thanks.html   |![Thanks Page Lighthouse Report Summary](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/lighthouse-testing/thanks-lighthouse-summary.png)                      |
| 404.html      |![404 Page Lighthouse Report Summary](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/lighthouse-testing/404-lighthouse-summary.png)                         | 

#### Lighthouse performance report diagnostics

The main negative influence upon Lighthouse performance scores for this site was the large size of some images. However, images were optimised and their size was reduced as much as possible whilst maintaining a high quality. Given that this site relies heavily upon attractive images, and that each page loads fairly quickly with an overall performance score of atleast 70%, it was decided to not reduce the size of the images any further. 

Other significant negative influences upon Lighthouse performance scores were related to the loading of external libraries, so couldn't be resolved without removing the content of the website, something which wasn't attempted due to the already high overall performance scores of each page. 

| Page          | Lighthouse Report Diagnostics                                                                                                                         |   
| ------------- |:-----------------------------------------------------------------------------------------------------------------------------------------------------:| 
| index.html    |![Index Page Lighthouse Report Diagnostics](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/lighthouse-testing/index-lighthouse-diagnostics.png)                   | 
| gallery.html  |![Gallery Page Lighthouse Report Diagnostics](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/lighthouse-testing/gallery-lighthouse-diagnostics.png)                 |
| contact.html  |![Contact Page Lighthouse Report Diagnostics](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/lighthouse-testing/contact-lighthouse-diagnostics.png)                 | 
| thanks.html   |![Thanks Page Lighthouse Report Diagnostics](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/lighthouse-testing/thanks-lighthouse-diagnostics.png)                  |
| 404.html      |![404 Page Lighthouse Report Diagnostics](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/lighthouse-testing/404-lighthouse-diagnostics.png)                     | 


### Wave accessibility testing

Further automated testing for the accessibility of the site was conducted using the [Wave Web Accessibility Evaluation Tool](https://wave.webaim.org/).

No accessibility errors were found for the contact, thanks or 404 pages, however, there were alerts relating to redundant links to the home page, due to the navbar brand and navbar menu both containing links to the home page. This alert could be resolved by removing the link from the navbar brand, but this link represents an easy and intuitive way for users to find the home page, so it was decided to keep both navbar links despite the altert. The index and gallery page wave reports also contained the same altert, aswell as some additional alerts and contrast errors. 

For the index and gallery pages, additional alerts related to long alternative text for the main image in the header and the marquee and cottage images in the services cards and gallery carousel. It was decided to retain this alternative text, as this was needed to properly describe the images for those who cannot see them. 

For the Gallery page, contrast errors resulted from a lack of contrast between the "next" and "previous" arrows of the image carousel and the images themselves, however it was decided that an increase in contrast would not be attempted due to 1. the arrows being best placed on top of the images for a consistent, mobile-first design, 2. The variation in colour of the images meaning that no consistent arrow colour could achieve a good level of colour contrast across all images, and 3. the message in the header of the carousel section explaining the use of the white arrows to navigate the image carousel signposting these arrows and making them easier to find despite the lack of colour contrast. 

#### Wave accessibility Report Summaries

| Page          | Wave Report Summary                                                                                                                             |   
| ------------- |:-----------------------------------------------------------------------------------------------------------------------------------------------------:| 
| index.html    |![Index Page Wave Report Summary](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/wave-testing/index-wave-summary.png)                                   | 
| gallery.html  |![Gallery Page Wave Report Summary](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/wave-testing/gallery-wave-summary.png)                                 |
| contact.html  |![Contact Page Wave Report Summary](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/wave-testing/contact-wave-summary.png)                                 | 
| thanks.html   |![Thanks Page Wave Report Summary](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/wave-testing/thanks-wave-summary.png)                                  |
| 404.html      |![404 Page Wave Report Summary](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/wave-testing/404-wave-summary.png)                                     | 

#### Wave accessibility Report Details

| Page          | Wave Report Details                                                                                                                             |   
| ------------- |:-----------------------------------------------------------------------------------------------------------------------------------------------------:| 
| index.html    |![Index Page Wave Report Details](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/wave-testing/index-wave-details-1.png)                                 | 
| index.html    |![Index Page Wave Report Details](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/wave-testing/index-wave-details-2.png)                                 |
| gallery.html  |![Gallery Page Wave Report Details](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/wave-testing/gallery-wave-details-1.png)                               | 
| gallery.html  |![Gallery Page Wave Report Details](https://github.com/ElFalch/lund-farm/blob/main/assets/images/testing-images/wave-testing/gallery-wave-details-2.png)                               |


## Manual Testing 

Manual testing was carried out to ensure all links worked as intended, aswell as the contact form and 404 page. Device mode in [Chrome DevTools](https://developer.chrome.com/docs/devtools) was used to ensure that the design was responsive and that features were fully functional across all device sizes. 

# Deployment

The site was deployed to GitHub pages. The deployed site can be found [here] (https://elfalch.github.io/lund-farm/) 

## Cloning the GitHub Repository using Gitpod

To make a copy of this repository within your own GitHub repository, you should do the following:

1. Open the repository you want to use in gitpod IDE.  

2. Select the folder in which you wish to store the repository and enter the following code into the terminal: 

`git clone https://github.com/ElFalch/lund-farm`

3. Add, commit and push your changes. 


## Deploying Your Repository to GitHub Pages

The steps to deploy to GitHub pages are as follows:

1. In the specific GitHub repository page, select the "Settings" tab in the menu at the top of the screen.
2. Select the "pages" tab on the left-hand side of the screen.
3. Find the "Build and Deployment" section and select "main" from the left-most dropdown menu of the "Branch" sub-section then select "save" **

** Note - deployement may take a few minutes. 

Once deployed, the steps to access your live site are as follows:  

1. In the specific GitHub repository page, select the "Code" tab in the menu at the top of the screen.
2. Refresh the page, then select "Deployments" in the bottom-right corner of the screen
3. Select the link at the top of the screen to open the deployed site. 


# Attributions 

## Frameworks Used

- [Bootstrap 5](https://getbootstrap.com/docs/5.3/getting-started/introduction/) was used for basic elements and styles. 

## Libraries Used

- Fonts used were from [Google Fonts](https://fonts.google.com/)

- Icons used were from [Font Awsome](https://fontawesome.com/v4/icons/)

## Other tools used

- Favicons were generated by [favicon.io](https://favicon.io/)

- [Autoprefixer](https://autoprefixer.github.io) to add css prefixes required for consistency across browsers. 

## Images

- main-image.webp: [Photo by Joel Paim from Pexels](https://www.pexels.com/photo/wedding-altar-set-up-2434255/)

- barn.webp: [Photo by Jonathan Borba from Pexels](https://www.pexels.com/photo/beautiful-rustic-barn-wedding-venue-with-decor-29051754/)

- marquee.webp: [Photo by Ollie Craig from Pexels](https://www.pexels.com/photo/aerial-view-of-a-vineyard-9596635/)

- buffet.webp: [Photo by Danny Audiovisual from Pexels](https://www.pexels.com/photo/luxurious-brunch-buffet-with-pastries-and-flowers-28425149/)

- cottage.webp: [Photo by Lina Kivaka from Pexels](https://www.pexels.com/photo/black-bicycle-parked-beside-white-wooden-chair-3639542/)

- party.webp: [Photo by Danik Prihodko from Pexels](https://www.pexels.com/photo/the-newlyweds-and-wedding-guests-at-the-reception-outdoors-at-night-15964967/)

- lambs.webp: [Photo by Lone Jensen from Pexels](https://www.pexels.com/photo/photo-of-lambs-sitting-on-the-grass-2156310/)

- reception: [Photo by Rene Terp from Pexels](https://www.pexels.com/photo/dining-table-and-chairs-set-13788574/)

- altar.webp: [Photo by Joel Paim from Pexels](https://www.pexels.com/photo/wedding-altar-set-up-2434255/)

- image used to create favicons: tweemoji, copyright 2020 Twitter. Licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)


## Code from external sources

- General website structure taken from [Code Institute Boardwalk Games module project](https://codeinstitute.net/uk-funded-cohorts/?utm_term=code%20institute&utm_campaign=CI%20-%20UK%20-%20Search%20-%20Brand&utm_source=adwords&utm_medium=ppc&hsa_acc=8983321581&hsa_cam=1578649861&hsa_grp=62188641240&hsa_ad=635720257674&hsa_src=g&hsa_tgt=kwd-319867646331&hsa_kw=code%20institute&hsa_mt=e&hsa_net=adwords&hsa_ver=3&gad_source=1&gclid=CjwKCAiAmMC6BhA6EiwAdN5iLboL3Mus4shnMVy0f0w_H3d2NIwegbliRN7ME8yx7dTEaBqlfBIV5xoCtnQQAvD_BwE).

- General Structure and code for dropdown menu contents section of ReadMe taken from the GitHub repository [horizon-photo](https://github.com/Ri-Dearg/horizon-photo/tree/main)

