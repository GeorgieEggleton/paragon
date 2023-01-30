# Sailing Yacht Paragon

S/Y Paragon website is intended to show people what life on board a sailing yacht is like. The site is aimed at people who are interested in following life at sea and seeing the progress of the boat while travelling around world. It should also give an insite into the type of vessel Paragon is and who the crew are. 

A link to the live site can be found here - https://georgieeggleton.github.io/paragon/



![responsivenessmockup](/assests/images-readme/responsivness-mockup.png)

## Features

### Current Features


#### Logo 
![Logo](/assests/images-readme/logo-screenshot.png)

The Paragon Diamond logo is the boats logo and used around the boat and on ships papers. It features on every page of the website as a link back to the home page. 

#### Favicon
![Favicon](/assests/images-readme/favicon-screenshot.png)

The yachts diamond logo also features as the favicon to help users identify the website when they have multiple tabs open. 

#### Navigation Menu 
![Favicon](/assests/images-readme/nav-menu.png)

This features at the top of all pages (except the 404 page) and has links to each page, home, boat, adventures, & contact. It also loads on the “thank you” page after the contact form has been filled in to allow users to carry on navigation of the site. On a desktop it is displayed horizontally along the top and as the screen size becomes smaller the items will stack vertically. To help users identify which page they are currently on the current page is underlined. 

#### Hero Images 
![Hero Images Selection](/assests/images-readme/hero-images-screenshots.jpg)

Each page features a hero image featuring the boat or scenic locations to give a feel of what life at sea can be like. 

#### Hero Image Text 
There is a text box over the hero image on each page that introduces the user to page and gives a short overview of what that page is about. On a desktop this can will display offset to the left or right depending on the image behind and what works best with that image. On a smaller screen such as a mobile the text box will be more centered to allow for the text to be easily readable. 

#### Opening Paragraphs 
The opening paragraphs on the home page and adventures page give a slightly longer explanation of the intentions of the page.  

#### Crew Section 
![Crew Section Desktop](/assests/images-readme/crew-section-desktop.png)

The crew section gives a brief overview of each of the crew on board, including the dogs, and what their background in sailing is. This is designed as a 2x2 grid layout on desktop but once the screen becomes smaller will stack vertically. 

#### The Boat 
On the boat page are the technically drawing of the yacht and a layout plan to show the user in more details the design of the yacht. Below is a table with the basic specifications of the yacht followed by a selection of photos showing what life is like on board the boat.
![Boat page screenshot ](/assests/images-readme/boat-page-screenshot.png)


#### Our adventures  
This page is designed to give the user the change to see what some of the specific location visited are like. This page is designed using accordions to compress the sections to start with making it easier for the user to navigate to the relevant section. This will become more important as more locations are added and the list becomes longer. Originally on the wireframes these were planned as a scrolling carousel of photos but this proved very difficult to do using only html & css and having an open gallery for each made the page too long and busy so the accordions provided a good solution. 
![Boat page screenshot ](/assests/images-readme/adventure-gallery-usage-example.gif)

#### Contact Us  
The contact page features a form for the user to complete if they would like to get in contact. On completion & submission this will re-direct to a “thank-you” page to ensure the user knows that the form has been successfully submitted. All fields are mandatory fields to make sure the user has given enough information to allow a response. 
![Form filled out without including a valid email address](/assests/images-readme/incomplete-form.png)
![Thank you page following successful form completion](/assests/images-readme/thank-you-page.png)

#### Footer
The footer features on each page and has links to the yachts social media accounts (not yet created so currently links to SM home pages). These links open in a new tab to ensure the user doesn’t lose the original site. 

![Footer](/assests/images-readme/footer.png)

### 404 Page 
A 404 page is included and will display if a user navigates to a broken link. The 404 page has a link to allow the user to easily navigate back to the main website without the need of the browsers back button.

![404 Page](/assests/images-readme/404page.png)

## New Features to come

#### Hamburger Menu
On smaller screen I believe it would be a more user friendly experience to use a hamburger menu.

 #### The Crew
Allow the user to click on each crew member to open a full CV as this could also be useful for finding work on other yachts which is done sometimes. 

#### Our Adventures
More locations and larger galleries including videos split into sections – like a ships log

#### The Boat 
Following the technically specification of the yacht I would like to imbed a series of videos which follow the upgrades currently been made to the boat to allow off-grid living in remote locations. Users would be able to use these videos to help with their own conversion works. 


## TESTING 

All HTML and CSS have been run through the W3C validators with no errors found. 

![cssvalidator](/assests/images-readme/css-validator-image.png)

![htmlvalidator](/assests/images-readme/index-check.png)
![htmlvalidator](/assests/images-readme/boat-check.png)
![htmlvalidator](/assests/images-readme/adventure-check.png)
![htmlvalidator](/assests/images-readme/contact-check.png)
![htmlvalidator](/assests/images-readme/thankyou-check.png)
![htmlvalidator](/assests/images-readme/404-check.png)

The site was also run through LightHouse on Google, initially there was a lower than expected performance score due to the large hero images on each page and the crew photos on the home page. This was fixed by compressing the images. using https://tinypng.com/ which resolved the issue. 

![lighthousescore](/assests/images-readme/lighthouse-scores.png)

After deployment the site was tested in:-
- Safari desktop
- Safari mobile 
- Google Chrome
- Firefox

initially it was found that safari desktop was not supporting .webp files that were used on the hero images. As a result these were changed back to compressed .jpgs 


### Link Testing 

