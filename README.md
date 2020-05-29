# Learn English in South Africa

## Purpose

The Learn English in South Africa website is a B2C commercial website owned by a study-tourism agency that provides a booking service for people who would like to complete an English-language course in South Africa.

The website allows users to browse options for courses, accommodation and experiences. The experiences are activities they can enjoy in South Africa.

My inspiration for this website has come from conversations I have had with people who have travelled to South Africa, from all over the world, to study English. One of my friends is a host and has been providing accommodation for students for many years. The students are from 16 years old and up and come from many different backgrounds.

The agency's USP is allowing prospective students to book their entire study-tourism experience in three easy steps - first they find the course they want to take, by browsing accredited courses offered on the website. Then they decide on their preferred accommodation type. The last step is to choose their experiences. 

Currently the site only allows users to book courses and browse the other options, and the agency would then get in touch with the user to take the next steps. However, in future developments I would like to add the ability for users to log in and add items to their 'shopping basket' and book for everything online.

**Business goals:** The agency recieves commission from bookings taken for courses, accommodation and activities. The agency’s goal is to become a popular information source for foreign students who want to complete a language course in South Africa, and to have prospective students book their entire package (courses, accommodation and experiences) through the agency. SEO will be very important in order to attract as many prospective students as possible.

**User goals:** Users would be looking for a trustworthy source of information about English courses, and would want to compare a number of courses based on price, suitability, length of time and rating. Users who are willing to travel abroad to learn English will want to ensure they have suitable accommodation booked before they depart and would like to plan a few activities in South Africa to make the most of their time in the country. The selling point for this website is that users can book all of these parts of their trip at the best prices (the agency will have negotiated bulk discounts), all in one place and as easily and quickly as possible.

## UX

### User story one

The user is looking for English courses abroad but does not yet know where she wants to study. She lands on the home page, reads through the 'Why study in South Africa?' section then scrolls to the 'Get started in 3 easy steps' section which tells her how the process will work. After reading the content she is satisfied that she would like to study in South Africa. 
[See the user journey here](assets/user-stories/user-story1.jpg) 
1. She clicks the 'Find your course' button 
2. This takes her to the Courses page. She browses through the courses. When she finds one she likes she clicks 'Book this course'.
3. She completes the form and hits 'send'
4. She is taken to the 'Thank you' page and from there either chooses to leave the site or carry on browsing through to the accommodation page. 

### User story two

User knows he wants to study in SA and wants to find the best course. He is researching many sites and wants to go straight to looking up the courses we have available.
[See the user journey here](assets/user-stories/user-story2.jpg) 
1. He immediately clicks the 'Courses' navigational link.
2. On the courses page he browses through the courses. When he has found the one he wants he clicks 'Book this course'
3. He completes the form and hits 'send'. 
4. He is taken to the 'Thank you' page and from there he clicks the button to browse through he accommodation options.

### User story two

The user reaches the courses page via a search engine (bypassing the home page). 
[See the user journey here](assets/user-stories/user-story3.jpg)
1. She browses the content in the accordions, finding the course she would like to apply for and clicks 'Book this course'. 
2. Having completed the form she is taken to the 'Thank you' page. She is interested in booking accommodation for her stay in South Africa and clicks the 'Browse accommodation' button.
3. On the Accommodation page she looks through the types of accommodation and decides which she would prefer. Then, she scrolls down to the '3 Easy steps' section and reads about the process. She is interested in finding out more about the experiences and clicks the 'Choose your experiences' button.
4. She reads through the experiences and decides which she would like to take part in. From there she leaves the site as she will wait to hear from the agency by email.

## Design

I created mockups before building the site. This helped me plan how to structure the content, the user journeys and the responsive design.

[See my wireframes here](assets/mockups-and-wireframes/milestone-project-1-wireframes.pdf)

I also created style mockups to test out colour combinations and styles for the site. 

[Home page mockup](assets/mockups-and-wireframes/styles-mockup--home-pg.jpg)

