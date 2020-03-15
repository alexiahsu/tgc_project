# tgc_project

tgc_project is an elegant yet simple webpage that is suitable for candidates looking to upload their curriculum vitae. The webpage seeks to create a seamless experience and the design is suitable for a variety of industries. The use of colors is a marriage between deep and vibrant colors that can evoke both sense of professionalism and spontaneity. To keep users engaged, the webpage is deliberate in decluttering words and showcasing only exemplary details of the candidate. Alternatively, interested users can also extract the full detailed copy of the CV.

tgc_project will be an open-source CV webpage in hope to nudge candidates into impressing their potential employers with a web-based CV. As we collectively move into an almost-complete digitised world, we must first begin with how we present ourselves in our applications.
 
## UX

This website is suitable for candidates looking to present their CV on a webpage. Given the color scheme, which is a balance between bold and vibrant, it can be used for a myriad of industries - ranging from professions to creatives. The website is scroll-only and does not require further loading, which takes away the potential impatience arising from slow loads. The user can either be taken through each important segment by scrolling, or skip to relevant sections with the help of a sticky navbar. 

### Webpage elaboration
* The page begins with a sticky navbar that is linked to each section. With the sticky function, it allows users to jump to any section at any point of time.
* The carousel is deliberate in showcasing the candidate's top 3 strengths. By doing so, users are first greeted with powerful messages written by the candidates. First impression counts, hence the carousel seeks to capture the attention of users with their competencies.
* The Story section is where candidates unveil their current commitments and past experiences.
* Referrals important for candidates to boost credibility in the experiences they've presented. The placement of this section is deliberate in gaining the users' trust upon reading the track record.
* Talents section mirrors the first section because it reminds users to tie back these competencies to their past experiences.

### User Stories
* As a user, I want to navigate seamlessly through the page
* As a user, I want to see decluttered webpages. 
* As a user, I want to have the option of downloading the full CV
* As a user, I want to see credibility in the candidates' track record by linking me to external parties
* As a user, I want to be able to contact the candidate
* As a user, I want a see a color scheme that is not discomforting

### Inspiration
* Inspired by: https://www.pinterest.com/pin/496733033903898193/
* Mock-up: https://github.com/alexiahsu/tgc_project/blob/master/mockup.png

## Features

* Sticky navbar: presents the different sections within the webpage. Titles model after CV.
* Carousel: presents top 3 strengths of candidates. 
* Story: includes current commitment and past experiences. Able to download full CV version.
* Referrals: includes link related to Story section. Seeks to improve credibility.
* Talent: includes other skillsets that may not be relevant to job application. 
* Footnote: provides contact details for users to reach out to candidates.
 
### Additional features to be implemented
* Chatbox function to allow direct communication between users and candidates (integration with intercom)
* Dropdown list for talents - showcase more talent within the section, but dropdown allows users to pick interests
* Slideshow in referrals: instead of list of links, have carousel of referrer and their testimonial for the candidate

## Technologies Used

* [JQuery](https://jquery.com)
  * The project uses **JQuery** to simplify DOM manipulation.
* Adobe XD(https://www.adobe.com/sea/products/xd.html)
  * Used for scaffolding
* Pintrest(https://www.pinterest.com/)
  * Used for reference
* Unsplash(https://unsplash.com/)
  * Used to retrieve HD quality pictures
* Adobe color(https://color.adobe.com/search?q=soft&page=2)
  * Reference for color scheme
* Github(https://github.com/)
  * Deploy webpage
* Responsinator(https://www.responsinator.com)
  * Test responsiveness of webpage
* Bootstrap 4(https://getbootstrap.com/)
  * Provides general CSS framework


## Testing
1. Navbar links: check hover and click on each link 
  - Scrolly function should work
  - Each link takes to correct section
    - Alexia's take to start of page
    - Story takes to story section
    - Referrals takes to referrals section
    - Talents takes to talents section
    - Contact takes to footer section
2. Carousel
  - Click on left arrow -> should change to previous slide
  - Click on right arrow -> should change to next slide
  - Auto transition should occur without clicking
  - Slide 4: Let me tell you more -> should take to Story section
3. Story section
  - Download full cv button -> should open a new tab with cv PDF version
4. Referrals 
  - Each link should open a new tab to the respective referrers
5. Contact
  - Handphone number should open up dial mode
  - Email address should open into mail mode
    

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits & Acknowledgements
- Intensify - TEMPLATED(https://templated.co/intensify)
  - Provided scrolly, buttons, and layout
- Unsplash
  - Provided pictures for containers
