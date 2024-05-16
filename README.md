Welcome to,

# 🏆 Freestyle Fanatics 🏆

![Electronic devices showing website on screen: computer, tablet, phone.](docs/design/freestyle_mockup.png "freestyle fanatics device mockup")

[View the live project here.](https://gemmabutcher-dev.github.io/freestyle_dance/)

## Table of Contents
1. [UX](#ux)

  * Project Goals
  * Dancer Goals 
  * User Stories  
  * Design Choices
  * Wireframes

2. [Features](#features)

  * Existing Features
  * Features left to implement

3. [Technologies used](#technologies-used)

  * Languages Used
  * Frameworks, Programs and Libraries Used

4. [Testing](#testing)

  * Overall Peformance
  * Code Validation
  * Accessibility Testing
  * Bug Fixes
  * Hero Image Change
  * Testing User Stories from User Experience (UX) Section
  * Further Testing

5. [Deployment](#deployment)

  * GitHub Pages
  * Forking the GitHub Repository
  * Making a Local Clone

6. [Credits](#credits)

  * Content
  * Media
  * Code
  * Acknowledgements

------

## UX

### Project Goals

The primary goal of Freestyle_dance is to provide a hub of all things freestyle to all aged 12 - adult with easy and clear navigation with signposting to external sites where necessary. 

#### Dancer Goals

The main target audeince for this website is dancers aged 12. and over.

Dancers and guardian goals are:

  * Navigate way around site easily.
  * Easily follow links to signposted pages.
  * Find the site informative, fun and engaging.
  * Know what the next steps to take are.
  * Easily navigate to the facebook page to follow and interact.

Freestyle Fanatics can help dancers meet these goals by:

  * Providing relevant information and links all in one website.
  * Providing a simple and clear navigation bar.
  * Give dancers information about freestyle dance and relevant associated information.
  * Engaging images to allow dancer to know they have found the site for the 
    correct genre.
  * Same theme and layout for all pages.
  * Use a maximum of 3 clicks from start to end goal to minimise cognitive 
    overload.
  * The feel is engaging and informative.

#### User Story

As a current or aspiring freestyle dancer or dancers guardian i need to...
  * Find information about the freestyle dance genre.
  * Find where i can to learn to dance and who is qualified to teach me.
  * Learn about competitions and what is required to compete.
  * Be informed of regulatory associations.


### Design Choices

  * Single column mobile first responsive design.

#### Colour Scheme

  * Four colours will be used in addition to black and white throughout the site to create a theme. The colour pallette was picked from the hero image on the home page. This should carry the site identity across all pages.

![A young girl performing a dance routine on stage, dressed in a sparkling blue costume with feathered accessories, surrounded by an attentive audience.](docs/design/color_palette.png "color pallette freestyle fanatics")

#### Typography

  * The Poppins font will be the font used for the all headings on the website and Sans Serif is to be used as a fallback font should for any reason the Poppins google font not load correctly to the website. Poppins is a crisp clear font that has rounded features that adds flow and creativity whilst having a corporate edge.

  * The Roboto font will be the font used for the other text on the website and Sans Serif is to be used as a fallback font should for any reason the Roboto google font not load correctly to the website. Roboto is a sharper font that has less rounded features than Poppins having more of a corporate edge, complimenting the poppins font with increased ease of readability.

#### Imagery

  * Imagery is key to immediately letting the user know they are viewing the correct dance genre and engage quickly and convey a positive and energetic energy.

### Wireframes

## Features

### Current Features

  * Mobile first design fully responsive.

## Technologies Used

### Languages Used
  
  * [HTML5](https://en.wikipedia.org/wiki/HTML5)
  * [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Programs and Libraries Used

1. Bootstrap 4.3.1:
   Bootstrap was used to assist with the responsiveness and styling of the website.
2. Hover.css:
   Hover.css was used on the Social Media icons in the footer to add the float transition while being hovered over.
3. Google Fonts:
   Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.
4. Font Awesome:
   Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
5. jQuery:
   jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.
5. Git
   Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
6. GitHub:
   GitHub is used to store the projects code after being pushed from Git.
7. Balsamiq:
   Balsamiq was used to create the wireframes during the design process.
8. Am i responsive?:
   Am i reponsive was used to create the device mockup in README.md.
9. ahrefs:
   ahrefs was used to help generate alt text for images.
10. Canva:
   Canva's color pallette generator was used to create a color pallette from the homepage hero image.

## Testing

### Overall Peformance

The complte site was tested on lighthouse to assess the overall performance of the site. You can see the results [here](docs/testing/lighthouse_test.png)

### Code Validation

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

[HTML Results can be viewed here](docs/testing)

[CSS Results can be viewed here](docs/testing)

### Accessibility Testing

  * The complete site was tested using [Web Aim](https://wave.webaim.org/) and has passed. This can be [viewed here](docs/testing/webaim.png).
  * Some issues were created using the jumbotron to create a hero section. For some reason the only way i could 
    create the hero image with the jumbotron in front was to use a background images in the jumbotron div css. Whilst this is not best practice for accessibility it has not impacted the score for accessibility which is 100%. 

### Bug Fixes

  * Bug found where the bootstrap navbar would expand but not compress back down. The issue was eventually traced back to the js script links at the bottom of the html pages. These have been updated and it now works as it should. The issue can be viewed on [this screenshot](docs/bug_fixes/navbar_bugfix.png) for further   details.
  * There is a bug on the submit button on the contact form in contact.html. There is an active class that when 
    the button is clicked it changes colour even if all the required fields are not filled out and the form 'sent'. I have logged this issue with bootstrap as it appears it cant be overridden and is an error at bootstrap. It does not seem to effect the submission of the form itself and is more of an aesthetic and design issue to be rectified.

### Hero Image Change

A change in hero image on the homepage was made with the same colour theme as i feel the updated image is more fun and engaging than the original.

### Testing User Stories from User Experience (UX) Section

#### Project Goals

1. The primary goal of Freestyle_dance is to provide a hub of all things freestyle to all aged 12 - adult with easy and clear navigation with signposting to external sites where necessary. 
  
  * Upon entering the site there is a clear functioning nav bar at the top of the page with links to the other 
    site pages that are clearly labelled. There is a clean and crisp hero image lettignthe user know they have found relevant content as a quick glance. 
  * The clear welcome section below the hero image offers text to reaffirm what the site is about.
  * There are 3 pages each with defined topics that are clear to the user. The user can quickly, easily and 
    conveniently move from section to section with ease to gather required information.
  * There are links to external sites that open in new tabs to keep the navigation simple and clear.

2. The main target audeince for this website is dancers aged 12. and over.

  * The site content could be understood by children 12 years and over and adults alike. 
  * Children under 10 years old may struggle with some aspects of terminology and navigation.
  * Hero images let people of most ages know they are navigating their way around a dancing topic.
  * The clear welcome section below the hero image offers copy to reaffirm what the site is about.
  * The Youtube iframe offers a visually stimulating and engaging experience and is appropriate for all ages 
    making it appropriate for the intended audience.

    ![mobile device showing website on screen](docs/testing/navbar_screenshot.png "freestyle fanatics device mockup")

#### Dancers and guardian goals are:

1. Navigate way around site easily.

  * A clean crisp fully functioning navbar ensures this is achieved.
  * There is a clear crisp footer which is the same across all pages which can be viewed [here](docs/testing/footer_screenshot.png)

2. Easily follow links to signposted pages.
  
  * All links to external signposted pages open in new tabs with the _blank attribute. Links clearly
    indicate their function and purpose. 
  * Links are located in the copy and footer.


3. Find the site informative, fun and engaging.

  * The content is focused on informing what the dance genre is who is able to take part. 
  * The site offers information on the steps to take in order to compete or dance for fun.
  * The hero images were chosen 
  * The youtube iframe offers a visually stimulating and engaging experience and is appropriate for all ages 
    making it appropriate for the intended audience.
  * The decision was taking to change the hero image on the home page to one where the dancer was smiling in 
    order to meet this criteria. The colour theme remains unchanged due to the back ground and image colour remaining the same.
  * The user can engage with the site user by filling out the contact form on the contact page which can be 
    viewed [here](docs/testing/contact_form_screenshot.png)

4. Know what the next steps to take are.

  * The competition page offers information on what is required to be able to take part in competitions and how 
    to go about it.
  * External links to the Association of Dance and Freestyle professionals which lists qualified teachers and 
    respective schools. This link is also found in the footer.
  * The contact form on the contact page offers users the opportunity to contact the site owner for further 
    information.

5. Easily navigate to the facebook page to follow and interact.

  * There is a link to the facebook page in the footer on all pages allowing the user to navigate to the 
   facebook page in one click.
  * The link opens in a new tab for ease of navigation.
  * The link is represented by the standard facebook icon.

#### Freestyle Fanatics can help dancers meet these goals by:

1. Providing relevant information and links all in one website.

  * All relevant links and information is displayed across the three pages.
  * Links to facebook and the ADFP can be found in the footer on all pages.

2. Providing a simple and clear navigation bar.

  * Upon entering the site there is a clear functioning nav bar at the top of the page with links to the other 
    site pages that are clearly labelled.
  * The navbar reduces to a "hamburger" icon for mobile and tablet devices maintaining clear navigation.

3. Give dancers information about freestyle dance and relevant associated information.
  
  * Information across the site lets the user know what the topic is and how they can become invoved in the 
    dance genre.
  * External links provided to associations for further information.
  * The contact form on the contact page offers the user the opportunity to contact the site owner.

4. Engaging images to allow dancer to know they have found the site for the correct genre.
  
  * Hero images are used on both the home page and the contact page to allow the user to know they are viewing 
    the correct information and in relation to the relevent genre.

5. Same theme and layout for all pages.

  * All pages use the same navbar and footer to maintain site identity and theme.
  * The same single column layout is used across all pages in line with site theme. 
  * The same colour scheme and border styling is used for all containers and sections.

6. Use a maximum of 3 clicks from start to end goal to minimise cognitive 
    overload.

    * There is no more than 3 click from one point of the site to the end of the navigation to another part of the site. 
    * Use of a clear navbar, footer and hyperlinks ensure this.

7. The feel is engaging and informative.
 
    * The hero image provies an immediate user visual stimulation on both the home page and competition page.
    * There is a fully responsive youtube iframe video of a freestyle competiton performance on the competition page which offers engaging visual and audio stimulation that the users has full control over at all times. An example of this is viewed [here](docs/testing/iframe_screenshot.png)
    * Information across the site lets the user know what the topic is and how they can become invoved in the 
      dance genre. 
    * The contact form on the contact page offers users the opportunity to contact the site owner for further 
      information.


### Further Testing

* The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
* The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
* A large amount of testing was done to ensure that all pages were linking correctly.
* Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/GemmaButcher-dev/freestyle_dance.git)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://gemmabutcher-dev.github.io/freestyle_dance/) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/GemmaButcher-dev/freestyle_dance.git)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/GemmaButcher-dev/freestyle_dance.git)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/GemmaButcher-dev/freestyle_dance.git
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/GemmaButcher-dev/freestyle_dance.git
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

### Code

  * [Bootstrap4](https://getbootstrap.com/docs/4.4/getting-started/introduction/): Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System.
  * [Google Developer Tools](https://developer.chrome.com/docs/devtools) : For problem solving and managing css overrides. 

### Content

  * All content was written by the developer.
  * Canva color pallette picker for generating the brand [color palette](https://www.canva.com/colors/color-palette-generator/)

### Media

  * All images are the property of the developer who holds fully copywrite.
  * Iframe video is the property of youtube.

### Acknowledgements

  * My Mentor for continuous helpful feedback.
  * Tutor support at Code Institute for their support.