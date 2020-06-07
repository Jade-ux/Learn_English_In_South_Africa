# Learn English in South Africa

[View my live site here.](https://jade-ux.github.io/Learn_English_In_South_Africa/)

## Purpose

The Learn English in South Africa website is a B2C commercial website owned by a study-tourism agency that provides a booking service for people who would like to complete an English-language course in South Africa.

The website allows users to browse options for courses, accommodation and experiences. The experiences are activities they can enjoy in South Africa.

My inspiration for this website has come from conversations I have had with people who have travelled to South Africa, from all over the world, to study English. However, the concept of offering the ability to book courses, accommodation and experiences in one place is my own idea.

One of my friends is a host and has been providing accommodation for students for many years. The students are from 16 years old and up and come from many different backgrounds.

The agency's USP is allowing prospective students to book their entire study-tourism experience in three easy steps - first they find the course they want to take, by browsing accredited courses offered on the website. Then they decide on their preferred accommodation type. The last step is to choose their experiences. 

Currently the site only allows users to book courses and browse the other options, and the agency would then get in touch with the user to take the next steps. However, in future developments I would like to add the ability for users to log in and add items to their 'shopping basket' and book for everything online.

**Business goals:** The agency recieves commission from bookings taken for courses, accommodation and activities. The agency’s goal is to become a popular information source for foreign students who want to complete a language course in South Africa, and to have prospective students book their entire package (courses, accommodation and experiences) through the agency. SEO will be very important in order to attract as many prospective students as possible.

**User goals:** Users would be looking for a trustworthy source of information about English courses, and would want to compare a number of courses based on price, suitability, length of time and rating. Users who are willing to travel abroad to learn English will want to ensure they have suitable accommodation booked before they depart and would like to plan a few activities in South Africa to make the most of their time in the country. The selling point for this website is that users can book all of these parts of their trip at the best prices (the agency will have negotiated bulk discounts), all in one place and as easily and quickly as possible.

**Competitor analysis:** Individual schools have their own websites but these do not offer a broad range of courses across different schools so users would need to visit many sites to compare courses and offers across schools.

## Core requirements

-	The website should allow users to translate the contents using their browser’s translator – therefore most content should be in the form of text and not text in images
-	Iconography should be used to help users navigate the site
-	Icons should be internationally recognized as associated with the content they are referring to
-	Images should illustrate the experience of studying in SA 
-	As this is a B2C site, users are likely to make decisions based largely on emotional responses. Therefore images and design should be welcoming and reassuring as well as compelling and, as much as possible, universally representative.
-	Must be optimised for search engines
-	Users would expect an intuitive journey and would want to find out information quickly therefore I have made the menu bold and clear.
-	Mobile design important as many users will be navigating on their phones

## UX

### User story 1

As a prospective student I want to find and book the best English language course to suit my needs, in a country where I can practice speaking English to locals every day, and book my accommodation and activities all with one agency. I do not yet know where I want to study. 

### User story 2

As a prospective student I know I want to study English in South Africa. I would like to find and compare courses before booking. 

### User story 3

As a prospective student I want to compare English language courses and book the best one for my needs. I would also like to book accommodation. I have reached the courses page of this site via a search engine (bypassing the home page). 

## Design

I created mockups before building the site. This helped me plan how to structure the content, the user journeys and the responsive design.

[See my wireframes here](assets/mockups-and-wireframes/milestone-project-1-wireframes.pdf)

After beginning the development of the website I changed a few of the design elements and features such as the banner. In the wireframes you will see the banner is a carousel image with a small text box over it. I learnt that carousels are not accessible and therefore changed the banner to a static image. I also realised the text over the banner would not work well on mobile devices and left that off the final design.

I created style mockups to test out colour combinations and styles for the site. 

[Home page mockup](assets/mockups-and-wireframes/styles-mockup--home-pg.jpg)

**Colours:** The accent colours I have used, the pink, green, yellow and blue, are colours taken from the houses shown in the banner image on the home page. I have used these colours because they are vibrant and high-energy colours and will appeal to adventurous, energetic people looking for new learning experiences. 
I added additional colours for roll-overs and active states which are much deeper and richer, which demonstrates the rich variety of experiences a student could expect in South Africa, and the country's rich cultural heritage.

**Navigation links:** These are large buttons for large and smaller screens. I chose to keep these as buttons on smaller screens because I think they help encourage the user to click through to other pages and easily see where they are. Howevre, for phones with a width smaller than 374px I have changed this to a burger menu as the buttons do not fit well on those screen sizes.

**Home button on navigation:** The logo at the top of the website and in the footer serve as the link to get back to the home page. However, when I tried to create the entire div as a link it broke the grid structure. Therefore I have created each individual element within the logo as a link. In future developments I plan to make the entire logo block a link in both the top and footer of the website.

**Buttons:** There are two styles of buttons on the site. The outline buttons are for people in the first phase of the buying cycle and are still only looking around at information. The solid colour buttons are for people in the next buying phase who are ready to book a course or contact the agency. The colours of the buttons or the colour of the hover effects are linked to the content for instance, all buttons to the courses page will be green or green on hover.

## URL naming

As SEO is an important consideration for this site, I have named URLs for SEO, therefore the 'Courses' page URL is 'english-courses'

## Issues/challenges

### Courses page

**Booking form:** The form includes a question 'Which course would you like to book' which I realise is not good user experience because the user would have already chosen their course and clicked the 'Book this course' button next to their chosen course.
However, as the development of a solution that would automatically add the course name to the form is beyond the scope of this milestone project, I have deferred the development of that feature to future releases.  

The form uses the 'Get' method instead of the 'Post' method because I wanted to send the user to a 'Thank you' page upon submission of the form. In future developments I would add a success message to the form using JavaScript.

### Accommodation page

I had originally added a carousel to the Accommodation page, to show a gallery of accommodation options. However, I know that carousel's are not accesible so in the end I decided to remove it.

I have not added a gallery of images in a different format to make up for it because I realised without the gallery the page was much more succint and would get users moving on to the next step quicker. I don't think the gallery added much to the user experience.

## Features

### Existing Features

- The 3 Easy Steps feature helps all users understand the process that they would go through with this agency to get everything booked. This section changes depending on the page and allows users to follow the steps.
- The accordions feature allows users to browse through content quickly, without having to process large amounts of text all at once.
- The booking form in a modal feature allows users who want to book a course, to book the course online.
- The contact form on the Enquire page allows users to either contact the agency to ask a general question, or book a course.

### Features Left to Implement

- **Forms success message:** I have added a new page for the form action, to display the 'Thank you for booking' or 'Thank you for contacting us' text but in the next release I would like to add that message to the page the user is on when they submit the form and connect the form up to a database. 
- **Forms automatically include course name:** On the courses page, I would like to have the form title automatically include the name of the course relating to the 'Book this course' button the user clicked.
- **Log in:** I would like to enable users to log in so that they can save their choices and add options to a 'Shopping basket' and then check out, paying for everything on the website.
- **Experience filter:** A feature that allows users to filter to only the experiences they are interested in.
- **Courses filter:** A feature allowing the user to filter courses based on certain criteria (price, city, level, length of time, ratings).

## Technologies Used

- HTML5: This site was written in HTML5
- CSS3: I styled the HTML using CSS3. My CSS class naming convention is based on the BEM method.
- [Bootstrap](https://getbootstrap.com/)
  - This project uses Bootstrap to speed up the development process. Some Bootstrap elements use Jquery, Popper.js and Javascript.

## Testing

### Testing user stories 

I tested each user story by clicking through each step to make sure I could find the information I would need if I were one of the users:

**Testing User Story 1:**

I land on the home page of this site, read through the 'Why study in South Africa?' section which convinces me that South Africa is a good place to study. Then I scroll to the 'Get started in 3 easy steps' section. 

Here I find how the process will work with this agency. 
 
(assets/user-stories/user-story1.jpg) 
1. I click the 'Find your course' button to browse courses available
2. On the Courses page I can quickly find the courses at my level and click to open the relevant accordion section. I find the course I like the sound of and click 'Book this course'.
3. I complete the form and hit 'send'
4. I am taken to the 'Thank you' page and from there either choose to leave the site or carry on browsing through to the accommodation page. 

**Testing User Story 2:**

(assets/user-stories/user-story2.jpg) 

1. From the home page I immediately click the 'Courses' navigational link.
2. On the courses page I glance over the accordion titles, finding the catagory of courses that I want and click to open that accordion. When I have found the course I want to book I click 'Book this course'
3. I complete the form and hit 'send'. 
4. I am taken to the 'Thank you' page and from there click the button to browse through the accommodation options. From there I decide which type of accommodation I would like to choose.

**Testing User Story 3:**

(assets/user-stories/user-story3.jpg)

1. I have landed on the Courses page from a search engine. I browse through the content in the accordions, finding the course I would like to apply for and click 'Book this course'. 
2. Having completed the form I am taken to the 'Thank you' page. I am interested in booking accommodation for my stay in South Africa and click the 'Browse accommodation' button.
3. On the Accommodation page I look through the types of accommodation and decide which I would prefer. Then, I scroll down to the '3 Easy steps' section and read about the process. I am interested in finding out more about the experiences and click the 'Choose your experiences' button.
4. I read through the experiences and decide which I would like to take part in. From there I leave the site as I will wait to hear from the agency by email.

**Colours:** I tested the colours I have used for navigation elements using the [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) to ensure accessibility of all colours. I realised that a few of the colours I was using for the roll-over effects were not accessible and I have therefore chosen darker colours to ensure accessibility to WCAG AA standards. This has worked well as I now have deeper and richer colours for roll-overs but brighter colours for highlights which hint at the rich variety of experiences people can expect when they visit South Africa.

**Forms:** I manually tested each of the forms on the website, making sure all required fields had to be completed before the form could be submitted and ensuring that the input validators are working. I also tested that when the form is submitted the user is notified that it has been submitted successfully - this notification comes in the form of a new page which says 'Thank you for ...'.

To manually test each form I followed these steps:

1. On each form I attempted to submit the form leaving all fields blank to ensure the error message sould show for all required fields. This showed that the required attribute was working on all required fields.
2. For fields where the input data needs to be verified, such as the email address, I entered data that did not meet the requirements, such as an email address without the '@' symbol. Then I tried to submit the form and the error message showed, alerting me to fix the data in that field.
3. I entered all fields with valid data and clicked the 'Send' button. I was taken to the 'Thank you' page which is as intended.

**Links:** The site was tested for broken links using the [Dead Link Checker](https://www.deadlinkchecker.com/website-dead-link-checker.asp) and no broken links were found.

I also manually tested that each link is going to the correct page by clicking each link.

**Validating CSS:** I tested my CSS code using the [Jigsaw validator](https://jigsaw.w3.org/css-validator/validator) and the result was that no errors were found.

**Validating markup:** My HTML was tested using the [W3C Markup Validation Service](https://validator.w3.org/). There were a few errors highlighted and I have fixed each one except for the following:
- Heading warning on banner images - recommended to add header to the banner section, however, I do not want text over the banner and my next heading is one section down so I have left this as it is for now.

There were a few interesting bugs on the forms:
- An error on the label for the checkboxes group - therefore I have added a legend instead of a label for the fieldset of checkboxes. When I ran the code through the validator again this error did not come up.
- There is a warning on the date field as this is not supported in all browsers. However, I have chosen to leave it in and have conducted my own testing in Firefox, Chrome and Safari. In all of these the date option works as expected. In future, when I have completed the JavaScript module, I will add a pollyfill to fix this issue, [I have found a resource here that may fix the issue](https://github.com/jonstipe/date-polyfill/blob/master/date-polyfill.js).

**Responsive behaviour**

- The site uses Bootstrap's breakpoints to break down content for small, medium and large screens, to provide a good user experience on any device. I have also added media queries to some content to ensure these sections would be optimally displayed on any screen size.
- I have tested the site across various devices and browsers and using Chrome Developer tools and Mozilla developer tools, to ensure the content breaks at the points I intended for each screen size.
- I have also tested each page of the site using [Google's automated mobile friendly test](https://search.google.com/test/mobile-friendly). The results showed the site is mobile-friendly, [see screenshot here](assets/user-stories/mobile-friendly-test.PNG).

## Deployment

This site is deployed on GitHub pages and I deployed it in the following way:

1. Navigated to my repository on [GitHub here](https://github.com/Jade-ux/Learn_English_In_South_Africa)
2. Clicked 'Settings'
3. Scrolled down to the 'GitHub Pages' section 
4. Under 'Source' I selected 'Master Branch' as that is the branch I want to show.
5. My site was then published

[View my live site here.](https://jade-ux.github.io/Learn_English_In_South_Africa/)

**If you would like to run my code locally you can clone the site by following these steps:**

[Instructions taken from GitHub Help, you can find out more here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository)

1. Visit the main page of my repository on [GitHub here.](https://github.com/Jade-ux/Learn_English_In_South_Africa)
2. Click 'Clone or download'
3. Click the icon to the right of the URL. This will allow you to clone the repository using HTTPS.
4. If you would like to clone if using SSH, click 'Use SSH'
5. On your computer open Git Bash
6. Change the directory to the folder where you would like to run the cloned directory
7. Type 'Git clone' and then paste the URL you copied from my repository in GitHub
8. Press enter and your local clone of my site will be created.

## Credits

### Content

- All content was written by me.

### Media

- **Icons:** I used the [Font Awesome](https://fontawesome.com/) font library for the icons used throughout the site.

- **Image sources:** All photos used on this site have been labled for reuse and were taken from the following sources:

* [Wikimedia Commons](https://commons.wikimedia.org/)
* [Unsplash](https://unsplash.com/)
* [Pixabay](https://pixabay.com/)
* [Pope Field](https://www.pope.af.mil/News/Features/Display/Article/243323/taking-volunteering-to-a-whole-new-level/)
* [PxHere](https://pxhere.com/)

### Solutions to issues/bugs

**Fixing left and right scroll on mobile**
I found tht on mobile my website was scrollable left and right which was unintentional. [I found the solution here ](https://www.weblimitless.com/stop-website-showing-white-space-right-side/) and therefore have added that to the top of my stylesheet.

### Acknowledgements

- I received inspiration for this project from my friend, Susan Bandli, who is a host to students from around the world, and from conversations I have had with a few of these students.
- I took some inspiration for the design of my navigation from the Resume project from Module 5 of the Full Stack Developer course.
- Thank you to the Code Institute Slack community for support.
- Thank you to my mentor, Dick Vlaanderen for support and guidance.
