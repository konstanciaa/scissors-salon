# Scissors
[View the live project here.](https://konstanciaa.github.io/scissors-salon/)

The Scissors website is made for a beauty salon called "Scissors". This website gives all the information about a beauty salon and its services.  Potential clients can book an appointmnet online using a form on the "Booking" page of the website. 

The website is designed to be responsible on a range of devices. 

![A screenshot of the website on different devices](/docs/responsive.png)

## Table of Contents

- [Scissors](#scissors)
  * [User Experience (UX)](#user-experience--ux-)
    + [User stories](#user-stories)
  * [Features](#features)
    + [Navigation](#navigation)
    + [The Hero Image Section](#the-hero-image-section)
    + [The Gallery Section](#the-gallery-section)
    + [The Offer Section](#the-offer-section)
    + [The Contact Information Section](#the-contact-information-section)
    + [The Footer](#the-footer)
    + [The Services Page](#the-services-page)
    + [The Booking Page](#the-booking-page)
  * [Future Features](#future-features)
  * [Testing](#testing)
  * [Bugs](#bugs)
      - [Solved bugs](#solved-bugs)
  * [Validator Testing](#validator-testing)
      - [HTML](#html)
      - [CSS](#css)
      - [Accessibilty](#accessibilty)
      - [Unfixed Bugs](#unfixed-bugs)
  * [Testing User Stories from User Experience (UX) Section](#testing-user-stories-from-user-experience--ux--section)
  * [Deployment](#deployment)
  * [Contributing](#contributing)
  * [Technologies Used](#technologies-used)
      - [Languages Used](#languages-used)
      - [Programs Used](#programs-used)
  * [Credits](#credits)
      - [Code](#code)
      - [Content](#content)
      - [Media](#media)
      - [Acknowledgements](#acknowledgements)



## User Experience (UX)

### User stories
+ **First Time Visitor Goals**

    a. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the beauty salon.
    
    b. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.

    c. As a First Time Visitor, I want to look for photos of their work to understand what result to expect from their services. 

    d. As a First Time Visitor, I also want to locate their social media links to see their followings on social media to determine how trusted and known they are.

+ **Returning Visitor Goals**

    a. As a Returning Visitor, I want to find information about special offers and discounts.

    b.  As a Returning Visitor, I want to find the best way to get in contact with the salon with any questions I may have.

    c. As a Returning Visitor, I want to be able to book an appointmnet.

+ **Frequent User Goals**

    a. As a frequent User, I want to check to see if there are any newly added photos in the gallery section.

    b. As a frequent User, I want to check to see if there are any new services or offers.

## Features

### Navigation
+ The navigation is located at the top of the page. It shows the beauty salon name in the left corner: SCISSORS that links to home page.
+ The navigation is in an appealing bright color that contrasts with the background and clearly shows the name of the salon.
+ The other navigation links are to the right: Home, Services, Booking which link to different pages of the website. 
+ The color change of the navigation links tells on which page of the website the users are.

![A screenshot of navigation section](/docs/navigation.png)

### The Hero Image Section
+ The hero image shows the beauty salon interior, using a photo. It helps potential clients to understand what to expect when they decide to visit the salon.
+ The image also contains welcoming words which can make potential clients to feel welcomed.
+ The heading with the welcoming words was designed to partly cover the salon interior image with the goal to prevent users from focusing on less important details on the image rather than on the website's content which calls them to action.

![A screenshot of the beauty salon interior image](/docs/interior-image.png)

### The Gallery Section
+ This section contains short information about the kind of services the salon provides and the first call to action. 
+ The bright color button below with the words "Get your hair done" opens the "Booking" page with a form which gives the opportunity to book an appointment.
+ The Gallery section shows six pictures which give a clear idea about the result potential clients may achieve after visiting the salon.

![A screenshot of the gallery section](/docs/gallery.png)

### The Offer Section
+ The Offer section tells users about a discount and encourages them to book an appointment.
+ This section also contains a button which opens the "Booking" page with a form that gives the opportunity to book an appointment.

![A screenshot of the offer section](/docs/offer.png)

### The Contact Information Section
+ The contact information section provides users with the inforamtion about opening hours, phone number and the address.
+ This section is valuable to the user as it gives them the ability to find and contact the Scissors beauty salon if they want to.

![A screenshot of the contact information section](/docs/contact.png)

### The Footer
+ The footer contains social media icons with active links to the Scissors social networks profiles.
+ The social media links open a new tab. It gives users the opportunity to get more information about the salon without closing its website.

![A screenshot of the footer](/docs/footer.png)

### The Services Page
+ The Services page contains a list of the services the Scissors salon provides along with the prices.
+ The reminder about the discount and the button "Book an appointment" below the pricelist encourage users to make a decision to book an appointment.
+ The button "Book an appointment" when clicked opens the "Booking" page which contains a form for booking.

![A screenshot of the services page](/docs/services.png)

### The Booking Page
+ The Booking page contains a form which enables users to leave their request for an appointment.
+ The form contains three radio buttons which help a potential client to choose a kind of service or to write their option.
+ The textarea in the form provides users with an opportunity to express their needs in a more detailed way.

![A screenshot of the booking page](/docs/booking.png)

## Future Features

+ New Gallery page will be added to provided users with more photos.
+ The Service page will be enriched with pictures and descriptions of some services.
+ The Booking page will contain a calendar which enables potential clients to choose the date and time convinient for them.
+ New Blog page will be created to post articles about haircare and hairstyle trends.

## Testing

| **To test**                         | **Expected Result**                    |
|-------------------------------------|----------------------------------------|
|Open the site in different browsers. |The website works properly in different browsers: Chrome, Safari.
|Open it on a tablet and a mobile phone. |It's responsive and looks good on a range of devices.             
|Tap the navigation to open another pages. |I confirmed that all three pages are easily open through the navigation bar.
|Click the button "Get your hair done". |It opens the Booking page with a form for booking.
|Click the button "Book an appointment" on the home page. |It opens the Booking page with a form for booking.
|Click social media icons at the bottom of the page. |Each link is being opened in a new tab.
|Enter your name, last name and phone number in a booking form. |The entered info is clear and readable.
|Try to submit the form without filling out one of the fields. |The form requires all the fields to be filled out before submiting.
|Type some text into the textarea. |The text is clearly seen.           


## Bugs

#### Solved bugs

+ When I typed a name in the form input field, it was not shown. 
+ I realized that it was because of my mistake in a css rule. Both the color of the input field and of the text were set to white. 
+ As soons as I changed the color of the text to more contrasting dark color, the issue was solved. 

## Validator Testing

#### HTML
+ No errors were returned when passing through the official W3C validator.

<a href="https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Fkonstanciaa.github.io%2Fscissors-salon%2Findex.html" target="_blank">W3C Markup Validator - Results</a>

#### CSS
+ No errors were returned when passing through the official (Jigsaw) validator.

<a href="https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fkonstanciaa.github.io%2Fscissors-salon%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en" target="_blank">W3C CSS Validator - Results</a>

#### Accessibilty
+ I confirmed that the colors and fonts chosen are easy to read and accessible by running it through lighthouse in devtools.

![A screenshot of the lighthouse test result](/docs/lighthouse.png)

#### Unfixed Bugs
+ No unfixed bugs

## Testing User Stories from User Experience (UX) Section

+ **First Time Visitor Goals**

    i. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the beauty salon.

    *a. Upon entering the site, users are automatically greeted with a clean and easily readable navigation bar to go to the page of their choice. Underneath there is a Hero Image with Welcoming text* 

    *b. Below the Hero Image users can find information about the kind of services the salon provides and the first call to action.*

    *c. The user is able to immediately book an appointment*

    ii. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.

    *a. The site has been designed to be fluid and never to entrap the user. At the top of each page there is a clean navigation bar, each link describes what the page they will end up at clearly.*

    *b. At the bottom of the first two pages there is a button with a call to action to ensure the user always has aomewhere to go and doesn't feel trapped as they get to the bottom of the page.*

    *c. On the third page there is a booking form which is easy to fill out.*

    iii. As a First Time Visitor, I want to look for photos of their work to understand what result to expect from their services.

    *In the middle of the first page between two buttons which call to action, the user can take a look at the gallery of photos.*

    iv. As a First Time Visitor, I also want to locate their social media links to see their followings on social media to determine how trusted and known they are.

    *At the bottom of all three pages users can easily find social media icons. They open the salon social media profiles in a new tab and give the opportunity to investigate more about the quality of service the salon provides.*

+ **Returning Visitor Goals**

    i. As a Returning Visitor, I want to find information about special offers and discounts.

    *The information about special offers and discounts can be easily found on the home page just below the gallery and on the Services page just below the pricelist.*

    ii. As a Returning Visitor, I want to find the best way to get in contact with the salon with any questions I may have.

    *Scrolling the home page further, the user can locate all the necessary contact information: open hours, phone number and the address.*

    iii. As a Returning Visitor, I want to be able to book an appointment.

    *As entering the site users get two options to book an appointment. The first option is to navigate to Booking page which contains a booking form. The second option is to click the button just below the hero imag eand welcoming words.*

+ **Frequent User Goals**

    i. As a frequent User, I want to check to see if there are any newly added photos in the gallery section.

    *The user can easily locate the gallery with new photos on the home page. It is placed between the first button calling to action and the speciiel offer.*

    ii. As a frequent User, I want to check to see if there are any new services or offers.

    *a. The information about new services can be found on the Services page. The user can open it by navigating at the top of the page.*

    *b. The information about the new offers is located on the home page underneath the gallery with photos.*


## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows:
+ In the GitHub repository, navigate to the Settings tab
+ Choose Pages on the left side menu
+ From the source section drop-down menu, select the Main Branch
+ Once the main branch has been selected, the page will automatically refresh
+ Click the provided link to now published website.

The live link can be found here - [SCISSORS](https://konstanciaa.github.io/scissors-salon/)

## Contributing

Any contributions are greatly appreciated. If you have a suggestion that would make this website better, please fork the repo and create a pull request.

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/konstanciaa/scissors-salon)
2. At the top of the Repository on the right site of the page just above the "Setings" Button on the menu, locate the "Fork" Button.
3. Fork the Project
4. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
5. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
6. Push to the Branch (`git push origin feature/AmazingFeature`)
7. Open a Pull Request

## Technologies Used

#### Languages Used
+ HTML5
+ CSS3

#### Programs Used
+ **Google Fonts** were used to import the 'Oswald' and 'Source Serif Pro' fonts into the style.css file which are used on all pages throughout the project.
+ **Font Awesome** was used to represent links to social media in the footer of the website throughout all the pages.
+ **Git** was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
+ **GitHub** is used to store the projects code after being pushed from Git.
+ **Canva** is used to resize and edit pictures.

## Credits

#### Code
+ The full-screen hero image, logo and navigation code came from [Love Running project](https://github.com/konstanciaa/love-running)
+ The footer code came from this [YouTube tutorial](https://youtube.com/shorts/kNGYuTelE3E?feature=share)

#### Content
+ All the website content was written by the developer.
+ Readme file templates from [GitHub](https://github.com/othneildrew/Best-README-Template) and [Code Institute](https://codeinstitute.net/) were used to help to create this README file.

#### Media
The images were taken from [Pexels](https://www.pexels.com/) and [Pixabay](https://pixabay.com/) 

#### Acknowledgements
+ My Mentor for continuous helpful feedback.
+ Tutor support at Code Institute for their support.