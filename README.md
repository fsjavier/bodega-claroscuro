# Bodega Claroscuro

Welcome to Bodega Claroscuro, a fictional business located in northern Spain. The winery produces their own red and white wines, capturing the essence of the region.

The website serves as an online presence to engage wine enthusiasts, offering the possiblity to know more about winemaking and high-quality wines, which can be then purchased.

[View the live site here](https://fsjavier.github.io/bodega-claroscuro/)

![Mockup](documentation/readme_images/mockup.png)

## Table of Contents

* [User Goals](#user-goals)
* [Features](#features)
* [Design](#design)
* [Technologies Used](#technologies-used)
* [Testing](#testing)
* [Deployment](#deployment)
* [Credits](#credits)

## User Goals

* As a new user, I want to:
  1. Know what wines are produced, their characteristics and price.
  2. Learn about the winemaking process.
  3. Discover the location and opening times.
  4. Find out how to contact them.

* As a returning user, I want to:
  1. Stay updated on any changes or news.
  2. Know the current offered wines.
  3. Easily access the contact information.


## Features

### Home

* Navigation Bar
  * The navigation bar is present in all pages. It keeps always the same position for consistency and to make it easier for user to navigate the website.
  * It includes the logo (clickable, linking to the home page) and links to "Home", "Oud wines" and "Contact". It's responsive, on wide screen the logo is on the left side and the navigation bar on the right, while on smaller screens the navigation bar moves under the logo.
  * It's implemented in all pages.

![Logo and navigation](documentation/readme_images/header.png)

* Landing Page image
  * An image of the vineyard at sunset occupies the majority of the screen. As specialists in both white and red wines, this carefully chosen moment captures the essence of the winery, where the interplay of light and darkness symbolizes the meaning behind the name, Claroscuro.

![Vineyard](documentation/readme_images/hero_image.png)

* The latest from the vineyard section
  * This section has a double purpose: 
    * Give a direct way to access the wines available with the call to action "Discover our wine selection".
    * Offer information about the winery, which will be periodically updated with news like the production of a new wine.
 
 ![The latest from the vineyard](documentation/readme_images/latest_vineyard.png)

* Get in touch section
  * Here users are informed about the possibility of visiting the winery and are encouraged to contact with the call to action "Request information"

![Vineyard](documentation/readme_images/get_in_touch.png)

* Footer
  * Like with the navigation bar, its design is responsive and consistent in all pages.
  * It includes the shop opening hours and the links to social media, which open in a new tab.
  * It's implemented in all pages except the 404 page.

![Vineyard](documentation/readme_images/footer.png)

### Our wines

* This page gives an overview of all available wines, split into two sections: Red wines and White wines.
* Each wine is contained in a card like box to separate visually each of them. The cards contain a description of the wine and its price.
* The design is responsive, with two columns of cards for wide screens and the image of the bottle and text next to each other. For mid size screen there is only one column of cards. For the smallest screens there is also one column and the text moves below the image.

![Our wines](documentation/readme_images/our_wines.png)

### Contact

* This page is divided in two parts: a contact form and the location.
  * The contact form section is the way for users to request information or provide feedback. It has 3 mandatory fields (first name, last name and email) and optional message and checkbox to receive emails with the latest news and offers.
  * The location section contains key points for users who want to visit the winery and shop including a embeded map.
  * The design is responsive, with the sections next to each other on wide screens and the location section moving below the contact form on small screens.

![Contact](documentation/readme_images/contact.png)

* Submitting successfully the contact form loads the contact-confirmation.html page, where the user gets confirmation of submission and can navigate back to the Home page.

![Contact confirmation](documentation/readme_images/contact-confirmation.png)

### 404 page

* A custom 404 page will be displayed if the users tries to navigate to a page that can't be loaded.
* It maintains the look and feel of the website and provides users with the ability to navigate back through links.

![404 page](documentation/readme_images/404-page.png)

### Favicon

* A site wide favicon provides an image with the look of the website in the tabs header, allowing users to easily find it among several open tabs.

![favicon](documentation/readme_images/favicon.png)

### Features left to implement

* Add an "about us" page, with information dedicated to the winery and its winemaking process.
* Add online shop functionality, so that users can purchase wine online and have it delivered.
* Make the wines section more interactive - Replace the current style by images of just the bottle and wine name, giving then the user the option to navigate to a details page of each wine with a more thorough description.


## Design

### Wireframes

* Home

![Wireframe Home](documentation/wireframes/wireframe_home.png)

* Our wines

![Wireframe Our wines](documentation/wireframes/wireframe_wines.png)

* Contact

![Wireframe Contact](documentation/wireframes/wireframe_contact.png)

## Technologies Used

### Languages

* HTML for the sctructure of the website.
* CSS for the style.

### Frameworks and tools

* [Codeanywhere](https://codeanywhere.com) was the IDE used to develop the website.
* Git was used for version control.
* [GitHub](https://github.com) is used to host the code and deploy the website.
* [Balsamiq](https://balsamiq.com/wireframes) was used to create the wireframes.
* [Google Fonts](https://fonts.google.com) was used to import the Montserrat and Poiret One fonts.
* [Font Awesome](https://fontawesome.com) was used to import the icons.
* [TinyPNG](https://tinypng.com) was used to compress the images.
* [Convertio](https://convertio.co) was used to convert the images to webP.
* [Favicon](https://favicon.io/) to create the favicon files and links.

## Testing

### Validator Testing

#### HTML

All pages passed without errors or warning through the the W3C Markup Validation Service.

* Home page

![Home page HTML validator result](documentation/tests/test_html_home.png)

* Our wines page

![Our wines page HTML validator result](documentation/tests/test_html_our-wines.png)

* Contact page

![Contact page HTML validator result](documentation/tests/test_html_contact.png)

#### CSS

No errors were found through the W3C Jigsaw CSS Validation Service. The report can be found [here](documentation/tests/test_css_report.pdf).

![W3C CSS validator result](documentation/tests/test_css.png)

### Accessibility
 
#### Lighthouse

Lighthouse from Google Chrome Developer Tools was used to test performance and accessibility.
    
* Home
    
![Home page Lighthouse report](documentation/tests/lighthouse_home.png)

* Our wines

![Our wines page Lighthouse report](documentation/tests/lighthouse_our-wines.png)

* Contact

![Contact page Lighthouse report](documentation/tests/lighthouse_contact.png)
  
#### Wave WebAIM

The WAVE WebAIM web accessibility tool was used during the dvelopment and for final testing of the website to check there were no accessibility problems.

No errors were found, the only alert was due to redundant links. This was due to having the same links in the navigation bar and some other parts of the website (e.g. the link to home in the logo.).

### Manual Testing

#### User goals fulfillment

| Type of user | Goal | Steps | Feature | Outcome |
|--------------|------|-------|---------|---------|
| New /<br>Returning | Know what wines are produced, their characteristics and pricing. | Option 1: Go to "Our wines" on the top navigation bar.<br><br> Option 2: Scroll down to "The latest from the vineyard" and click on "Discover our wine selection". | Option 1: Navigation bar. <br><br> Option 2: The latest from the vineyard section. | Works as expected. |
| New | Learn about the winemaking process. | At the moment this can only be done requesting a tour.<br><br>Option 1: Go to "Contact" on the top navigation bar.<br><br> Option 2: Scroll down to "Get in touch" and click on "Request information".<br><br> From there, fill out the contact form. | Option 1: Navigation bar. <br><br> Option 2: Get in touch section.<br><br>Contact form. | Works as expected. |
| New | Discover the location and opening times. | Opening times are located at the footer of each page and on the "contact page".<br><br>Option 1: Go to "Contact" on the top navigation bar.<br><br> Option 2: Scroll down to "Get in touch" and click on "Request information".<br><br>See "Where to find us section". | Option 1: Navigation bar. <br><br> Option 2: Get in touch section.<br><br>Footer<br><br>Where to find us section. | Works as expected. |
| New /<br>Returning | Find out how to contact the winery. | Option 1: Go to "Contact" on the top navigation bar.<br><br> Option 2: Scroll down to "Get in touch" and click on "Request information".<br><br> From there, fill out the contact form. | Option 1: Navigation bar. <br><br> Option 2: Get in touch section.<br><br>Contact form. | Works as expected. |
| Returning | Stay updated on any changes or news | Option 1: Scroll down to "The latest from the vineyard section".<br><br> Option 2: Request to receive news per email through the contact page.<br><br> From there, fill out the contact form, checking the box. | Option 1: The latest from the vineyard section. <br><br> Option 2: Get in touch section.<br><br>Contact form. | Works as expected. |

#### Functional testing

All links have been tested to ensure they load the right page without errors.

* Navigation bar
  * The link in the logo links to the Home page
  * The menu links navigate to the "Home", "Our wines" and "Contact" pages respectively.
  * The active page is highlighted with a bigger font and a glass of wine icon.
  * Hovering over an inactive page in the menu increases its size.

* Footer
  * All socia media links open its respective page (Facebook, Twitter, Youtube, Instagram) in a new tab.

* Hovering over the link with the text "Discover our wine selection" in "The latest from the vineyard" section higlights it changing its color. Clicking on it loads "Our wines" page.

* Hovering over the link with the text "Request Information" in "Get in touch" section higlights it changing its color. Clicking on it loads "Our wines" page.

* Form in Contact page and contact confimation page
  * The first three fields are required and the form can't be submitted unless they are filled out.
  * Sending a form loads the "Thank you" page. The link to return to Home page works correctly.

* The embedded Google Map is displayed correctly and can be interacted with.

* The 404 page is loaded if a page can't be loaded. The link to the Home page works correctly.

#### Responsiveness

All pages have been tested for responsiveness with Google Chrome Developer Tools on screens from 280px, making sure the content adjusts correctly on all screen sizes.

On physical device, it has been tested on iPhone 13 in vertical and horizontal orientation.

#### Browsers compatibility

The website has been tested in the following browsers on desktop, without finding any issues:

* Chrome
* Safari
* Firefox
* Opera
* Edge

### Bugs

One of the wine bottle images had incorrect aspect ratio, so in big screen the image and text in the grid looked misaligned. This has been fixed resizing the image, but in the future the images should be replaced for new ones made with the required size.

## Deployment

### Deployment to GitHub Pages

* The site was deployed to GitHub pages. The steps to deploy are as follows:
  * In the GitHub repository, navigate to the Settings tab
  * From the menu on left select 'Pages'
  * From the source section drop-down menu, select the Branch: main
  * Click 'Save'
  * A live link will be displayed in a green banner when published successfully.

The live link can be found here - https://fsjavier.github.io/bodega-claroscuro/

### How to clone the repository

* Go to https://github.com/fsjavier/bodega-claroscuro
* Click on the code drop down button, then click on HTTPS and copy the link to the clipboard.
* Open a GitBash terminal and navigate to the directory where you want to locate the clone.
* Type git clone copied-git-url and press the Enter key.

The project will now of been cloned on your local machine for use.

## Credits

### Content

* The location of the winery is a tribute to the family hometown, but it's not a specific address.
* The text for the wines has been written by me but enhanced using ChatGPT for richer descriptions.

### Code

* Code for the social media links in the footer is based on the Code Institute "Love Running" walkthrough project.
* Approach on how to apply Flexbox from tutorials by:
  * [Dee MC](https://www.youtube.com/watch?v=2uvyx4YK_rQ)
  * [Kevin Powell](https://www.youtube.com/playlist?list=PL4-IK0AVhVjMSb9c06AjRlTpvxL3otpUd)
* Approach on how to apply Grid from tutorial by:
  * [Kevin Powell](https://www.youtube.com/playlist?list=PL4-IK0AVhVjPv5tfS82UF_iQgFp4Bl998)
* Inspiration for background blend mode from [W3Schools](https://www.w3schools.com/cssref/pr_background-blend-mode.php)

### Media

* hero-image: Photo by [Boudewijn Boer](<https://unsplash.com/@boudewijnboer?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText>) on [Unsplash](<https://unsplash.com/photos/qT515JdZNy8?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText>)
* about-grapes: Photo by [Nacho Domínguez Argenta](https://unsplash.com/pt-br/@nachoargenta?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/photos/QVdFEzkAkmg?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
* wine-bottle: Photo by [Jadon Barnes](https://unsplash.com/@jadonbarnes?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](Unsplash)
* wine-cellar: Photo by [Oleksandr Gamaniuk](https://unsplash.com/@oleksander_gamaniuk?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/photos/pKfpCKgkLwo?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
* red-wine-1: Image by [mkt102](https://pixabay.com/users/mkt102-1390883/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=1010656) from [Pixabay](https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=1010656)
* red-wine-2: Image by [mkt102](https://pixabay.com/users/mkt102-1390883/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=1010657) from [Pixabay](https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=1010657)
* red-wine-3: Image by [Christo Anestev](https://pixabay.com/users/anestiev-2736923/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=2041225) from [Pixabay](https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=2041225)
* red-wine-4: Image by [Christo Anestev](https://pixabay.com/users/anestiev-2736923/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=2041226) from [Pixabay](https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=2041226)
* white-wine-1: Image by [Alexis León](https://pixabay.com/users/alexisleon-1398503/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=939640) from [Pixabay](https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=939640)
* white-wine-2: Image by [avgustintomaz](https://pixabay.com/users/avgustintomaz-15252385/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=4981815) from [Pixabay](https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=4981815)
* white-wine-3: Image by [Gábor Adonyi](https://pixabay.com/users/adonyig-4265448/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=3546566) from [Pixabay](https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=3546566)
* white-wine-4: Image by [Christo Anestev](https://pixabay.com/users/anestiev-2736923/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=2026626) from [Pixabay](https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=2026626)
* 404 page: Image by [Alexa](https://pixabay.com/users/alexas_fotos-686414/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=642267) from [Pixabay](https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=642267)

### Acknowledgments

Thank you to my mentor Gareth McGirr for his guidance, feedback and resources provided.