**Colours:** The accent colours I have used, the pink, green, yellow and blue, are colours taken from the houses shown in the banner image on the home page. I have used these colours because they are vibrant and high-energy colours and will appeal to adventurous, energetic people looking for new learning experiences. 
I added additional colours for roll-overs and active states which are much deeper and richer, which demonstrates the rich variety of experiences a student could expect in South Africa, and the country's rich cultural heritage.

**Home button on navigation:** The logo at the top of the website and in the footer serve as the link to get back to the home page. However, when I tried to create the entire div as a link it broke the grid structure. Therefore I have created each individual element within the logo as a link. In future developments I plan to make the entire logo block a link in both the top and footer of the website.

**Buttons:** There are two styles of buttons on the site. The outline buttons are for people in the first phase of the buying cycle and are still only looking around at information. The solid colour buttons are for people in the next buying phase who are ready to book a course or contact the agency.

##URL naming

As SEO is an important consideration for this site, I have named URLs for SEO, therefore the 'Courses' page URL is 'english-courses'

## Issues/challenges

### Courses page

**Booking form:** The form includes a question 'Which course would you like to book' which I realise is not good user experience because the user would have already chosen their course and clicked the 'Book this course' button next to their chosen course.
However, as the development of a solution that would automatically add the course name to the form is beyond the scope of this milestone project, I have deferred the development of that feature to future releases.  

### Accommodation page

I had originally added a carousel to the Accommodation page, to show a gallary of accommodation options. However, I know that carousel's are not accesible so in the end I decided to remove it.

I have not added a gallery of images in a different format to make up for it because I realised without the gallery the page was much more succint and would get users moving on to the next step quicker. I don't think the gallery added much to the user experience.

## Features

//In this section, you should go over the different parts of your project, and describe each in a sentence or so.

### Existing Features

- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- **Forms success message:** I have added a new page for the form action, to display the 'Thank you for booking...' text but in future development I would like to add that message to the page the user is on when they submit the form and connect it up to a database. 
- **Forms automatically include course name:** On the courses page, I would like to have the form title automatically include the name of the course relating to the 'Book this course' button the user clicked.


## Technologies Used

- This site was written in HTML5 and CSS3
- [Bootstrap](https://getbootstrap.com/)
  - This project uses Bootstrap to speed up the development process. Some Bootstrap elements use Jquery, Popper.js and Javascript.

## Testing

**Colours:** I tested the colours I have used for navigation elements using the [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) to ensure accessibility of all colours. I realised that a few of the colours I was using for the roll-over effects were not accessible and I have therefore chosen darker colours to ensure accessibility to WCAG AA standards. This has worked well as I now have deeper and richer colours for roll-overs but brighter colours for highlights which hint at the rich variety of experiences people can expect when they visit South Africa.

**Forms:** I manually tested each of the forms on the website, making sure all required fields had to be completed before the form could be submitted and ensuring that the input validators are working. I also tested that when the form is submitted the user is notified that it has been submitted successfully - this notification comes in the form of a new page which says 'Thank you for ...'.

//In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

//Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

//For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
   1. Go to the "Contact Us" page
   2. Try to submit the empty form and verify that an error message about the required fields appears
   3. Try to submit the form with an invalid email address and verify that a relevant error message appears
   4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

## Credits

### Content

- All content was written by me.

### Media

- **Icons:** I used the [Font Awesome](https://fontawesome.com/) font library for the icons used throughout the site.

- **Image sources:** All photos used on this site have been labled for reuse and were taken from the following sources:

*[Wikimedia Commons](https://commons.wikimedia.org/)
*[Unsplash](https://unsplash.com/)
*[Pixabay](https://pixabay.com/)
*[Pope Field](https://www.pope.af.mil/News/Features/Display/Article/243323/taking-volunteering-to-a-whole-new-level/)
*[PxHere](https://pxhere.com/)

### Solutions to issues/bugs

**Fixing left and right scroll on mobile**
I found tht on mobile my website was scrollable left and right which was unintentional. [I found the solution here ](https://www.weblimitless.com/stop-website-showing-white-space-right-side/) and therefore have added that to the top of my stylesheet.

### Acknowledgements

- I received inspiration for this project from Susan Bandli, who is a host to students from around the world.
- I took some inspiration for the design of my navigation car from the Resume project from Module 5 of the Full Stack Developer course.
