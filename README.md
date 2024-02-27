# Read and Grow
## Overview
Read and Grow is a website that serves as a hub for a non-fiction reading book club, offering information on upcoming meetups and current reading selections. The aim is to promote non-fiction reading across various topics and cultivate a community of like-minded individuals committed to lifelong learning. The website caters to current members of the book club community, as well as anyone interested in reading or starting to read non-fiction books and engaging in post-reading discussions. The book club hosts both online meetups and in-person gatherings in central London.

<hr><hr>

## Planning

<hr>

### Aim

<hr>

### Targeted Audience

<hr>

### User Stories

<hr><hr>

## Features 

<hr> 

### Navbar 

 - Featured on all three pages, the fully responsive navigation bar includes links to the logo, home page, current reading, and sign-up page. It is identical on each page to facilitate easy navigation.
 - This section allows users to navigate seamlessly between pages on all devices without needing to use the 'back' button.

  <details><summary>Navbar Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

### Introduction

- An Image of people holding books and having a discussion. This is to create a positive user experience and create a feeling of relaation as well as desire of belonging and being part of a community.
- A welcoming sentence to summarise who this book club is for "lifelong learning lovers".

  <details><summary>Introduction Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

### About Us

- An information about the book club and its purpose.
- An invitation to check the current reading section with more details about oncoming meetup. It contains a link to allow intuitive navigation on the website.

  <details><summary>About Us Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

### Testimonials

- Quotes of people that have participared in book club meetups.
- Each testimonial contains a photo of a person smiling and holding a book. This is to give autenticity as well as share the positive approach and increased happiness linked ot learing and being a part of comunity.

  <details><summary>Testimonials Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

### Current Reading

- Introduction of a new book "The Psychology of Money" with an image of the cover and short description of what the book is about.

  <details><summary>Current Reading Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

### Discussion Guide

- Suggested questions to consider while reading and to be used during the meetup.

  <details><summary>Discussion Guide Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

### Meetup Details

  - Details of future meetups including dates and location.
  - Users are encouraged to get in touch for further details by sending the sign up form. Link to sign up page provided for wasy navigation.

  <details><summary>Meetup Details Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

### Sign Up Form

  - An interactive sign up form to enable potential memebers to get in touch and receive further information about the book club and meetups
  - Includes fields for name, email and a message

  <details><summary>Sign up Form Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

### The Footer

  - The footer section includes links to the relevant social media sites for Read and Grow. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media

  <details><summary>Footer Screenshot</summary>

   <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

## Future Features
While the current version of the project is fully functional, I have some exciting features planned for future updates. Here are a few ideas that we didn't have time to implement in this release:

1. **Reading History**:
   - Additional page with bookcovers and short descriptions of the book. Promotes reading non-fiction books as well as demonstrate what type of books are being chosen for the bookclub.
2. **Online Booking**:
   - Implement a booking system for in person meetups that cater for limited numebr of people in the set location.
3. **Blog Section**:
   - More detailed and personal accounts of in person meetups, including inteesting discussion points, recomendations and photos.

<hr>

## Testing

### Features Testing

|  Feature |  Action | Effect |
|---|---|---|
|Logo|Click|Brings back to Home page|
|Navbar Links|Click on Current Reading|Opens Current Reading page|
||Click on Sign up|Opens Sign up page|
||Click on Contact|Opens Contact page|
|Contact Page|Fill out the form and submit|A form dump is rendered|
||Attempt to submit empty Name and Surname|Error pops up in field that's left empty|
||Attempt to submit empty or incorrect format email|Error pops up in field that's left empty or with incorrect email format|
|Social Media Links|Test Facebook, X and Instagram links|Facebook, X and Instagram main page opens in a separate tab|

<hr>

### Browsers 

**Supported Browsers and Devices**
Our web application is officially tested and supported on the following browsers and devices:
- Google Chrome (latest version)
- Safari (latest version)

**Responsiveness Testing**
I conduct manual responsiveness testing on Chrome and Safari to ensure a seamless user experience.

**Test Results**

| Device/Screen Size  | Chrome Performance | Safari Performance |
|----------------------|--------------------|---------------------|
| Desktop (2560x1440) | no issues | no issues |
| Laptop (1366x768)   | no issues | no issues |
| Tablet (iPad)       | no issues | no issues |
| Mobile (iPhone 12pro)   | Heading fonts on landscape view were not responsive | as Chrome |

**Known Issues**
- Heading fonts on landscape view were not responsive. I fixed that by setting font size as percentages.

<hr>

### Lighthouse

**Introduction**
This report presents the results of Lighthouse testing conducted to assess the performance, accessibility, best practices, SEO, and PWA compliance of Read and Grow.

**Test Execution**
Lighthouse tests were executed using the Google Chrome browser's DevTools.

**Test Metrics**
- Performance Score: 81
- Accessibility Score: 93
- Best Practices Score: 92
- SEO Score: 92

**Detailed Results**
- **Performance**: The website's performance score is 81, indicating good overall performance. However, there is room for improvement to further optimize loading times.
- **Accessibility**: The website excels in accessibility, with a score of 93, indicating strong adherence to accessibility standards. Minimal accessibility issues were detected.
- **Best Practices**: The website follows best practices with a score of 92. There are minor areas for improvement, particularly in script loading.
- **SEO**: SEO performance is strong, with a score of 92. The website has well-optimized meta tags and structured data markup.

**Areas for Improvement**
- Performance can be enhanced by optimizing resource loading and reducing unnecessary requests.
- Continue monitoring accessibility to maintain a high standard and address any emerging issues.
- Best practices can be further improved by optimizing script loading and code splitting.
- Maintain and regularly update meta tags and structured data markup to ensure strong SEO performance.