- The form was tested and would not submit without the required inputs as expected. On correct completion of the form the page re-directs to the Thank You page as expected. 

- All links in the navigation bar were tested on both desktop and mobile devices and work correctly. 

- The links to social media were tested on both desktop and mobile devices and work correctly. 

![Link Testing Mobile](/assests/images-readme/mobile-link-testing.gif)
![Link Testing Mobile](/assests/images-readme/desktop-link-test.gif)


## Accessibility

![lighthousescore](/assests/images-readme/accessability-score.png)

The site scored well on the LightHouse accessibily score. 

- All images have alt text
- All icon have aria labels for screen readers 
- All text is large and in contrasting colours
- All form fields have labels for screen readers 

## Responsiveness

Media queries were used to allow the site to be responsive to use on desktop and mobile devices. During development this was tested using Google's dev tools. After deployment this was tested on the following devices:
- MacBook Air
- iPhone 13 Pro Max
- iphone X
- Armor 11T
- 2560 x 1080 resolution curved wide screen

The areas that needed adjustment were:-

- The home page hero image uses a cropped version of the image on mobile devices in order to keep the yacht in frame.
- The navigation menu in vertical instead of horizontal on a mobile device for a more user friendly experience. 
- The crew section is 2x2 on a desktop this restructures to a single column on mobile devices to make it easier to read for the user. 
- The lines drawings on the boat page take up a larger area on a mobile device to make it easier to see.
- The boat photos on the bottom of the boat page stack 2x2 on mobile devices to ensure the photos are still big enough to see. 
- The videos stack vertically on a mobile device to make them easier to use. 


All worked as expected except for the bug found on the super wide screen, now resolved. 

## Bugs & Fixes

On the 2560 x 1080 wide cured screen the hero image on the home page was found to crop too much to generate the needed width. This was fixed by adding a maximum width as it was decided it would be unusual for a user to use a wide screen like this for one website at a time. 

The lines drawing was found to overlap the edge of the screen on small mobile devices This has been fixed. 

After deployment the site was tested on Safari Desktop and it was found that it was not supporting .webp files that were used on the hero images. As a result these were changed back to compressed .jpgs 

## Wireframe Design

The initial design was done in balsamic 

### Strategy 
The site should allow the user to learn more about Sailing Yacht Paragon, her crew, and recent trips the boat has been on. It should be accessible and user friendly on  desktop, tablet and mobile devices.  

### Scope
 - The home page should have and introduction to the boat and past and future plans and a short bio for each crew member. 
 - The boat page should have information on the design and specification of the boat. 
 - The adventures page should have image galleries for recent trips the boat has been on.
 - The contact should have a contact from for the user to fill out and get in touch. This will re-direct on successful completion to a thank you page so the user is sure it has been submitted successfully. 

### Structure 
All pages will have the logo and navigation menu at the top of the page and a footer at the bottom with links to social media. This will remain constant on all pages to ensure intuitive use. 

The home page will start with a brief overview of the boat and the future plans and then continue on to shot bio on each of the crew members. 

The boat page will have images of the layout of the boat and rig, a table with the important specifications of the yacht followed by a series of images showing more detail of different areas on board. 

The adventures page will be the page most commonly updated. This will have a series of image galleries split down into different locations / times so the user can easily navigate to the section they are interested in looking at. 

The contact page will have a form for the user to complete to get in contact. This should be simple to fill in, have heading to instruct the user what should be in each field and all fields will be required before submission to ensure we are able to respond to the user.

On successful submission of the form the user should be re-directed to a thank you page to ensure they know the enquiry has been sent. This should be a simple page that then re-directs the user back to the site. 

### Surface
The site should use images that show some of the unique locations the boat has been to along with a clear, crisp design to allow for easy navigation around the site by the user. The imagery and story details about where the boat has recently been and heading to next should encourage the user keep returning to the site to see updates. 

![home page design](/assests/images-readme/homepagedesign.png)
![boat page design](/assests/images-readme/boatpagedesign.png)
![adventure page design](/assests/images-readme/adventurepagedesign.png)
![contact page design](/assests/images-readme/contactpagedesign.png)

## Technologies


- HTML - The main structure of the website uses HTML.
- CSS The website was styled using custom CSS linked to an external file.
- Gitpod - The website was developed using Gitpod.
- GitHub - The site is hosted on GitHub. 
- Font Awesome - Icons for the social media links and the chevrons on the drop down accordions are from [Font Awesome](https://fontawesome.com/) 
- Tinyjpg - [Tiny PNG](https://tinyjpg.com/) was used to compress the size of the hero images
- Favicon.io - A favicon was created of the boats logo using [favicon.io](https://favicon.io/favicon-converter/)
- Balsamiq - wireframes were created using [Balsamiq](https://balsamiq.com/wireframes/desktop/)
- GitHub Pages - The site is deployed using [GitHub Pages](https://github.com/GeorgieEggleton/paragon)
        The deployment steps taken were:-
            - In the GitHub repository, go to the settings
            - In the left hand menu select Pages
            - Set source to "Deploy from a branch"
            - In the Branch section set the drop down menus to "main" & "/(root)"
            - Click 'Save'
            - Refresh the pge and the link will be displayed at the top. 

## Credits

I used the html code structure from Code Institutes "Love Running" walk through project for the footer social media icons. 

I used the following tutorial to help with creating the accorians [MAKE A PURE CSS ACCORDION 
WITHOUT JAVASCRIPT](https://supfort.com/pure-css-accordion-without-javascript)

The home page hero image was taken by [Saltwind Photography](https://www.instagram.com/saltwind_photography/)