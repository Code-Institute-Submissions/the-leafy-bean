# The Leafy Bean Website

## Table of Contents

* [Purpose](#purpose)
* [User Experience Design (UXD)](#user-experience-design)
    * [User Stories](#user-stories)
        * [First Time Visitor Goals](#first-time-visitor-goals)
        * [Returning Visitor Goals](#returning-visitor-goals)
        * [Frequent Visitor Goals](#frequent-visitor-goals)
* [Design](#design)
    * [Colour scheme](#colour-scheme)
    * [Wireframes](#wireframes)
    * [Typography](#typography)
    * [Imagery](#imagery)
* [Features](#features)
    * [Existing Features](#existing-features)
    * [Features Left to Implement](#features-left-to-implement)
* [Technologies Used](#technologies-used)
* [Testing](#testing)
    * [Automated Testing](#automated-testing)
    * [Manual Testing](#manual-testing)
* [Deployment](#deployment)
* [Credits](#credits)

------

## Purpose

Many local businesses in Ireland have been hit hard by the COVID-19 pandemic. New Government restrictions have led to shop closures and continued uncertainty for small businesses. As consumers’ buying habits shift predominantly online, it’s more important than ever for small businesses 
to have a strong online presence during these challenging times. 

I have created a fictional local independent coffee shop called The Leafy Bean located in Blackrock, Dublin. The Leafy Bean has a poor online presence and is struggling to reach their customers during the pandemic. They requested a fully responsive website which will allow them to notify their customers of their opening hours in line with government restrictions, and promote their new takeaway coffee service. Furthermore, The Leafy Bean wants to establish itself as a local provider of the best coffee in Blackrock and provide information about its high quality coffee beans.

Please note, this company is entirely fictional and was created for the Code Institute’s Milestone Project 1 as part of their Diploma in Full Stack Software Development. It was developed using the knowledge gained from the HTML, CSS and User Centric Design modules. 

Please see [The Leafy Bean’s](https://jessicajuliet.github.io/the-leafy-bean/) live website. 

![The Leafy Bean website](https://github.com/JessicaJuliet/the-leafy-bean/blob/6eb52d7a9c38ae54053eb01e469f7320fbadf913/testing/amiresponsive.png "The Leafy Bean website")

## User Experience Design

### User Stories

* First Time Visitor Goals

    * As a first-time visitor, I want to be able to navigate through the website easily on mobile to find what I’m looking for
    * As a first-time visitor, I want to see a visually pleasing website with eye-catching coffee related imagery to entice me to buy
    * As a first-time visitor, I want to locate their social media links to see if they have a large social following and whether they're well-rated
 
* Returning Visitor Goals

    * As a returning visitor, I want to find information about their takeaway service 
    * As a returning visitor, I want to check the shop’s opening hours during the current COVID-19 restrictions
    * As a returning visitor, I want to see information about the quality of their coffee beans

* Frequent Visitor Goals

    * As a frequent visitor, I want see if they they take resuable cups
    * As a frequent visitor, I want to check to see if they have a loyalty scheme
    * As a frequent visitor, I want to read about the company to establish whether they're an independent 
    coffee shop or a chain

## Design 

### Colour Scheme
The two main colours used across the website are white and brown to tie in with The Leafy Bean's product offering - coffee. Furthermore, a dark grey was used for the paragraph text, instead of black, to improve its contrast and readability on screens.

Adobe Color was used to create a colour swatch to find the right shade of brown for the site. A dark brown (Hex Code #695138) was used for the H2 headings and a lighter shade of brown (Hex Code #8f6f4d) was used for icons and buttons. 

#### _Adobe Color Swatch_:

![Colour swatches](https://github.com/JessicaJuliet/the-leafy-bean/blob/1bc7680561ed4c7ea9e4e8733e5ad784f6c640cf/assets/img/color-swatches.png "Colour Swatches")


### Wireframes

The Leafy Bean's website is a single page site. A single page design was chosen because the website has a narrow focus and is purely informational. Furthermore it's ideal for a mobile first design and users will have less clicking to do to find the information they need. 

Please see the wireframes below for the varying devices:
* [Mobile Wireframe](https://github.com/JessicaJuliet/the-leafy-bean/blob/d62452db8b21e054deae33caea1cf9dfdeb1d65a/assets/wireframes/mobile-wireframe.pdf)
* [Tablet Wireframe](https://github.com/JessicaJuliet/the-leafy-bean/blob/d62452db8b21e054deae33caea1cf9dfdeb1d65a/assets/wireframes/tablet-wireframe.pdf)
* [Desktop Wireframe](https://github.com/JessicaJuliet/the-leafy-bean/blob/d62452db8b21e054deae33caea1cf9dfdeb1d65a/assets/wireframes/desktop-wireframe.pdf)

A high-fidelity mockup for mobile was also created using Adobe Illustrator to trial the use of colour and to allow for better visualisation of how the website would look prior to commencing coding. 
* [High-fidelity mobile mockup](https://github.com/JessicaJuliet/the-leafy-bean/blob/d62452db8b21e054deae33caea1cf9dfdeb1d65a/assets/wireframes/hifi-mobile-mockup.png)

### Typography

The fonts originally chosen for this website were [Roboto](https://fonts.google.com/specimen/Roboto) and [Playfair Display](https://fonts.google.com/specimen/Playfair+Display?query=playfair), 
based on inspiration take from [The Art of Coffee](https://theartofcoffee.ie/) website. However, once I commenced building the site, 
I didn't feel that Playfair Display tied into the branding I had in mind for The Leafy Bean - a fun and modern coffee shop 
who's knowledgeable about their coffee! 

I trialed new fonts using Google Fonts and Google Chrome Developer tools to view sample text from The Leafy Bean's website in various fonts. Furthermore, I took guidance from Google Font's "Popular Pairings" to find new fonts.  

I decided to change Playfair Display to [Roboto Slab](https://fonts.google.com/specimen/Roboto+Slab?query=roboto) instead. Roboto Slab offers a more fun font with its friendly and open curves, versus Playfair which has a more vintage feel to it. 

### Imagery

The website uses strong impactful coffee related imagery to reinforce The Leafy Bean's product offering and to also appeal to the website user. These images were sourced from [Pexels](www.pexels.com) and [Unsplash](www.unsplash.com) and referenced in the code. In addition, the images give structure and dimension to the website and help provide the user with a positive overall user experience. The size and positioning of these images will vary depending on the screensize. 

Lots of white space was used to help structure and organise the content, improve user experience and improve the legibility of text on the site

## Features

The website is a single page site and is broken down into eight sections. Each section is described in more detail below along with its features and how they meet the visitor goals outlined in the user stories: 

### Existing Features

**Section 1 - Navbar**

The Navbar is fully responsive and collapses down into a hamburger menu on smaller devices. In addition, it provides a full list of links to access each of the key sections on the website, and remains fixed to the top on all devices so the user can easily navigate the site should they not wish to scroll.

> As a first-time visitor, I want to be able to navigate through the website easily on mobile to find what I’m looking for
    
**Section 2 - Hero Image**

The hero image sets the scene for The Leafy Bean's quality product offering by displaying a large and enticing image of coffee and descriptive text overlaying that. 
It includes a CTA which directs users to the shops Opening Hours/ Find Us section of the website. The text displayed shortens down to just the H1 heading on mobile devices so as not to obstruct the users view of the attractive coffee image.

> As a first-time visitor, I want to see a visually pleasing website with eye-catching coffee related imagery to entice me to buy

**Section 3 - Coffee to Go**

The Coffee to Go section provides information about The Leafy Bean's takeaway coffee service. It includes four icons which highlight the shops unique selling points and expand when hovered over on desktop or click on mobile or tablet devices. They allow users to quickly identify The Leafy Bean's key selling points 

> As a returning visitor, I want to find information about their takeaway service

> As a frequent visitor, I want see if they they take resuable cups

> As a returning visitor, I want to see information about the quality of their coffee beans

**Section 4 - Bean Points**

The Bean Points section describes details of the shops loyalty scheme and provides a strong image of coffee beans to capture the users attention.

> As a frequent visitor, I want to check to see if they have a loyalty scheme

**Section 5 - About**

The About Section offers the user more information about The Leafy Bean and their passion for coffee. It also includes a grid of four images to help illustrate the about content. These remain in a grid of four across all devices to reduce the scrolling for users. 

> As a frequent visitor, I want to read about the company to establish whether they're an independent 

**Section 6 - Opening Hours/ Find Us**

The Opening Hours/ Find Us section includes details of The Leafy Bean's opening hours during the COVID-19 pandemic. It also includes an embedded Google map to help users find the shops location.

> As a returning visitor, I want to check the shop’s opening hours during the current COVID-19 restrictions

**Section 7 - Contact**

The Contact section offers a simple contact form to allow the user to send a message to the shop with any queries they may have. The fields are all required and it will not allow a user to submit it unless the email input is valid (contains @).

**Section 8 - Footer**

The Footer highlights the shops contact details and address again it also includes links to their social platforms. These were all included in the Footer because this is a location which they are most commonly expected to be by website users.

> As a first-time visitor, I want to locate their social media links to see if they have a large social following and whether they're well-rated

### Features Left to Implement  

Users would like to have a newsletter to sign up to which provides them which insights on the latest coffee trends. This feature was not implemented in the initial release, but will be addressed for a future release. It's dependent on the growth of The Leafy Bean's marketing team.

## Technologies Used

* [GitHub](https://github.com/)
    * GithHub is the hosting site used to store the source code for the Website

* [Git](https://git-scm.com/)
    * Git was used as the version control software to add, commit and push code to the GitHub repository

* [GitPod]()
    * Git Pod was used as the development environmen to write my code

* [balsamiq](https://balsamiq.com/wireframes/)
    * balsamiq was used to create low-fidelity wireframes of the website

* [Bootstrap](https://getbootstrap.com/)
    * Bootstrap was used throughout the website for the grid layout, navbar, forms and buttons 

* HTML
    * HTML was the main language used to create this website

* CSS
    * Custom CSS was used to add bespoke design

* [Adobe Photoshop](https://www.adobe.com/ie/products/photoshop.html)
    * Photoshop was used to create high-fidelity mock-ups of the website

* [Adobe Illustrator](https://www.adobe.com/ie/products/illustrator.html)
    * Illustrator was used to create the logo and favicon for the website

* [Adobe Color](https://color.adobe.com/)
    * Adobe Color was used to generate a color palette for the website

* [Google Fonts](https://fonts.google.com/)
    * Google Fonts was used to find, sample and import fonts for the website 

* [Font Awesome](https://fontawesome.com/)
    * Font Awesome was used to source the icons used across the site

* JavaScript
    * JavaScript was used to create interactive elements such as the hamburger icon

*  [Am I Responsive](http://ami.responsivedesign.is/#) 
    * Am I Responsive was used to test the website's responsiveness across different screen sizes

* [Responsinator](https://www.responsinator.com/)
    * Responsinator was used to test the website's responsiveness across different screen sizes

* [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools) 
    * Chrome Develiper Tools was used to test the site's responsiveness and to debug the code

## Testing

### Automated Testing

**Responsiveness**

To check the responsiveness of the website across all devices, [Am I Responsive](http://ami.responsivedesign.is/#) and [Responsinator](https://www.responsinator.com/) were used. I input the projects live URL to view it across multiple device sizes.

Furthermore, I regularly used [Google Chrome Developer Tools](https://developers.google.com/web/tools/chrome-devtools) to resize the website on different device sizes throughout coding this project. 

**W3C Validator Tools**

The website HTML and CSS was regularly run through the [W3C Markup Validation Service](https://validator.w3.org/) and [CSS Validation Service](https://jigsaw.w3.org/css-validator/).

* A number of issues were picked up for the styling of the iFrame for the embedded Google Map. It specified that the elements used were obsolete and CSS should be used instead. This issue was fixed by moving the styling from the html file to the css file and removing the unused styles

* Another issue encountered was for the layout of the code for the hero image CTA button. It identified that the button element must not appear as a descendant of the a element. This error was resolved by changing the button element to an a element instead

* The validator also gave the following error "Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections." This issue was resolved by changing the section element to a div instead

### Manual Testing

**User Stories**

* A manual review of the user stories was carried out where automation was not possible. Please view this [here](https://github.com/JessicaJuliet/the-leafy-bean/blob/2f91b40b4944c7997f8f776f745ffd68d4260c17/assets/testing/user-story-testing.pdf).

**Devices**

The website was tested on different physical devices with varying screen sizes including:
* Apple iPhone XS Max
* Samsung Galaxy S5
* Samsung A71
* Apple iPad (6th generation)
* Samsung Galaxy Tab Pro SM-T520
* Macbook 12

**Browsers**

The website was tested across different browsers including Google Chrome and Safari. It renders well on all browsers and works as intended.

**Code Institute peer-code-review review**

The webite was also submitted on the Code Institute's Peer Code Review channel on Slack, which highlighted a few areas for improvements. 

From this feedback, I implemented a hover over effect on the navbar items and removed the "Opening Hours" nav item which linked to the same section as "Find Us". I decided not to change the four icons in the Coffee to Go section into clickable links, as my mentor highlighted that the mouse cursor should make it clear that it's not clickable.

**Issues Encountered**

Overall the website worked well across all device types, however a few minor issues were encountered:

* The Samsugn A71 was set to open websites in 'dark mode' and the website did not appear as well visually on this device until its settings were changed to restore its view. This highlighted the need to implement dark mode functionality in a future release, but is out of scope for this project

* The navbar menu on the Apple iPad jumped onto two lines when displayed horizontally. This issue was fixed by decreasing the amount of padding placed left and right on the navbar from 100px to 80px

* The nav links did not jump to the desired location on the page on mobile and desktop devices. Despite multiple attempts to fix this, it was impossible to get it accurate on each device. Following mentor guidance, this was left as is but could be implemented successfully with JavaScript later down the line. 

## Deployment

### GitHub Project Creation

The project was created using these steps:

1. Click the green 'New' button in my GitHub repositories section
2. Select the Code Institute template
3. Name repository "The Leafy Bean" and give it a description
4. Set repository to 'Public' to ensure the commit history is visible
5. Click 'Create repository'

### GitHub Pages

The website was deployed using these steps:

1. Open The Leafy Bean repository in GitHub
2. Navigate to the 'Settings' tab at the top
3. Scroll down to 'GitHub Pages' section
4. Select 'Branch Master' as the source
5. Click save
6. Click link to live deployed website

### Run Locally

To run the code locally, follow these steps:
1. Navigate to The Leafy Bean repository
2. Click the 'Code' drop down menu
3. Select to copy the GitHub URL from HTTPS box or 'Download Zip'
4. Open a new terminal and type 'git clone' command in the CLI and paste copied URL
5. Alternatively, click 'Open with GitHub Desktop' and follow the steps to complete the clone

## Credits

### Content
* All written content on the website was created by me

### Media 

* The logo and Favicon for The Leafy Bean was designed by me using Adobe Illustrator
* The photos used in this website were obtained from [Pexels](https://www.pexels.com/) and [Unsplash](https://unsplash.com/) and their source is 
referenced in the code
* The icons used across the website were sourced from [Font Awesome](https://fontawesome.com/)

### Acknowedgements 

* A huge source of inspiration for this website was drawn from [The Art of Coffee's](https://theartofcoffee.ie/) website and coffee themed projects on [Behance](https://www.behance.ne)
* My friend, and coffee lover, Aisling gave me an insight into the target audience for this website and what they would hope to gain from it 
* Thank you to my family members for testing the website across their mobile device

