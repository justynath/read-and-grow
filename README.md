<p align="center"><img src="/assets/images/responsive.png" alt="drawing" width="800"/></p>


# Introduction
# Read And Grow
### Project Description - This website serves as a hub for a non-fiction reading book club, offering information on upcoming meetups and current reading selections. The aim is to promote non-fiction reading across various topics and cultivate a community of like-minded individuals committed to lifelong learning. The website caters to current members of the book club community, as well as anyone interested in reading or starting to read non-fiction books and engaging in post-reading discussions. The book club hosts both online meetups and in-person gatherings in central London.




# Features 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. 
You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

<hr> 

**Navbar**

  - Featured on all three pages, the fully responsive navigation bar includes links to the logo, home page, gallery, and sign-up page. It is identical on each page to facilitate easy navigation.
  - This section allows users to navigate seamlessly between pages on all devices without needing to use the 'back' button.

  <details><summary>Navbar Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

**Services**

  - Services section highlights available to the client services in a form of cards, each with a Call To Action button leading to the Contact form 

  <details><summary>Services Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

**The Gallery**

  - Gallery showcases various artwork by the Photographer, or images of past events
  - This section is valuable to the user as they will be able to easily identify the types of events the organisation puts together. 

  <details><summary>Gallery Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

**Contact Form**

  - An interactive contact form to enable users to get in touch with the company
  - Includes fields for name, email and a message

  <details><summary>Contact Form Screenshot</summary>

  <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 

**The Footer**

  - The footer section includes links to the relevant social media sites for Love Running. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media

  <details><summary>Footer Screenshot</summary>

   <p align="center"><img src="https://placehold.co/600x400" alt="drawing" width="600"/></p>

  </details>

<hr> 




## Future Features
While the current version of the project is fully functional, we have some exciting features planned for future updates. Here are a few ideas that we didn't have time to implement in this release:

1. **Client Galleries**:
   - Allow photographers to create private galleries for clients to view and download their photos securely.
2. **Online Booking and Scheduling**:
   - Implement a booking system that allows clients to schedule sessions with photographers, choose dates, and make payments online.
3. **Photo Editing Tools**:
   - Integrate basic photo editing tools like cropping, rotating, and applying filters directly on the website to enhance user-generated photos.
4. **Print Ordering**:
   - Enable clients to order prints, canvases, or other products featuring their favorite photos directly from the website.
5. **Portfolio Builder**:
   - Provide photographers with tools to easily create and customize their online portfolios, including options for different styles and layouts.
6. **Blog or News Section**:
   - Add a blog or news section to share photography tips, behind-the-scenes stories, and updates about your services.

<hr>

## Manual Testing 

#### Features Testing

|  Feature |  Action | Effect |
|---|---|---|
|Logo|Click|Brings back to Home page|
|Navbar Links|Click on Gallery|Opens Gallery|
||Click on About|Opens About page|
||Click on Contact|Opens Contact page|
|Contact Page|Fill out the form and submit|A form dump is rendered|
||Attempt to submit empty|Error pops up in field that's left empty|
|Social Media Links|Test Instagram link|Instagram profile opens in a separate tab|

<hr>

#### Lighthouse

**Introduction**
This report presents the results of Lighthouse testing conducted to assess the performance, accessibility, best practices, SEO, and PWA compliance of [Website Name].

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

#### Browsers

**Supported Browsers and Devices**
Our web application is officially tested and supported on the following browsers and devices:
- Google Chrome (latest version)
- Mozilla Firefox (latest version)

**Responsiveness Testing**
We conduct manual responsiveness testing on Chrome and Firefox to ensure a seamless user experience.

**Test Results**

| Device/Screen Size  | Chrome Performance | Firefox Performance |
|----------------------|--------------------|---------------------|
| Desktop (1920x1080) | Describe performance and issues on Chrome | Describe performance and issues on Firefox |
| Laptop (1366x768)   | Describe performance and issues on Chrome | Describe performance and issues on Firefox |
| Tablet (iPad)       | Describe performance and issues on Chrome | Describe performance and issues on Firefox |
| Mobile (iPhone X)   | Describe performance and issues on Chrome | Describe performance and issues on Firefox |

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