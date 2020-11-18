# The Drum School

Live Page: [The Drum School](https://oisintohak.github.io/Milestone-Project-1/)

This website was built to allow potential students to find information about The Drum School and to book lessons.

---
## User Stories:
- I need to view the page on a mobile device.
- I'm looking for contact info or social media links.
- I want to book a series/course of lessons as a gift.
- I want to read some reviews from past students.
- I want to watch a video demonstration of an example lesson.
- I want to know the price of lessons.
---
## Five Planes:

#### - Strategy (What this website aims to achieve, and for whom?)
The website aims to present essential information that the user stories request in a way that is visually appealing, professional and accessible. The main purpose of the website is to gain new students by motivating them to fill out the contact form.



#### - Scope (Which features, based on information from the strategy plane, do you want to include in your design?)
The website should be clearly laid out with user friendly navigation to make the site easy to use and accesible. The colors, typography and styling should give the user an impression of professionalism. The user should be able to easily access links to social media, a phone number and a user-friendly contact form. There should be a page or section with pictures of the teaching environment and possibly video content of a performance or demo lesson.



#### - Structure (How is the information structured and how is it logically grouped?)
Pages: Home, lessons, gallery, contact

- The first view of the home page will be simple in structure with a short text intro and a call to action button.
Below it will be some further introductory information about the drum school, lesson types and some student testimonials. The footer will contain contact details, an address and social media links.
- The lessons page will contain detailed information on each lesson type and prices for lessons. There will be a student testimonial slider to give potential customers added reassurance of the quality of the lessons.
- The gallery page will feature a set of pictures to show users what the lesson environment is like and what to expect.
- The booking/contact page will feature a simple contact form in one section and a map with contact details in another.

#### - Skeleton (How will our information be represented, and how will the user navigate to the information and the features?)
###### Wireframes:
- [Desktop_Home_page](wireframes/HOME_DESKTOP.PNG)
- [Mobile_Home_Page](wireframes/HOME_MOBILE.PNG)
- [Desktop_Lessons_Page](wireframes/LESSONS_DESKTOP.PNG)
- [Mobile_Lessons_Page](wireframes/LESSONS_MOBILE.PNG)
- [Desktop_Gallery_Page](wireframes/GALLERY_DESKTOP.PNG)
- [Mobile_Gallery_Page](wireframes/GALLERY_MOBILE.PNG)
- [Desktop_Contact_Page](wireframes/CONTACT_BOOK_DESKTOP.PNG)
- [Mobile_Contact_Page](wireframes/CONTACT_BOOK_MOBILE.PNG)

#### - Surface (What will the finished product look like? - What colors, typography, and design elements will we use?)
I have chosen to use a full-screen background image of a drumkit with sticks for the home page. I have taken the color profile of this image as inspiration for the color scheme for the rest of the website to give some consitency to the colors.

---
## Technologies used:
- HTML 5
- CSS 3
- [Bootstrap 4.5](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
- [FontAwesome](https://fontawesome.com/) for icons.
- [Google Fonts](https://fonts.google.com/) : I used two fonts for this project, [Righteous](https://fonts.google.com/specimen/Righteous?query=righ) and [Lato](https://fonts.google.com/specimen/Lato?query=lato).
- [Fancybox](https://fancyapps.com/fancybox/3/) : this is a JavaScript lightbox library for presenting various types of media. I used it for the gallery page.
- [Autoprefixer](https://autoprefixer.github.io/) : this was used to automatically add CSS prefixes to support multiple browsers.
- [GitHub Pages](https://pages.github.com/) was used for deployment.

---
## Features:

 - The first view of the home page is always be the same height as the viewport, to give a landing page effect and to focus attention on the call to action button.
 - There is a more info button on the first view of the home page to indicate the presence of additional content.


---
## Implementation and Process:
I began with some initial UX planning and basic wireframes. I then started coding with a navbar and a background image for the home page. I added a banner link to the center of the home page. I separated the body into two sections, the content before the footer and the footer, then separated them using flexbox to ensure that the footer will always remain at the bottom of the screen even on larger displays.

 After the initial planning session with my mentor I needed to change the layout from the initial wireframes:
- Change the banner text on home page to not be a link (you don't want to redirect users who've just arrive on your page)
- Add a call to action/book now button below the banner text on the home page
- Add some introductory text on the home page below the call to action button
- Below it, add lesson cards with a brief description of each lesson type
- Add another call to action below these cards
- Add contact and social links to the footer
- The lessons page should be divided into separate cards for each lesson type, with detailed information for each
- Use fancybox.js for the gallery

After my mid-project session with my mentor I had the following changes left to implement:
- Space the address over 2 lines in footer
- Add vertical space around the intro text above the lesson cards on the home page, with a headng above the cards and push the 'find out more' buttons to the bottom of the lesson cards
- Add a testimonial slider with a header below the lesson cards on the home page
- Add call to action text to book now button above footer
- Move the email and phone beside the home address in the footer and increase the size of the social links
- Only use the background image for the first view of the home page
- On lessons page, use large horizontal cards with image on left
- On book now page make address text responsive and move map down in card

After my end-of-project mentor session I had the following changes to implement:
- The order in the footer from left to right should be contacts(address, email, tel), logo, social links.
- The copyright info should be a normal size and placed under the logo in the footer
- Change form heading to let users know why they are leaving their details
- On mobile, move social icons down on the contacts page and make the map larger

---
## Testing:
- [W3C HTML Validation Service](https://validator.w3.org/) was used to validate the HTML
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) was used to validate the CSS

---
## Deployment
The site was deployed to [GitHub Pages](https://pages.github.com/) using the following steps:
- Create a repository on GitHub and initialize it with a README.MD file
- The root of your repository must contain an index.html file which will be the main page of your live GitHub Page.
- Go to repository settings, scroll to GitHub Pages and select the master branch for your source.
- Save the selection and when the page reloads the link to your live site will be in the GitHub Pages section. The link can take up to 1 hour to go live.

To clone this repository run `git clone https://github.com/oisintohak/Milestone-Project-1.git` into a terminal with git installed.

---
## Credits
- #### Images
  - The Images on this website were taken from [Unsplash](https://unsplash.com/)
  - The icon used for the logo and favicon was taken from [Flaticon](https://www.flaticon.com/)
  - All other icons were taken from [FontAwesome](https://fontawesome.com/)

- #### Code
  - Styling for faded horizontal rule elements taken from [CSS Tricks](https://css-tricks.com/examples/hrs/)
  - Responsive map iframe code taken from [This blog](https://blog.duda.co/responsive-google-maps-for-your-website)
 