**Visuals**

<p align="center"><img src="https://res.cloudinary.com/dugnokxox/image/upload/v1692960667/Screenshot_2023-08-25_at_11.50.29_cfmkxt.png" alt="drawing" width="800"/></p>

<hr>

### Bugs Resolved

**Introduction**
This section provides a summary of bugs that have been identified, reported, and subsequently resolved in Read and Grow.

**Bug Tracking**
Below is a summary of resolved bugs:

| Bug ID | Bug Description | Status |
|--------|-----------------|--------|
| #001   | White space under the background image gives an impression as if something is missing from the page | Resolved |
| #002   | Describe the bug and its impact on the user experience. | Resolved |
| #003   | Describe the bug and its impact on the user experience. | Resolved |
| #004   | Describe the bug and its impact on the user experience. | Resolved |
| #005   | Describe the bug and its impact on the user experience. | Resolved |

**Bug Details**
Here are the details of the resolved bugs:

**Bug #001**
- **Description**: White space under the background image despite seting background-image to cover.
- **Resolution**: I added display flex to the main sectiona and set it as c.
- **Impact**: The user feels reassured that the form is the only item on the page, no information is missing.

**Bug #002**
- **Description**: Describe the bug and the steps to reproduce it.
- **Resolution**: Explain how the bug was resolved, including any code changes or fixes.
- **Impact**: Discuss the impact of this bug on users and the importance of the fix.

**Bug #003**
- **Description**: Describe the bug and the steps to reproduce it.
- **Resolution**: Explain how the bug was resolved, including any code changes or fixes.
- **Impact**: Discuss the impact of this bug on users and the importance of the fix.

**Bug #004**
- **Description**: Describe the bug and the steps to reproduce it.
- **Resolution**: Explain how the bug was resolved, including any code changes or fixes.
- **Impact**: Discuss the impact of this bug on users and the importance of the fix.

**Bug #005**
- **Description**: Describe the bug and the steps to reproduce it.
- **Resolution**: Explain how the bug was resolved, including any code changes or fixes.
- **Impact**: Discuss the impact of this bug on users and the importance of the fix.

<hr>

#### Bugs Unresolved(if applicable)

| Bug ID | Bug Description | Status |
|--------|-----------------|--------|
| #001   | Describe the bug and its impact on the user experience. | Unesolved |
| #002   | Describe the bug and its impact on the user experience. | Unesolved |
| #003   | Describe the bug and its impact on the user experience. | Unesolved |
| #004   | Describe the bug and its impact on the user experience. | Unesolved |
| #005   | Describe the bug and its impact on the user experience. | Unesolved |
<hr>

### Validator Testing 

**HTML**
Code has been validated with the official [W3C validator]https://validator.w3.org/nu/#textarea
index.html
  - Error setting width=100% and no-repeat for the book-club image. Fixed by moving styling to css file.
  - Warnings about possible misused of aria-label with the images linked to testimonials
  - No further errors were returned when passing through the official [W3C validator]
current-reding.html
  - No errors were found when passing through the official [W3C validator] https://validator.w3.org/nu/#textarea
signup.html
  - Errors with misuse of h3 headings in label, fixed
  - No further errors were returned when passing through the official [W3C validator]

**CSS**
  - One warning linked ot texarea - "Imported style sheets are not checked in direct input and file upload modes"
  - No errors were found when passing through the official [(Jigsaw) validator]



## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository I navigate to the Settings tab 
  - From the source section drop-down menu, I selected the Main Branch
  - Once the main branch has been selected, the page automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://justynath.github.io/read-and-grow/signup.html


## Credits 

In this section you need to reference where you got your content, media and extra help from. 
It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- Na bar and toggle bar were inspired by the Code Institute Love Running walk through project.
- The use of the flexbox was supported by this [lesson] (https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- The icons used were taken from [Font Awesome](https://fontawesome.com/)
- The fonts were imported from [Google Fonts](https://fonts.google.com/)
- The colour scheme was inspired by this [article](https://muffingroup.com/blog/calm-color-palette/)

### Media

- The image used as background waw sourced from https://www.pexels.com/
- The following images were source from https://www.freepik.com/:
   - Book Club image [attribution](https://www.freepik.com/free-photo/authentic-book-club-scene_37155644.htm#page=2&query=book%20club&position=0&from_view=keyword&track=ais&uuid=1d4feaf7-528f-40ee-a71d-f1a81bc071c0")
- Photos used for tesimonials, source from https://www.freepik.com/:
   - Man reading image 1 [atttribution](https://www.freepik.com/free-photo/man-sitting-couch-holding-book_6880673.htm#fromView=search&page=1&position=37&uuid=683e1cd9-401b-4c09-ba00-b4b29e997f16)
   - Man reading image 2 [atttribution](https://www.freepik.com/free-photo/senior-person-gesturing-isolated_20728512.htm#fromView=search&page=1&position=38&uuid=0a943e5a-72e2-4f31-af82-36739a80e5e8)
   - Women reading image 1 [atttribution](https://www.freepik.com/free-photo/leisure-self-education-hobby-retirement-concept-picture-good-looking-mature-senior-female-striped-sweater-stylish-eyewear-enjoying-reading-living-room-smiling-joyfully_11199979.htm#fromView=search&page=1&position=5&uuid=437c8519-9919-4c2a-8203-74929a13020b)
   - Women reading image 2 [atttribution](https://www.freepik.com/free-photo/front-view-woman-enjoying-book_5123756.htm#fromView=search&page=3&position=8&uuid=34c15c65-001e-4a75-a3b2-8d376e861515)
