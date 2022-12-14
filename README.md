## Table of Contents
- [Milestone Project 1](#milestone-project-1)
  * [Purpose](#purpose)
  * [Exam Hacker](#exam-hacker)
  * [Target User Group](#target-user-group)
  * [UX Design](#ux-design)
    + [User Stories](#user-stories)
  * [Features](#features)
    + [Existing Features](#existing-features)
      - [Landing Page Images](#landing-page-images)
      - [Exam Structure Page Images](#exam-structure-page-images)
      - [Exam Resources Page Imagees](#exam-resources-page-imagees)
    + [Technology Used](#technology-used)
    + [Features left to implement](#features-left-to-implement)
  * [Testing](#testing)
    + [Development Testing](#development-testing)
      - [Deploying a Local Server](#deploying-a-local-server)
      - [Some Examples](#some-examples)
    + [High Level Testing](#high-level-testing)
    + [Validator Testing](#validator-testing)
  * [Version Control Strategy](#version-control-strategy)
    + [VCS in the GitPod IDE](#vcs-in-the-gitpod-ide)
  * [Deployment](#deployment)
    + [Project Creation](#project-creation)
    + [Using Github Pages](#using-github-pages)
  * [Credits](#credits)
    + [Content](#content)
    + [Media](#media)

# Milestone Project 1

## Purpose
This website is for students enrolled in the International Baccalaureat's Computer Science program who wish to master the third examination paper (Paper 3). Paper 3 focuses on a case study which changes each year. Teachers and students receive the case study at the same time. Although the strucure of the exam remains unchanged, the questions change each year with the new case study. Therefore, students cannot rely on past papers to help them learn content, and neither can teachers rely on previous years' content to teach their lesson. They must understand how the paper is strucutred and be able to anticiapte what might be asked of them in order to be well prepared.  

Although the case study provides key terms and introduces key concepts, this is done in a most superficial way. In order to prepare for the exams, students are expected to do quite a bit of independant research. That also means teachers must also research in order to teach the content properly.

There are currently limited resources avaialble for students and teachers. There are a YouTube videos and tutorials that address the content, but none that I have found that address the structure of Paper 3. Nor do any of these resources address how students can frame their responses to maximize their marks. What ends up happening is teachers and students end up scouring the internet for resources, some are good and some not so good.

There is really only one website that is dedicated to DP Computer Science Paper 3 - [IB CompSci-Hub](https://ib.compscihub.net/paper3).  The only thing available is a generic description of the what the paper is about. Another site found [ibcomputerscience.xyz](https://ibcomputerscience.xyz/ib-hl-paper3-case-study-2022-genetic-algorithms/) has the exam for May 2022 and is out of date. The site is poorly organized and extremely frustrating to navigate.

## Exam Hacker
Exam Hacker addresses this gap in study resources and provides students a single resource to help them achieve their best on this particular exam while teachers can use the site to get resources to help them understand what to teach and how to teach it. The site is found here: [Exam Hacker](https://tony-albanese.github.io/ci-project-1/)

## Target User Group

This website is for both teachers and students of the International Baccalaureate's Diploma Programme Higher Level Computer Science course.

## UX Design

### User Stories
A User is a student or a teacher in the IB Diploma Programme Higher Level Computer Science course. Although these users have two different roles, their stories are the same.  

As a user, I want to:
* Understand the purpose of the site from the landing page.
* Have a well-organized summary of all the Computer Science exams
* Have an overview of how the Paper 3 Questions are structured
* Have some example questions to reinforce content
* Easily navigate throughout the site
* Access the material on a mobile screen, a tablet screen, or a larger screen with equivalent ease.
* Have an organized overview of resources whose structure is easily perceived
* Have a variety of different types of resources available
* Have a short summary of the resources available to help decide if it is what I need
* Easily distinguish between resource types
* Have pleasing overall visual experience with a color scheme that is consistent and easy to read.
* Have trust in the websites and feel safe using it

## Features

### Existing Features

- __Navigation Bar__
    - This navigation bar, located at the top of the page, contains links to the Home, Paper 3 Structure, Resource Gallery, and About pages. The bar is fully responsive. On larger screens, the elements are displayed horizontally. On smaller screens, they are arranged vertically.
    - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ???back??? button.
    - ![nav bar screenshot](assets/images/screenshots/navbar-A.png)
    > Easily navigate throughout the site

- __Landing Page Structure__
    - The landing page features a large hero image showing an illustration of happy young people. There is a overlay in a position of prominence that explains what the site is about.
    - The overlay has a call to action button that will take users directly to the exam resources page.
    > Understand the purpose of the site from the landing page.
    - ![screenshot of hero image and overlay](assets/images/screenshots/hero-with-overlay-B.png)
    - The landing page also has a section which summarizes information on the three exams. Each summary is formatted as a material card.
    > Have a well-organized summary of all the Computer Science exams
    - ![screenshot of material exam card](assets/images/screenshots/exam-material-card-C.png)

- __Exam Structure Page__
    - This focuses on the structure of Paper 3. There is a section for each of the four questions. The content in each section is consistently organized into three color coded areas: one for a description of the questions, one for how to respond, and one for example questions.
    > Have an overview of how the Paper 3 Questions are structured  
    > Have some example questions to reinforce content
    -![screenshot of exam structure content](assets/images/screenshots/exam-structure-D.png)
- __Resources Page__
    - The resources page contains a curated list of resources to help students prepare for Paper 3. Resources include videos, articles, summaries, and tutorials. Articles are longer pieces of text. Summaries present content in less depth. Tutorials focus on implementing a particular feature with code. Some resources are a mixture of these, and I made a best-fit judgement to fit them into just one category.
    ![exam resources](assets/images/screenshots/exam-resources-E.png)
    > Have a variety of different types of resources available
    - Each resource is presented on a Material Card. The card contains a title, the type of resource, a description, and a button which links to the resource. The resources all open in a new broweser tab.
    > Have a short summary of the resources available to help decide if it is what I need
    - There is also a hierarchy to the page structure. Each set of resources is organized into subsections which are keyed to subsections in the case study document. Students and teachers can therefor easily see how the resources are related and go them based on what they want to learn.
    > Have an organized overview of resources whose structure is easily perceived
    - Each card is color coded by resource type. There is a cartoon representing each resource type in the description area of the card. 
    > Easily distinguish between resource types  
    - ![material card for a resource](assets/images/screenshots/material-card-resource-F.png)  

- __Color Scheme__
    - The color palette was generated by uploading the hero image to coolers.co and using their automatic palette generator. The blue was used for header, footer, and buttons. The rgb(176, 45,16) was used when a dark color was needed for contrast. Accent colors were either white or rgb(242, 221, 211).
    - For the material cards and the exam structure pages, related pastel colors were used since these had to be gentler in order to not ruin the contrast with the text.
    - The pictures used in the background of the resource material cards were chosen becuase their colors were similar to those of the hero image and simulataneously not too harsh. I used a color picker to generate colors for the header areas of these cards so that there would be consistency within similar cards but contrast between different ones. 
    > Easily distinguish between resource types  
    > Have pleasing overall visual experience with a color scheme that is consistent and easy to read  
    -![color palette](assets/images/screenshots/palette-G.png)  
    

- __Material Card__
    - Cards based on Google's Material Design specification are used for both the exam summaries and resource pages. These are a common design element in web development and they intuitively structure related information. This was a natural choice to organize this related content.
    
- __Footer__
    - The footer section will contain discaimers ensuring that students udnerstand that this site is not endorsed by the IB nor is there any gurantee as to the accuracy of the content.
    - Attribute credit for images used. The images are used legally, but their creators require attribution on the page they are used in. The footer is an appropriate place for this. The content creators provide the link to use for attribution in the page.
    > Have trust in the websites and feel safe using it
    ![screenshot of footer](assets/images/screenshots/footer-H.png)

- __Images__
    Images were chosen to have gentle, pleasing colors that are not distacting and yet coordinated.
    Images were chosen to relate to the content they are placed with. 
    
    #### Landing Page Images
    An illustration of happy students was used as the hero image in order to project what the website is ultimately trying to acheive, happy students.
    #### Exam Structure Page Images
    + An illustration of head with gears was used for Question 1 because these are memorization questions
    + An illustration of lego blocks was used for Question 2 because this is an application quetion. Legos seemed a good metaphor.
    + An illustration of a pencil was used for Question 3 because these questions require a more extended response.
    + An illustration of an essay was used for Question 4 because this is an essay question.
     ![essay image](assets/images/original-images/essay.png)  

    #### Exam Resources Page Imagees
    + An illustration of an article was used for article resources
    + An illustration of a presenter was used for tutorial resources since this implies instruction.
    + An illustration of a director's scene cutter with the play button was used for image resources.
    + An illustration of a report was used for summary type resources since reports imply summaries.
    >Have pleasing overall visual experience with a color scheme that is consistent and easy to read.
    ![article image](assets/images/original-images/article.png) 

- __Responsive Design__
    - To keep the layout responsive, CSS Flexbox and CSS Grid layouts were used to layout more complicated elements such as the material cards or the exam
    structure section. These layouts devices make it easy to rearrange the layout elements based on screen size. Most of the time, these elements respond naturally to changes in screen size and position the child elements properly.
    - CSS media queries were used to adjust for the most common screen size breakpoints. The breakpoints used are: 425px, 768px, 1024px, and 2600px
    > Access the material on a mobile screen, a tablet screen, or a larger screen with equivalent ease.

### Technology Used ###
* HTML
    * The site uses HTML5 to structure the page elements.
* CSS
    * The site uses pure CSS3 to style the HTML elements. No libraries were used.
* [GitPod](https://www.gitpod.io/)
    * Gitpod is a workspace that is closely integrated with GitHub. I used the IDE in their workspace (which is a version of VS Code) to code the project and 
    push commits to GitHub. The idea of using GitPod is that it provides a standardized development environment that is easy to share.
* [GIMP](https://www.gimp.org/)
    * GNU Image Manipulator Program. This powerful image editor was used to crop, scale, and adjust opacity of images.
* [Google Fonts](https://fonts.google.com/knowledge)
    * Three fonts, Heebo, Quicksand, and Nunito Sans were used in the site. They are available from Google Fonts.
* [Fontawesome](https://fontawesome.com/)
    * The icons on the landing page in the exam cards were from Fontawesome. I used the freely available font kit.
* [Coolers.co](https://coolors.co/)
    * I used their palette generator to generate the colors from the hero image using their free tool.
* [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/)
    * Using Firefox Developer Edition from Mozilla helped me diagnose layout and CSS problems as well as test differnt screen sizes. 


### Features left to implement
Without JavaScript, the site is necessarily static. the following features would be benefecial to add:
* A sidebar on the exam structure page would be useful to navigate through the sections and to let users know their location on the page.
* An About page to display the author's qualifications. This would increase trust in the site's content.
* A timed sample exam to let students know what they can experience. The sample exam responses could be sent to their teachers for commentary.
* A rating system for users to rate the quality of the resources. 
## Testing

### Development Testing
Throughout the development of the project, testing was performed. As elements were added or a CSS style was applied, the behavior was checked in the Firefox Developer Edition web browser. There are many instances where the behavior that was desired and the behavior that was achieved were not the same. Sometimes it was a misunderstanding of how the CSS properties worked and sometimes it was from typos and coding mistakes. There are too many to list here. I will give a few key examples to give a sense of how the testing phase during development was carried out.

#### Deploying a Local Server
To deploy the website locally for debug and design purposes, I opened a terminal and launched a python server by entering:

***
python3 -m http.server
***
Then one can click on the PORTS tab and open port 8000 to see the local webserver address running on GitPod's servers. This is private by default. To open it to other browsers, one can click on the lock icon to open the port to any traffic. This is how I could test my website on different browesers before deployment.

#### Some Examples
I started each page by marking up the content with HTML that best matched my designs. After adding basic styling I would run the markup through the validator. The validator caught several key errors.
+ I had misused the h1 element. I had h1 elements nested under h2 elements etc. The validator gave me a warning that this might confuse screen readers' navigation. I therefore had to refactor my html and adjust my CSS targets. 
+ The validator also caught several stray tags.
+ The validator also threw an error when I tried to make a button by nesting a button inside an anchor elmement (to make the button open a link without javascript). This forced me to wrap the anchor in a div and style the div.
+ Another peculiar error was that one two of the pages the nav bar was slightly different sizes which caused it to shift slightly when the user navigated. This was extremely jarring, even though the shift was small. Using the inspector on the Mozilla developer browser allowed me to compare each elment, its container, and styling side by side. The inspector helped me locate the error by showing the sizes of the navs were different. It turns out div that was placed inside an anchor rather than the other way around was causing the sizing issue.
+ Placing the buttons on the resource cards was particularly challenging. The inspector pointed out I was using the wrong positioning commands based on the type of container it was. 
+ Of particular use was the breakpoints for responsive layout. After imeplementing some layout declarations in CSS, I could test them immediately on different screen sizes and adjust accordingly. For example, this is how I found that the headers in the sections on the pages were overalpping on even mid-size tablet screens. I therefore added a media query to adjust the font size to avoid the wrapping. 

### High Level Testing
High level testing was performed. The accuracy of links and navigation was tested for proper functionality. Website layout responsiveness was tested on the Chrome, Firefox, Opera, and Safari web browsers running on laptops. The website was also tested on a real Android device (Motorola G6+). The testing performed can be found in the following document whose size prevents clear reading here.

[Testing Table pdf](assets/documents/Project%201%20Test%20Cases.pdf)

### Validator Testing
All Pages were run through the [W3C HTML Validator](https://validator.w3.org/) and showed no errors.  
CSS Stylesheet was run through the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/validator) and showed no errors.  

## Version Control Strategy
Git was employed in this project and the project code hosted on [GitHub](https://github.com/). I used branches in order to keep the main branch as "pure" as possible. The strategy was to have each branch dedicated to one feature or fix. For example, coding the landing page or coding the structure page. I did not always stick to this strategy. There is a branch called re-design that has far too many commits. Ideally, these would be broken down further so that each branch is self explanatory as to what it is responsble for. Once I was satisfied at a particular stage of a branch, I would navigate to GitHub, click on my repository, select the branch, and create a pull request. GitHub would then check if there are no conflicts and indicate if the branch could be merged into main. (One can choose which branch to merge into.) Once the pull request is created, I navigated down, wrote a comment, and clicked on the green Merge button and the commits would be merged into the main branch.

I tried to keep commits as atomic as possible - focusing only one one element or feature at a time. This was not always the case, but most of the commits are realtively small changes.

### VCS in the GitPod IDE
To make a commit, I clicked on the branch icon in the sidebar of the ide. There, one could see all the files that had changed since the last commit. To stage commits, I clicked on the plus icon next to the file that I wanted to stage. If I thought changes in different files should be commited together, I added multiple files. Occasionaly, after adding a bug or a breaking change, I would discard my changes by clicking in the left curly arrow icon. I then added a commit message in the textfield at the top of the sidebar which was as descriptive and brief as possible. I then clickd on the Commit button. To push, I clicked on the three dot icon and selected push.
## Deployment

### Project Creation
* The project was started by navigating to the [template] and clicking 'Use this template'. Under Repository name I input ci-project-1. I then navigated to the new [repository](https://github.com/tony-albanese/ci-project-1). I then clicked on the GitPod button which set up a GitPod workspace.
* To work on a project, navigate to [GitPod](https://www.gitpod.io/) and click on Dashboard which will navigate to the Workspaces. A workspace is where the project lives. Click on workspace and the VS Code IDE is launched in browser. (There is an option to work on the desktop.)

### Using Github Pages
1. Navigate to the GitHub [Repository:](https://github.com/tony-albanese/ci-project-1)
1. Click the 'Settings' Tab.
1. Scroll Down to the Git Hub Pages on the left panel.
1. Select Deploy from a Branch
1. Select 'main' as the source.
1. Click the Save button.
1. Click on the link to go to the live deployed page.

## Credits
### Content
The information about the exam schedule was taken from [IBO](https://www.ibo.org/programmes/diploma-programme/assessment-and-exams/exam-schedule/) which is the IB's website. The exam weightings and times are taken from the IB DP Computer Science courseguide.

The content on the Exam Structure page is written entirely by me.
### Media
The hero image was taken from [freepik.com](https://www.freepik.com/free-vector/college-university-students-group-young-happy-people-standing-isolated-white-background_21852399.htm#query=happy%20student&position=27&from_view=keyword) and is free to use with citation on the page. They provide the citation link to use.
<br>
The icons used on the landing page in the exam information card are from [Fontawesome](https://fontawesome.com)
<br>
The images used on the both the exam structure page and the resources page came from [Flaticon](https://www.flaticon.com) and are free to use with citation on  the page. They provide the citation link to use.
<br>
The ideas for a material card design were based on this article by Abbey Fitzgeralnd on her [blog](https://getflywheel.com/layout/flexbox-create-modern-card-design-layout/)
<br>
The CSS code to make the hover animation effect on the cards in the resources page was taken from this [codepen](https://codepen.io/sdthornton/pen/wBZdXq)