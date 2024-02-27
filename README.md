<p align="center"><img src="/assets/images/responsive.png" alt="drawing" width="800"/></p>

# Read and Grow
**Read and Grow is a website that serves as a hub for a non-fiction reading book club, offering information on upcoming meetups and current reading selections. The aim is to promote non-fiction reading across various topics and cultivate a community of like-minded individuals committed to lifelong learning. The website caters to current members of the book club community, as well as anyone interested in reading or starting to read non-fiction books and engaging in post-reading discussions. The book club hosts both online meetups and in-person gatherings in central London.**

<hr>

## Planning

<hr>

### Aim

### Targeted Audience

### User Stories

## Features 

<hr> 

**Navbar**

  - Featured on all three pages, the fully responsive navigation bar includes links to the logo, home page, current reading, and sign-up page. It is identical on each page to facilitate easy navigation.
  - This section allows users to navigate seamlessly between pages on all devices without needing to use the 'back' button.

  <details><summary>Navbar Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

**Introduction**

  - An Image of people holding books and having a discussion. This is to create a positive user experience and create a feeling of relaation as well as desire of belonging and being part of a community.
  - A welcoming sentence to summarise who this book club is for "lifelong learning lovers".

  <details><summary>Introduction Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

**About Us**

  - A short information about the book club and it purpose.
  - An invitation to check the current reading section with more details about oncoming meetup. It contains a link to allow intuitive navigation on the website.

  <details><summary>About Us Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

**Testimonials**

  - Quotes of people that have participared in book club meetups.
  - Each testimonial contains a photo of a person smiling and holding a book. This is to give autenticity as well as share the positive approach and increased happiness linked ot learing and being a part of comunity.

  <details><summary>Testimonials Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

**Current Reading**

  - Introduction of a new book "The Psychology of Money" with an image of the cover and short description of what teh book is about.

  <details><summary>Current Reading Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

**Discussion Guide**

  - Suggested questions to consider while reading and to be used during the meetup.

  <details><summary>Discussion Guide Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

**Meetup Details**

  - Details of future meetups including dates and location.
  - Users are encouraged to get in touch for further details by sending the sign up form. Link to sign up page provided for wasy navigation.

  <details><summary>Meetup Details Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

**Sign Up Form**

  - An interactive sign up form to enable potential memebers to get in touch and receive further information about the book club and meetups
  - Includes fields for name, email and a message

  <details><summary>Sign up Form Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

**The Footer**

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

## Manual Testing 

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
| Mobile (iPhone 12pro)   | Header fonds on horizontal screen weren not responsive. I fixed that by setting font size as percentages. | as Chrome |

**Known Issues**
- [List any known responsiveness issues or limitations]

**Recommendations**
If you encounter any responsiveness issues, we recommend:
- Updating your browser to the latest version.
- Trying an alternative device or screen size for optimal viewing.

<hr>

#### Screen Sizes testing

**Introduction**
This section provides an overview of how our web application [Website Name] performs across different screen sizes.

**Supported Screen Sizes**
Our web application is designed to be responsive and adapt to various screen sizes. Below are the screen sizes we have tested:

| Screen Size     | Description             |
|-----------------|-------------------------|
| Desktop         | 1920x1080 pixels        |
| Laptop          | 1366x768 pixels         |
| Tablet (iPad)   | 768x1024 pixels (portrait) and 1024x768 pixels (landscape) |
| Mobile (iPhone) | 375x812 pixels (iPhone X, portrait) and 812x375 pixels (iPhone X, landscape) |

**Testing Results**

| Screen Size     | Test Results           |
|-----------------|------------------------|
| Desktop         | Describe performance and issues on different browsers |
| Laptop          | Describe performance and issues on different browsers |
| Tablet (iPad)   | Describe performance and issues on different browsers |
| Mobile (iPhone) | Describe performance and issues on different browsers |

<hr> 

#### Bugs Resolved


**Introduction**
This section provides a summary of bugs that have been identified, reported, and subsequently resolved in [Website Name].

**Bug Tracking**
Below is a summary of resolved bugs:

| Bug ID | Bug Description | Status |
|--------|-----------------|--------|
| #001   | Describe the bug and its impact on the user experience. | Resolved |
| #002   | Describe the bug and its impact on the user experience. | Resolved |
| #003   | Describe the bug and its impact on the user experience. | Resolved |
| #004   | Describe the bug and its impact on the user experience. | Resolved |
| #005   | Describe the bug and its impact on the user experience. | Resolved |

**Bug Details**
Here are the details of the resolved bugs:

**Bug #001**
- **Description**: Describe the bug and the steps to reproduce it.
- **Resolution**: Explain how the bug was resolved, including any code changes or fixes.
- **Impact**: Discuss the impact of this bug on users and the importance of the fix.

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

#### Validator Testing 
- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)



## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Main Branch
  - Once the main branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. 
It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

#### Content 

- The text for the Home page was taken from Wikipedia Article A
- The development of this project was aided by the following YouTube tutorials:

| Tutorial Title      | Creator/Channel Name | Description                                          |
|---------------------|-----------------------|------------------------------------------------------|
| [Tutorial Title 1](link-to-tutorial) | [Creator/Channel Name 1] | How this tutorial helped you.             |
| [Tutorial Title 2](link-to-tutorial) | [Creator/Channel Name 2] | How this tutorial contributed to your project. |

- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

#### Media

The following images used in this project are sourced from Unsplash and are used under their respective licenses: