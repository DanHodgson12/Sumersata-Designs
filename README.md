# Sumersata Designs

![Sumersata Designs Final Design](/assets/readme-files/sd_final.jpeg)

Sumersata Designs is a craft-design business situated in the South West of England, offering unique crafted products and courses teaching people how to craft like them.

The primary goal of this website is to provide an informative and easy-to-use platform for the user to explore products and coursesm offered by Sumersata Designs, as well as offer the ability for the user to contact the business for craft-design requests.

Visit the deployed site [here](https://danhodgson12.github.io/Sumerata-Designs/).

---

# User Experience (UX)

## Project Goals

* The website can be easily navigated and understood.
* Explains who Sumersata Designs are and what they have to offer.
* Contains clear imagery and content.
* Clearly outlines where to purchase products and courses offered.
* Shows a vibrant image gallery of craft designs.
* Provides a simple contact form.

## User Stories

* As a user, I want to be able to navigate the website easily.
* As a user, I want to know who Sumersata Designs are.
* As a user, I want to know how and where to purchase products and courses.
* As a user, I want to see a selection of previous/current designs.
* As a user, I want to be able to contact Sumersata Designs easily.
* As a user, I want to be able to view the website on a variety of screen sizes.

## Colour Scheme

![Colour Scheme](assets/readme-files/sd_color_scheme.png)

The colours used for this website are:

* Lavender (#b0bdef) - for the header, footer and contact form
* Beige (#d7d5c2) - for the background of the 'Reviews' section
* Off-white (#fefefc) - for the navbar toggler, nav underlines, social links icons and main background color for each page and all cards
* Light Grey (#5c5c5c) - for the social links, the background colour for the 'Address & Contact' section on the home page, the outline for the input fields of the contact form and the hover effect for the form submit button
* Charcoal (#313131) - for the bulk of the text including the nav title, card text and contact form text, and the nav link underlines

## Typography

The main font used throughout the site is Roboto Condensed, with sans-serif as a fallback if it fails to load. This font was suggested on [figma.com](https://www.figma.com/google-fonts/roboto-font-pairings/#:~:text=Roboto%20font%20pairings,Nunito%2C%20Raleway%20and%20Space%20Mono.) as a good font pairing with Lora, which is used for all headings and the nav title. Serif is used as a fall-back for Lora.

## Wireframes

[Figma](https://www.figma.com/) was used to showcase the visuals of each of the three pages of the site and where each of the elements within each page sit.

The [full version of wireframes](https://www.figma.com/file/OYkMASdYDDyC3K3OuCFwXX/Sumersata-Designs?type=design&node-id=3-210&mode=design&t=o6YosKl7NdoBeGkW-0) can be viewed to see the layout of all three pages across the three main screen sizes.

Page | Wireframe
--- | ---
Home section | ![Home section wireframe image](/assets/readme-files/home-section.png)
Gallery section | ![Gallery section wireframe image](/assets/readme-files/gallery-section.png)
Contact Us section| ![Contact Us section wireframe image](/assets/readme-files/contact-us-section.png)

[Back to top &#8682;](#sumersata-designs)

# Features

## General

* The website was designed from a mobile-first perspective.
* The website is responsive on all screen sizes, including very small screens such as the Galaxy Fold.

### Header

![Header on large screen sizes](/assets/readme-files/header-lg.jpeg)

The header consists of:

* The business logo in the top left - this is a clickable link that takes the user to the home page.
* The business name/title and their slogan - this is also a clickable link that takes the user to the home page.
* Navigation links for all three pages of the website - each link has a dark grey underline when hovered over and an off-white underline for the active page.

On medium and small screen sizes, the navigation links turn into a Navbar Toggler which expands and collapses when clicked on.

![Header on medium and small screen sizes - collapsed](/assets/readme-files/header-sm-md-clpsd.jpeg)

When expanded, the nav links are displayed vertically with the same underline and 'active' features as the large screen size header.

![Header on medium and small screen sizes - expanded](/assets/readme-files/header-sm-md-xpnd.jpeg)

On very small screen widths - 333px or less - the logo gets hidden otherwise there's not enough room for all the features of the header.

![Header on very smal screen sizes](/assets/readme-files/header-vs.jpeg)

### Footer

![Footer on large screen sizes](/assets/readme-files/footer-lg.jpeg)

The footer consists of:

* Copyright information on the left.
* Social links on the right - these are clickable links that go to their respective social pages:
  * Etsy
  * Facebook
  * Instagram
  * Twitter
  * Youtube

On medium and small screen sizes, the social links and copyright information stack on top of each other. This seems more visually appealing and stops the footer becoming cramped.

![Footer on medium and small screen sizes](/assets/readme-files/footer-sm-md.jpeg)

## Home Page

* The content of all sections of the home page stays the same - only layout and sizing changes.

### About Us

![About section image](/assets/readme-files/about-section.jpeg)

The About section consists of:

* An image of the business owners.
* Text explaining the 'who' and 'what' of the business.

### Shops/Courses/Events

![Shops/Courses/Events image](/assets/readme-files/shops-section.jpeg)

This section consists of three cards describing and taking the user to the following:

* Shop - the [Sumersata Designs Etsy](https://www.etsy.com/shop/SumersataDesigns) store where the user can browse or purchase pre-made designs.
* Courses - the [CraftCourses.com](https://www.craftcourses.com/craft-workshops?keyword=sumersata) website where the user can browse or purchase crafting courses that Sumersata Designs offer.
* Events - the [Sumersata Designs Facebook](https://www.facebook.com/SumersataDesigns) page where the user can see any upcoming events for the business.

These are all clickable links and there's a hover effect for each card to accentuate this.

### Reviews/Testimonies

![Reviews/Testimonies image](/assets/readme-files/reviews-section.jpeg)

The Reviews section consists of:

* The top rated reviews left by customers who've experienced courses offered by Sumersata Designs.
* An annotated image of a customer whom attended a course and left a review.
* A Silver Certificate of Excellence awarded to Sumersata Designs by CraftCourses.com.

### Address/Map

![Address/Map image](/assets/readme-files/address-section.jpeg)
This section consists of:

* The business address and contact email address.
* An interactive Google Map pinned to the business address.

## Gallery Page

This section consists of images of a selection of designs by Sumersata Designs. The gallery has been styled on the 'Masonry' layout, although altered to ensure there's no dead space at the bottom of the page.

The layout of the gallery columns and sizing changes depending on screen size (pictured below), but the content stays the same.

* On screens wider than 1024px, all gallery images are reduced in opacity, with an effect that reveals each image when you hover over them.

Screen Size | Gallery
--- | ---
Desktop | ![Desktop Gallery image](/assets/readme-files/gallery-lg.jpeg)
Tablet | ![Tablet Gallery image](/assets/readme-files/gallery-md.jpeg)
Phone | ![Phone Gallery image](/assets/readme-files/gallery-sm.jpeg)

## Contact-Us Page

* The content of all sections of the home page stays the same - only layout and sizing changes.

This section consists of:

* A full screen background image in the form of a wrapper around Header, Main section and Footer.
* A contact form containing the following inputs:
  * Name
  * Email
  * Textarea - where users can request a design idea
  * Checkbox - where users can sign up to the weekly newsletter
  * Submit button

On larger screen sizes, the form is positioned to the left of the screen in order to show more of the background image. This also helps the form remain a sensible width and remain visually appealing.

![Contact Us Page on large screen size](/assets/readme-files/contact-lg.jpeg)

On smaller screen sizes, the width of the form covers around 80% of the width of the screen and is positioned centrally.

![Contact Us page on smaller screen sizes](/assets/readme-files/contact-sm.jpeg)

[Back to top &#8682;](#sumersata-designs)

# Technologies Used

## Languages Used

* [HTML](https://en.wikipedia.org/wiki/HTML)
* [CSS](https://en.wikipedia.org/wiki/CSS)

## Frameworks, Libraries and Programs Used

* [Google Fonts](https://fonts.google.com/)
  * Google fonts was used to import Lora and Roboto Condensed into the head of each page. These fonts are used throughout the website.

* [Font Awesome](https://fontawesome.com/)
  * Font Awesome was used to add icons for the social links and stars for the reviews section, to add a better user experience.

* [CodeAnywhere](https://app.codeanywhere.com/)
  * CodeAnywhere was used for writing, committing and pushing the code to GitHub.

* [Bootstrap](https://getbootstrap.com/)
  * Bootstrap was used to develop a responsive mobile-first design using an assortment of templates.

* [Chrome DevTools](https://developer.chrome.com/docs/devtools/)
  * Chrome DevTools was used throughout the development of the website to test ideas and responsiveness, and debug issues that arose.

* [W3C Markup Validator](https://validator.w3.org/)
  * W3C Markup Validator was used to validate the HTML code.

* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
  * W3C CSS Validator was used to validate the CSS code.

* [Favicon.io](https://favicon.io/)
  * Favicon.io was used to create the site favicon.

[Back to top &#8682;](#sumersata-designs)

# Testing

## Testing User Stories

* As a user, I want to be able to navigate the website easily.
  * Navigation links have been placed at the top right of the page for easy navigation across each page.
  * A white underline on the navigation link indicates which page the user is currently on.
  * Darker underlines appear when the user hovers over each link.
  * The Header's Logo is clickable and takes the user back to the home page, as it [standard practice](https://www.nngroup.com/articles/homepage-links/) with modern websites.
* As a user, I want to know who Sumersata Designs are.
  * An About section explains to the user who the business owners are and what they have to offer.
  * A image of the business owners let the user see the business owners.
* As a user, I want to know how and where to purchase products and courses.
  * The Etsy 'shop card' let's the user visit the Sumersata Designs Etsy storefront and browse products.
  * The Courses 'shop card' let's the user visit the Sumersata Designs CraftCourses storefront and browse courses taught by the business.
  * Each card is a clickable link.
  * Each card is accentuated by a shadow when the user hovers over them.
  * The reviews section provides the user with reassurance.
* As a user, I want to see a selection of previous/current designs.
  * The Gallery page displays a wide range of products designed by Sumersata Designs.
* As a user, I want to be able to contact Sumersata Designs easily.
  * The Contact Us page let's the user fill in their details to get in touch with Sumersata Designs.
  * The Home page also provides the user with a contact email.
  * The Home page contains an address for the business and an interactive map to find the business.
* As a user, I want to be able to view the website on a variety of screen sizes.
  * The website is responsive across all screen sizes.

## Code Validation

* The [W3C Markup Validator](https://validator.w3.org/) and [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) services were used to checl for any code errors or misuse of syntax/elements.

  * The W3C Markup Validator returned a few errors:

    * The use of an aria-label on a div element which containtd a background image. This was overcome by adding an "sr-only" Bootstrap class to a 'p' element which a description of the image.
    * The use of a div element inside a figure element. This was overcome by changing the element to a span and moving it inside the ficcaption element.
    * The use of a 'section' element without a heading. This was overcome by removing it altogether, as it didn't serve a purpose.
    * The form inputs and labels missing ID attributes which were added shortly after.

  * The W3C CSS Validator returned no errors in the code.

## Lighthouse Report

Lighthouse in Google Chrome Dev Tools was used to test performance, accessibility, best practices and search engine optimisation of the webpage.

### Home Page

* Performance was somewhat hindered by an error message stating that the images didn't have efficient cache policies - performance was different on each lighthouse report despite no changes made.
* Suggestions were made to reduce file size. Decided not to as the images on this page were already at the smallest file size and pixel width/height they could be before image distortion.
  
![Home Page Lighthouse Report](/assets/readme-files/lh-home.jpeg)

### Gallery Page

![Gallery Page Lighthouse Report](/assets/readme-files/lh-gallery.jpeg)

### Contact Us Page

![Contact Us page Lighthouse Report](/assets/readme-files/lh-contact.jpeg)

## Tools Testing

* [Google Chrome DevTools](https://developer.chrome.com/docs/devtools/)
  * Google Chrome DevTools was used throughout the development process to test, exlpore and make changes to the HTML and CSS of the webpage.

* Responsiveness
  * [Responsive Design Checker](https://www.responsivedesignchecker.com/) was used to check responsiveness across a variety of devices and screen sizes.
  * [Am I Responsive?](https://ui.dev/amiresponsive) was used to check responsiveness across different screen sizes and generate the mockup final image.
  * [Google Chrome DevTools](https://developer.chrome.com/docs/devtools/) was used to check responsiveness across different screen sizes during the development and testing phases.

## Manual Testing

### Browser Compatibility

Browser | Outcome | Pass/Fail
--- | --- | ---
Google Chrome | No appearance, responsiveness or functionality issues | Pass
Safari | No appearance, responsiveness or functionality issues | Pass
Mozilla Firefox | No appearance, responsiveness or functionality issues | Pass
Microsoft Edge | No appearance, responsiveness or functionality issues | Pass
  
### Device compatibility

* The website was tested across a wide varietty of devices using [Google Chrome DevTools](https://developer.chrome.com/docs/devtools/) & [Responsive Design Checker](https://www.responsivedesignchecker.com/) - no appearance, responsiveness or functionality issues were found.

### Common Elements Testing

#### General
  
Feature | Outcome | Pass/Fail
--- | --- | ---
  NavBar Logo | Takes user back to home page as expected | Pass
  NavBar Title | Takes user back to home page as expected | Pass
  Nav Links | Each link takes user to relevant page | Pass
  Nav Link Hover | Shows underline when hovering over links as expected | Pass
  Nav Link Active | Shows underline on active page as expected | Pass
  Nav Toggler | Collapses and exapands with no visible issues | Pass
  Social Links | Each link opens in a new page | Pass

#### Home Page

Feature | Outcome | Pass/Fail
--- | --- | ---
Shop Cards | Each link opens in a new tab | Pass
Shop Card Hover | Each card has a border shadow when hovered over as expected | Pass
Review Figcaptions | Each link opens to the relevant review source | Pass
Google Map | Interactive map functions as expected | Pass

#### Gallery

Feature | Outcome | Pass/Fail
--- | --- | ---
Gallery Images | Number of columns change at breakpoint as expected | Pass
Gallery Image Hover | Hover effect only appears at extra large breakpoint as expected | Pass

#### Contact Us Page

Feature | Outcome | Pass/Fail
--- | --- | ---
Form Inputs | Name and Email inputs required to submit form | Pass
Form Inputs cont. | Design Idea field optional, can be expanded, minimum height effective | Pass
Submit Button | Hover effect works as expected and submits form | Pass

[Back to top &#8682;](#sumersata-designs)

# Finished Product

Page | Image
--- | ---
Home Page | ![Home Page Image](/assets/readme-files/home-page-full.png) Note: The interactive google map did not show in the full screenshot.
Gallery | ![Gallery Page Image](/assets/readme-files/gallery_full.png)
Contact Us | ![Contact Us Page Image](/assets/readme-files/contact-full.png)

[Back to top &#8682;](#sumersata-designs)

# Deployment

# Credits

# Acknowledgements
