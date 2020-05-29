# Learn English in South Africa 

**Purpose**

The Learn English in South Africa website is owned by a study-tourism agency that provides a booking service for people who would like to complete an English-language course in South Africa.

The website allows users to browse options for courses, accommodation and experiences. The experiences are activities they can enjoy in South Africa. 

The agency's USP is allowing prospective students to book their entire study-tourism experience in three easy steps - first they find the course they want to take, by browsing accredited courses offered on the website. then they decide on their preferred accommodation type. The last step is to choose their experiences. 
 
## UX

**User stories**



**Home button on navigation** The logo at the top of the website and in the footer serve as the link to get back to the home page. However, when I tried to create the entire div as a link it broke the grid structure. Therefore I have created each individual element within the logo as a link. In future developments I plan to make the entire logo block a link in both the top and footer of the website.

**Colours** I have taken the colours from the colours of the houses shown in the home page banner. These are vibrant and eye-catching colours and I think they will appeal to the agency's target market who are adventurous, energetic people looking for new learning experiences.

**Buttons** There are two styles of buttons on the site. The outline buttons are for people in the first phase of the buying cycle and are still only looking around at information. The solid colour buttons are for people in the next buying phase who are ready to book a course or contact the agency.

#Wireframes

[See my wireframes here](assets/mockups-and-wireframes/Milestone-Project-1-wireframes.pdf)

#mockups

I found the combination of colours for my website by creating mockups in Photoshop and trying out different colours. I settled on colours taken from the houses shown in the banner image on the home page because those colours are vibrant and fun and I believe they would appeal to young, adventurous people who are the target market for the agency's services and this website.
[Home page mockup](assets/mockups-and-wireframes/Styles-mockup--home-pg.jpg)

## URL naming

Named URLs for SEO therefore the 'courses' page URL is 'english-courses'
--------

##attribution

**Fixing left and right scroll on mobile**
I found on mobile my website was scrollable left and right which was unintentional. [I found the solution here ](https://www.weblimitless.com/stop-website-showing-white-space-right-side/) and therefore have added that to the top of my stylesheet.

Image sources (all labled for reuse)

https://commons.wikimedia.org/
Unsplash
Pixabay
https://www.pope.af.mil/News/Features/Display/Article/243323/taking-volunteering-to-a-whole-new-level/
https://pxhere.com/



##Courses page

**Form**

I have added a new page for the form action, to display the 'Thank you for booking...' text but in future development I would like to add that message to the page the user is on and connect it up to a database.

**Accommodation page** 

I had originally added a carousel to the Accommodation page, to show a gallary of accommodation options. However, I know that carousel's are not accesible so in the end I decided to remove it. 

I have not added a gallery of images in a different format to make up for it because I realised without the gallery the page was much more succint and would get users moving on to the next step quicker. I don't think the gallery added much to the user experience.



---- instructions
 
Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
- As a user type, I want to perform an action, so that I can achieve a goal.

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Another feature idea

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


## Testing

**Colours**

I tested the colours I have used for navigation elements using the [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) to ensure accessibility of all colours. I realised that a few of the colours I was using for the roll-over effects were not accessible and I have therefore chosen darker colours to ensure accessibility to WCAG AA standards. This has worked well as I now have deeper and richer colours for roll-overs but brighter colours for highlights which hint at the rich variety of experiences people can expect when they visit South Africa.


//In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

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
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X



----- Delete from here

<img src="https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png" style="margin: 0;">

Welcome Jade-ux,

This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. You can safely delete this README.md file, or change it for your own project.

