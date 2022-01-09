# Customer Cakery

This project is a static website for a Cake Baking company called Customer Cakery.

[View the website on GitHub pages here](https://zackocall.github.io/customer-cakery/).

# Table of contents

>1. [Overview](#overview)
>2. [UX](#ux)
>    1. [Strategy](#strategy)
>    2. [Scope](#scope)
>    3. [Structure](#structure)
>    4. [Skeleton](#skeleton)
>    5. [Surface](#surface)
>3. [Features](#features) 
>4. [Future Features](#future-features)
>5. [Technology Used](#technology-used)
>6. [Testing](#testing)
>    1. [Browser Testing](#browser-testing)
>    2. [Automated Testing](#automated-testing)
>    3. [Manual Testing](#manual-testing)
>    4. [Bugs](#bugs)  
>7. [Credits](#credits)
>    1. [Content](#content)
>    2. [Images](#images)
>    3. [Code](#code)
>8. [Acknowledgements](#acknowledgements)
>9. [Disclaimer](#disclaimer)

## Overview

**Customer Cakery**

Customer Cakery is a Bespoke Cake baking and decorating company. Customers can enquire for a price of their chosen dream cake for free, Customers can then choose to pay an invoice to also get 3 custom designs from qualified cake decorators for £14.99. After collecting all information, we will send over the pricing and designs within 3 days and offer to make the designs for a set price over the email provided.

The project is developed using HTML and CSS.

# UX

## Strategy

### User Stories

1. As a first-time visitor to the website, I want to know what the company does from the home page
2. As a potential customer, I would like to know what services can be made.
3. As a customer who is curious, I would like to know how much everything would cost me & history of potential designs.
4. As an assured customer, I want to be able to make my enquiry easily.
5. As an enquired customer, I would like to be able to be in contact with the company.

### Competitor Scouting

[Liggy Cake Co.](https://www.liggyscakes.co.uk/): A giant number of options where they can order a specified cake while also being able to book a consultation.

[The Enchanting Cake Company](https://www.theenchantingcakecompany.co.uk/): Bespoke only, booking deposit and a lot of information to explain their process.

[The Cake Architect](https://thecakearchitect.co.uk/): Bespoke only, has price ranges with visuals of what type of cake you will get for that price.

### Business Goals

* Make a positive and inviting feeling from the branding of the website.
  * Branding to be strong, playful, and obvious.
  * Branding to be consistent throughout the website.
  * Do not overwhelm the user.
  * Style/Design matches the branding of the company.
* Make the user feel at ease.
  * Use of you everywhere to make user's feel more welcome.
  * Offer a lot of options to get in contact with company.
  * Be upfront about everything.
* Be as transparent as possible with pricing.
  * The user has all the power on the price.
  * Offer free Enquiries.
  * Explain all potential pricing.

## Scope

### Requirements

**Interaction** 

* Each page should contain some way to interact with the site.
* Interaction is done through Navigation and Enquire Form.
* All forms of interaction should be clear.

**Convey Purpose**

* Explain key purpose of website in the landing page.
* Go further in detail on separate page.
* Descriptions are easy to understand and concise.
* All information is important and has a reason to be there.

**Ease Of Access**

* Everything on the page is minimalistic as possible and friendly to the customer.
* Branding is clear from the landing page and throughout.
* Provide numerous ways to get in contact with the business.

**Cost Approach**

* Transparent about the cost of designs(£14.99) before enquiring.
* Push the free aspect of enquiring.
* Table of content to explain base cost ideas.

## Structure

### Home Page

* User Goal
  * Allows easy navigation around site.
   * Explains the Companies purpose.
   * Easy to read.

* Business Goal
   * Showcases the Companies branding and purpose.
   * Interest and engage the user.
   * Don't overwhelm the user.

### About-Us Page

* User Goal
   * Understand more about the company.
   * Understand more about the pricing of the cakes.
   * Understand how the process works.

* Business Goal
   * Provide clarity with the user.
   * Sell the brand and process.
   * Reasure the user on everything.


### Gallery Page

* User Goal
   * See examples of cakes that the company has done. 

* Business Goal
   * Showcase a variety of cake styles from tiers, designs, shapes and more.

### Enquire Page

* User Goal
   * To make a free enquiry to the company.
   * Simple to use.
   * Forms a communication between user and company.

* Business Goal
   * Obtain information about the user.
   * Start engagement with the user.

### Enquire-Confirmation Page

* User Goal
   * Learn more about what's next.
   * Have ways to contact about enquiry.

* Business Goal
   * Further engagement with the company.
   * Reassure about the enquiry.
   * Promote a paid service to the user.

## Skeleton

### Wireframes

* [Home Wireframe](./assets/images/home-wireframe.jpg)
* [About Us Wireframe](./assets/images/about-us-wireframe.jpg)
* [Gallery Wireframe](./assets/images/gallery-wireframe.jpg)
* [Enquiry Form Wireframe](./assets/images/enquire-form-wireframe.jpg)
* [Enquiry Confirmation Wireframe](./assets/images/enquire-comfirmation-wireframe.jpg)

## Surface

The project's style matches the company's branding, playful, colourful and helpful.

### Colour Scheme

I used Contrast Ratio to test the accessibility of my [colours](https://contrast-ratio.com/#%23000000-on-%23EFBDEB) for the text and background colour if image failed to load and these [colours](https://contrast-ratio.com/#%2363185C-on-%23effded) for the heading and enquire button text and background colour. For the backgrounds I chose #EFBDEB and #EFFDED as both are extremely bright and playful which I want anyone who uses the site to get instantly, I used the text colour of #63185C as I didn't want something boring for the header however, I couldn't have it be too colourful to the point it wouldn't be readable.

I also used an image as my background with multiple colours, to allow accessibility I added a background of rgba(255, 255, 255, 0.7); with a text colour of #000000, No matter what colour of text I used be it black, white or pink it would all be un-accessible due to the multitude of colours in all of the potential background images I had, I was originally planning to put the text blocks into boxes like the enquire button however my Mentor guided in the direction of using a background lacking opacity to fix the accessibility.

### Font

[Caveat](https://fonts.google.com/specimen/Caveat?query=caveat) was my chosen font for the Navigation, subhead, enquire button and price. While browsing for a font which completely encompassed my company's style branding, I came across Caveat over a single glance was instantly recognisable to the eye. The font style is both playful and eye catching while not being too hard to read. I originally had this font for the whole website however I decided it would be for helpful to have a softer and less playful style for the text outside of the navigation and sub-head.

[Raleway](https://fonts.google.com/specimen/Raleway?query=rale) was the font I used for text, contact and lists. After realising my text was blending in due to how playful Caveat was all over the page, I decided to find a new font to go well with it, I found Raleway and Montserrat but ended going on with Raleway as it felt softer and balanced out well with Caveat.


### Images

All images were sourced from [Unsplash](https://unsplash.com/). The image chosen for the background was chosen as it showed off the beauty and style of our company through the cake. All other images in the gallery were chosen as they showcased a wide variety of styles to show the customers that any cake, they can dream of can be made for them. All images contained a cake and showed off a wide range of colours.

# Features

## Navigation Bar

Each page has a fixed navigation bar in the header. **This will allow the new users a grasp off what's to come in the site as well as quick access for returning users.** As the header is fixed, the navigation bar as well as title will follow the users scrolling. The navigation bar will also always have a bar underneath to indicate what page of the site the user is on and will flash with a bar when a different navigation is hover over.

## Enquire Form

To get to the enquire form users will be able to click on the navigation bar which is always in front of them due to it be fixed or at the bottom of every page except the enquire and enquire-confirmation page will be a enquire box link to send the user to the enquire page.

**The enquire form will allow users to enter their personal details such as name(required), email(required) and phone number(not required) as well as information about their dream cake(required)**, this will form a connection between the company and the user to start the promised service. This form after everything required is filled out can be submitted and will lead to our enquire-confirmation page.

Originally, I had decided to have all forms be required however I decided to only go with email as I was worried this could deter any users who felt like we were trying to a lot of the user's personal information.

## Footer

Each footer Will contain social media(Twitter, Instagram, Facebook and TikTok) and our business email. **This is so that customers have numerous options to be able to get in touch with us be for problems with our service or just to ask questions.**

## Responsive Layout

With the use of flexbox and media queries, **the site's design is responsive too all screen sizes.** Breakpoints have been implemented to vary sizes and positions of content so that they fit more in line with the new extra space allotted with the new size.

When trying to make the images in the gallery responsive I came upon a problem with flex box where due to the number of images the last image would stretch up to 3 images wide causing a drastic drop in quality, as such I implemented a flex grow of 0 which while make the quality of all images be much better.

# Future Features

## Live Service

A user may prefer to have a back-and-forth conversation about their enquiry, as such implementing a live chat service which can answer FAQ through a chat bot when the user asks common questions and then directing the user to an administrator at Customer Cakery for further questions which the chat bot cannot answer. This would make the enquiry process quicker and more communicative, however would require a larger team as people would be needed to respond quickly to live service. This could be added inside a of the footer of each page and an option to replace/quicken the enquiry process.

## Pricing Gallery

A user might want an to know the price of cakes based of the gallery, as such when we have enough customers, we can implement a pricing gallery where using our cakes we can showcase the cost of cakes we have made. This would give the user more of an idea on how much our cakes cost, as well as showcase our designs and why they would want to use us.

# Technology Used

* The project was written and tested on [Gitpod](https://gitpod.io/).
* The project was also debugged and tested using [Chrome DevTool](https://developer.chrome.com/docs/devtools/).
* The project uses [GitHub](https://github.com/) for hosting and deploying the code onto GitHub Pages.
* The project template used was sourced from [Code Institute's Gitpod Template](https://github.com/Code-Institute-Org/gitpod-full-template)
* The project uses [FontAwesome](https://fontawesome.com/) for the free icons used.
* The project uses [Google Fonts](https://fonts.google.com/) for the fonts used.
* The project's wireframes were mocked up in [Balsamiq](https://balsamiq.com/wireframes/).
* The images used in the project's README were hosted and served through [Imgur](https://imgur.com/).
* The project's HTML was validated using [W3 Markup Validation](https://validator.w3.org/).
* The project's CSS was validated using [W3 Jigsaw](https://jigsaw.w3.org/css-validator/).
* The project uses images from [Unsplash](https://unsplash.com/).
* The project colour contrast ratio was determined by [Contrast-Ratio](https://contrast-ratio.com/).
* The project's images were compressed by [Tinypng](https://tinyjpg.com/).

# Testing

## Browser Testing

### Chrome/Firefox/Edge

All pages worked as intended.

### Safari

I do not have access to any device to test browser view on safari, and unfortunately do not know anyone who would be able to test for me.

### Internet Explorer 

I believe the flexbox in my footer causes it to no longer stick to the bottom of the page as is intended, this is due to how outdated internet explorer is and how flexbox does not work well on the browser.

I've tested ways to change it but outside of making the footer overall very messy and less dynamic it would be best to just ignore the internet explorer problem as it is outdated.

### Safari/Chrome(Tablet)

All pages worked as intended.

### Safari/Chrome(iPhone)

Header will not correctly cover both heading title and navigation for some reason, currently looking into a fix for this.

## Automated Testing

Automated testing was completed via third party applications, in order to assess and validate the project.

1. [W3 Markup Validation](https://validator.w3.org/nu/?doc=https%3A%2F%2Fzackocall.github.io%2Fcustomer-cakery%2F)
   * The project's HTML was validated using W3 Markup Validator.
   * No errors were found.

2. [W3 Jigsaw](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fzackocall.github.io%2Fcustomer-cakery%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
   * The project's CSS was validated using W3 Jigsaw Validator.
   * No errors were found.
   * The project validates as CSS level 3 + SVG.

3. [Lighthouse](https://developers.google.com/web/tools/lighthouse)
   Accessibility, Performance, Progressive Web Apps, and Best Practices Audit:
    
   **Index**

   ![Index Lighthouse Score](https://i.imgur.com/QfbDrw5.png)

   **About-Us**

   ![About-Us Lighthouse Score](https://i.imgur.com/GCFXrpu.png)

   **Gallery**

   ![Gallery 1030px Lighthouse Score](https://i.imgur.com/6frR7Js.png)

   ![Gallery 500px Lighthouse Score](https://i.imgur.com/zkxVYCJ.png)

   1030px Height caused best practice to reach 100 but lowered the performance, while 500px did the opposite with raising performance but lowering best practice. In the end I chose to go with 500px as I preferred having 1 column for phone view, 2 columns for tablet view and 3-4 column for browser view rather than 1 column for phone/tablet view and 2 columns for browser view which would happen with 1030px.

   **Enquire**

   ![Enquire Lighthouse Score](https://i.imgur.com/O3mu6zX.png)

   **Enquire-Confirmation**

   ![Enquire-Confirmation Lighthouse Score](https://i.imgur.com/HHlJbhy.png)

## Manual Testing

## User Stories

### As a first-time visitor to the website, I want to know what the company does from the home page.

**On entering the website, the user will land on the "home" page, the user is greeted with the company logo, navigation, a explanation of the companies purpose, a call to action and ways to get in contact with the company.**
* The Branding in the home page is consistent with the rest of the site and showcases the companies branding.
* Both the navigation and the call to action works as intended.
* All information is simple and easy to process to make users feel more at ease and welcome to the site.
* All content is responsive on all devices.
### As a potential customer, I would like to know what services can be made.

**In the navigation bar of all pages the user can navigate to the "About-Us" page.**
* The page contains an explanation on what our service is and how the service is used.
### As a customer who is curious, I would like to know how much everything would cost me & history of potential designs.

**In the "About-Us" page will be a pricing breakdown, while designs of the cakes will be shown in the "Gallery" page. Both can be navigated to from all pages.**
* The about-us page contains information on how we start pricing the cakes.
* It will also contain information on how shipping works price wise.
* The gallery page will contain multiple images of different designs made by the cake decorators at Customer Cakery.
* These designs will showcase a wide variety of different options to entice the user.
### As an assured customer, I want to be able to make my enquiry easily.

**All pages will contain a working call to action to a simple form for easy enquiries.**
* All pages will have an enquiry call to action at the bottom as well as in the navigation for ease of access.
* The form will be simple and have 4 required sections to fill out before enquiry.
### As an enquired customer, I would like to be able to be in contact with the company.

**After enquiry all users will be greeted and reassured that a quote will be with them within 48 hours, they will also be reassured to get in contact using social media or our business email for any questions.**
* All pages will have social media and our business email in the footer so users can get in contact us before and after enquiry.
* They will also be encouraged to get in contact if they are worried after enquiring.

### Features

## Text

During testing my mentor pointed out that my overall text was too large and made the site look unprofessional. As such I decided to lower the font size for my text all over my content at all different media queries to create a more stylish look.
 
## Navigation Bar

* All navigation bar links are working correctly from every page.
* The navigation bar text to exceed the background in any view.
* The active page is always displayed correctly.
* The active page line does not exceed the back in any view.
* The navigation bar wraps when it can no longer fit in one line.
* Navigation bar works as intended on both tablet and phone.

## Enquire Form

* Enquire will not be submitted unless email, name and description are entered on all devices.
* Enquire inputs are correctly structured.
* Labels are above the correct input.
* Size is consistent for inputs.
* Size is increased for text field to suggest for more information to be added.
* Email input only accepts valid email address.
* If not filled out correctly a notification will show to explain why.
* Form is responsive to different views.

## Footer

* All social medias are linked correctly on all pages.
* All social medias work as intended on all devices.
* Social media is responsive to different views.
* Social media style is consistent throughout the site.
* Business email is accurate across all pages.

## Responsive Layout

* The title in the header changes size according to media queries.
* The navigation bar both changes size and wraps to two lines when no room to fit on one.
* All text on every page wrap and change size as is intended.
* All enquire buttons change in size according to media query.
* Table inside "About-Us" is responsive, text does not overflow, wraps and changes in size according to different views.
* Images inside the gallery up in column amount when there is enough room and do not grow as to keep quality of image intact on all devices.
* Form in "Enquire" page is fixed according to size on phone and tablet view according to media queries but stretches when above tablet view.
* Social medias in footer stack in 2 columns rather than inline when tablet media query is hit.

## Bugs

1. **Gallery Image responsive and clarity for different views.**
   * While adjusting the gallery for different views I found that after reaching 3 columns it would force the 10th image on it's on and 9/10th at 4 columns, these would be stretched, making them hard to see and just overall unpleasant.
   * I implemented a set width for all pictures and flex grow 0 to fight this. This made the images much clearer to see and still was responsive as they continued to change columns based on the size of screen.

2. **Fixed header background**
   * I originally had changed my header background to be fixed as I wanted it to always be on the screen as users scrolled through the pages, however having this fixed caused my navigation bar to not accurately be behind the header background when viewed on phone view, as the fixed would not responsively adjust to the navigation bar taking up 2 lines and only cover the 1st line of navigation.
   * To fix this I reverted to a relative position which completely fixed the issue on phone viewing.

3. **Form**
   * My form was just submitting without any content being added to it for some reason.
   * I had separate  forms for all inputs/text area/button as such this was corrected after placing all inputs/text area/button within 1 form.

4. **Internet Explorer(Existing)**
   * In Internet Explorer my footer does not stick to the bottom of the page and instead lands just underneath my header. This overlaps the subtitle and content.
   * After looking for a solution for a while I found out from googling that this is a common problem with Internet Explorer and using Flexbox. Internet Explorer does not correctly support flexbox and as such my footer does not take its position at the bottom as flexbox intended.
   * This has and will stay an issue as to get rid of this I would have to not use flexbox to structure my content.

# Credits

### Content

* All text used throughout the site was written by me.
* Business ideas, goals, concept were all thought of by me.
 
### Images

* All icons provided by Font Awesome [Link](https://fontawesome.com/).
* All photographs provided by Unsplash [Link](https://unsplash.com/).
   * background.jpg by Jason Leung [Link](https://unsplash.com/@ninjason)
   * purple-cake.jpg by Christina Victoria Craft [Link](https://unsplash.com/@victoriabcphotographer)
   * black-cake.jpg by Jacqueline A Hernandez [Link](https://unsplash.com/@jacquelinegalindo)
   * white-decorated-cake.jpg by Scott Osborn [Link](https://unsplash.com/@scottosbornphoto)
   * wood-cake.jpg by Junior REIS [Link](https://unsplash.com/@juniorreisfoto)
   * autumn-cake.jpg by Kiefer Likens [Link](https://unsplash.com/@kiefer)
   * cream-cake.jpg by Deva Williamson [Link](https://unsplash.com/@biglaughkitchen)
   * 6-tier-cake.jpg by Jonathan Borba [Link](https://unsplash.com/@jonathanborba)
   * 3-tier-cake.jpg by Sirio [Link](https://unsplash.com/@sirioberati)
   * 4-tier-cake.jpg by Igor Rodrigues [Link](https://unsplash.com/@igorrodrigues)
   * music-cake.jpg by David Holifield [Link](https://unsplash.com/@davidholifield)

### Code

* Code for flex used from [Link](https://philipwalton.github.io/solved-by-flexbox/demos/sticky-footer/)
* Helped me better understand flex for image flex's [Link](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
* Helped me better understand table CSS [Link](https://www.w3schools.com/css/css_table.asp)

# Acknowledgements

* The concept of my 1st project was devised by myself getting more into baking over the past 6 months through my own baking as well as watching YouTube videos.
* Thank you to my mentor, [Ben Kavanagh](https://github.com/BAK2K3) for his immense support over our mentoring sessions, providing me with a streamline of how to go forward into the project and a clear outline on how to structure my 1st ever README.md
* Thank you to [Suzy Bennet](https://github.com/suzybee1987), the MS1 Channel Lead for slack, for a great 1st look into MS1 project 1 prep and giving me a good idea of what to lookout for during the project. And for introducing me to the concept of flexbox.

# Disclaimer

This website is for educational purposes only.