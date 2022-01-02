# Customer Cakery

This project is a static website for a Cake Baking company called Customer Cakery.

[View the website on github pages here](https://zackocall.github.io/customer-cakery/).

# Table of contents

>1. [Overview](#overview)
>2. [UX](#ux)
>    1. [Strategy](#strategy)
>    2. [Scope](#scope)
>    3. [Structure](#structure)
>    4. [Skeleton](#skeleton)
>    5. [Surface](#surface)
>3. [Features](#features) 
>4. [Testing](#testing)
>    1. [Browser Testing](#browser-testing)
>    2. [Automated Testing](#automated-testing)
>    3. [Bugs](#bugs)  
>5. [Credits](#credits)
>    1. [Content](#content)
>    2. [Images](#images)
>    3. [Code](#code)
>6. [Acknowledgements](#acknowledgements)
>7. [Disclaimer](#disclaimer)

## Overview

**Customer Cakery**

Customer Cakery is a Bespoke Cake baking and decorarting company. Customers can enquire for a price of their chosen dream cake for free, Customers can then choose to pay a invoice to also get 3 custome designs from qualified cake decorators for £14.99. After collecting all information we will send over the pricing and designs within 3 days and offer to make the designs for a set price over the email provided.

The project is devoloped using HTML and CSS.

# UX

## Strategy

### User Stories

1. As a first time visitor to the website, I want to know what the company does from the home page
2. As a pontential customer, I would like to know what services can be made.
3. As a customer who is curious, I would like to know how much everything would cost me & history of pontential designs.
4. As a assured customer, I want to be able to make my enquiry easily.
5. As a enquired customer, I would like to be able to be in contact with the company.

### Competitor Scouting

[Liggy Cake Co.](https://www.liggyscakes.co.uk/): A giant number of options where they can order a specified cake while also being able to book a consultation.

[The Enchanting Cake Company](https://www.theenchantingcakecompany.co.uk/): Bespoke only, booking deposit and a lot of information to explain there process.

[The Cake Architect](https://thecakearchitect.co.uk/): Bespoke only, Has price ranges with with visuals of what type of cake you will get for that price.

### Business Goals

* Make a positive and inviting feeling from the branding of the website.
  * Branding to be strong, playful and obvious.
  * Branding to be consistent throughout the website.
  * Do not overwhelm the user.
  * Style/Deisng matches the brandning of the company.
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
* Go further in detail on seperate page.
* Descriptions are easy to understand and concise.
* All information is important and has a reason to be there.

**Ease Of Access**

* Everything on the page is minimilistic as possible and friendly to the customer.
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
   * Reasure about the enquiry.
   * Promote a payed service to the user.

## Skeleton

### Wireframes

* [Home Wireframe](./assets/images/home-wireframe.jpg)
* [About Us Wireframe](./assets/images/about-us-wireframe.jpg)
* [Gallery Wireframe](./assets/images/gallery-wireframe.jpg)
* [Enquiry Form Wireframe](./assets/images/enquire-form-wireframe.jpg)
* [Enquiry Comfirmation Wireframe](./assets/images/enquire-comfirmation-wireframe.jpg)

## Surface

The project's style matches the company's branding, playful, colourful and helpful.

### Colour Scheme

I used Contrast Ratio to test the accessibility of my [colours](https://contrast-ratio.com/#%23000000-on-%23EFBDEB) for the text and background colour if image failed to load and these [colours](https://contrast-ratio.com/#%2363185C-on-%23effded) for the heading and enquire button text and background colour. For the backgrounds I chose #EFBDEB and #EFFDED as both are extremly bright and playful which I want anyone who uses the site to get instantly, I used the text colour of #63185C as I didn't want something boring for the header however I couldn't have it be too colourful to the point it wouldn't be readable.

I also used a image as my background with multiple colors, to allow accessibility I added a background of rgba(255, 255, 255, 0.7); with a text colour of #000000, No matter what colour of text I used be it black, white or pink it would all be un-accessable due to the multitude of colours in all of the potential background images I had, I was originally planning to put the text blocks into boxes like the enquire button however my Mentor guided in the direction of using a background lacking opacity to fix the accessability.

### Font

[Caveat](https://fonts.google.com/specimen/Caveat?query=caveat) was my chosen font for the Navigation, subhead, enquire button and price. While browsing for a font which completely encompassed my company's style branding, I came across Caveat over a single glance was instantly recognisable to the eye. The font style is both playful and eyecatching while not being too hard too read. I orginally had this font for the whole website however I decided it would be for helpful to have a softer and less playful style for the text outside of the navigation and sub-head.

[Raleway](https://fonts.google.com/specimen/Raleway?query=rale) was the font I used for text, contact and lists. After realising my text was blending in due to how playful Caveat was all over the page I decided to find a new font to go well with it, I found Raleway and Montserrat but ended going on with Raleway as it felt softer and balanced out well with Caveat.


### Images

All images were sourced from [Unsplash](https://unsplash.com/). The image chosen for the background was chosen as it showed off the beauty and style of our company through the cake. All other images in the gallery were chosen as they showcased a wide variety of styles to show the customers that any cake they can dream of can be made for them. All images contained a cake and showed off a wide range of colours.

# Features

## Navigation Bar

Each page has a fixed navigation bar in the header. **This will allow the new users a grasp off what's to come in the site as well as quick access for returning users.** As the header is fixed, the navigation bar as well as title will follow the users scrolling. The navigation bar will also have a bar underneath at all times to indicate what page of the site the user is on and will flash with a bar when a different navigation is hover over.

## Enquire Form

To get to the enquire form users will be able to click on the navigation bar which is always infront of them due to it be fixed or at the bottom of every page except the enquire and enquire-confirmation page will be a enquire box link to send the user to the enquire page.

**The enquire form will allow users to enter their personal details such as name(required), email(required) and phone number(not required) as well as information about their dream cake(required)**, this will form a connection between the company and the user to start the promised service. This form after everything required is filled out can be submitted and will lead to our enquire-confirmation page.

Orginally I had decided to have all forms be required however I decided to only go with email as I was worried this could deter any users who felt like we were trying to a lot of the users personal information.

## Footer

Each footer Will contain social media(Twitter, Instagram, Facebook and TikTok) and our business email. **This is so that customers have numerous options to be able to get in touch with us be for problems with our service or just to ask questions.**

## Responsive Layout

With the use of flexbox and media queries, **the site's design is responsive too all screen sizes.** Breakpoints have been implemented to vary sizes and positions of content so that they fit more in line with the new extra space alloted with the new size.

When trying to make the images in the gallery responsive I cam upon a problem with flex box where due to the number of images the last image would stretch up to 3 images wide causing a drastic drop in quality, as such I implemented a flex grow of 0 which while make the quality of all images be much better.

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

### Safari(IPhone)

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

   ![Gallery 500px Lightouse Score](https://i.imgur.com/zkxVYCJ.png)

   1030px Height caused best practice to reach 100 but lowered the performance, While 500px did the opposite with raising performance but lowering best practice. In the end I chose to go with 500px as I prefered having 1 column for phone view, 2 column for tablet view and 3-4 column for browser view rather then 1 column for phone/tablet view and 2 column for browser view which would happen with 1030px.

   **Enquire**

   ![Enquire Lighthouse Score](https://i.imgur.com/O3mu6zX.png)

   **Enquire-Confirmation**

   ![Enquire-Confirmation Lighthouse Score](https://i.imgur.com/HHlJbhy.png)


## Bugs

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

* The concept of my 1st project was devised by myself getting more into baking over the past 6 months through my own baking as well as watching youtube videos.
* Thank you to my mentor, [Ben Kavanagh](https://github.com/BAK2K3) for his immense support over our mentoring sessions, and providing me with a streamline of how to go forward into the project.
* Thank you to [Suzy Bennet](https://github.com/suzybee1987), the MS1 Channel Lead for slack, for a great 1st look into MS1 project 1 prep and giving me a good idea of what to lookout for during the project. And for introducing me to the concept of flexbox's.

# Disclaimer

This website is for educational purposes only.