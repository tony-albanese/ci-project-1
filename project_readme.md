<!-- 
The following are the MINIMUM sections needed in the README.
-->
# Milestone Project 1

## Purpose
This website is for students enrolled in the International Baccalaureat's Computer Science program who wish to master the third examination paper which focuses on a case study. Although the strucure of the exam remains unchanged, the questions change each year with a new case study. Therefore, students cannot rely on past papers to help them learn content. They must understand how the paper is strucutred and be able to anticiapte what might be asked of them in order to be well prepared.

There are currently limited resources avaialble for students. There are a few YouTube videos that address the content, but none that I have found that address the structure of the paper. Nor do any of these resources address how students can frame their responses to maximize their marks.

There is really only one website that is dedicated to DP Computer Science Paper 3 - [IB CompSci-Hub](https://ib.compscihub.net/paper3).  The only thing available is a generic description of the what the paper is about.

Finally, the paper requires students to do much research in preparation. Students have complained that they must spend a lot of time searching through the internet to find material. Although some individual research is expected, students have several subjects to study for and a curated list of revision sources would be helpful.

The teachers of this course are also included. The case study is made known to them as the same time as the students. Therefore, teachers could also use this website to save precious time in looking for resources for their students. 
## Paper Hacker
Paper Hacker addresses this gap in study resources and provides students a single resource to help them achieve their best on this particular exam while teachers can use the site to get resources to help them understand what to teach and how to teach it.

## Target market

This website is for both teachers and students of the International Baccalaureate's Diploma Programme Computer Science course.

## UX Design

### User Stories
A User is a student or a teacher in the IB Diploma Programme Computer Science course.
As a user, I want to:
* Understand the purpose of the site from the landing page.
* Have a well-organized summary of all the Computer Science exams
* Have an overview of how the Paper 3 Questions are structured
* Have some example questions to reinforce content
* Easily navigate throughout the site
* Access the material on a mobile screen, a tablet screen, or a larger screen.
* Have an organized overview of resources whose structure is easily perceived
* Have a variety of different types of resources available
* Have a short summary of the resources available to help decide if it is what I need
* Easily distinguish between resource types
* Have pleasing overall visual experience with a color scheme that is consistent and easy to read.
* Have trust in the websites and feel safe using it

## Features
<!-- 
Feature name
A description about the feature and
how it works
Screenshot image of the feature
-->´
### Existing Features

<!--Maybe add color scheme as a feature.-->
- __Navigation Bar__
    - This navigation bar, located at the top of the page, contains links to the Home, Paper 3 Structure, Resource Gallery, and About pages. The bar is fully responsive. On larger screens, the elements are displayed horizontally. On smaller screens, they are arranged vertically.
    - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.
    > Easily navigate throughout the site

- __Landing Page Structure__
    - The landing page features a large hero image showing an illustration of happy young people. There is a overlay in a position of prominence that explains what the site is about.
    - The overlay has a call to action button that will take users directly to the exam structure page.
    > Understand the purpose of the site from the landing page.
    - The landing page also has a section which summarizes information on the three exams. Each summary is formatted as a material card.
    > Have a well-organized summary of all the Computer Science exams

- __Exam Structure Page__
    - This focuses on the structure of Paper 3. There is a section for each of the questions. The content in each section is consistently organized into three color coded areas: one for a description of the questions, one for how to respond, and one for example questions.
    > Have an overview of how the Paper 3 Questions are structured
    > Have some example questions to reinforce content

- __Resources Page__
    - The resources page contain a curated list of resources to help students prepare for Paper 3. Resources include videos, articles, summaries, and tutorials. Articles are longer pieces of text. Summaries present content in less depth. Tutorials focus on implementing a particular feature with code. Some resources are a mixture of these, and I made a best-fit judgement to fit them into just one category.
    > Have a variety of different types of resources available
    - Each resource is presented on a Material Card. The card contains a title, the type of resource, a description, and a button which links to the resource. The resources all open in a new broweser tab.
    > Have a short summary of the resources available to help decide if it is what I need
    - Each card is color coded by resource type. There is a cartoon representing each resource type in the description area of the card. 
    > Easily distinguish between resource types
- __Color Scheme__
    - The color palette was generated by uploading the hero image to coolers.co and using their automatic palette generator. The blue was used for header, footer, and buttons. The rgb(176, 45,16) was used when a dark color was needed for contrast. Accent colors were either white or rgb(242, 221, 211).
    - For the material cards and the exam structure pages, related pastel colors were used since these had to be gentler in order to not ruin the contrast with the text.
    - The pictures used in the background of the resource material cards were chosen becuase their colors were similar to those of the hero image and simulataneously not too harsh. I used a color picker to generate colors for the header areas of these cards so that there would be consistency within similar cards but contrast between different ones. 
    > Easily distinguish between resource types
    > Have pleasing overall visual experience with a color scheme that is consistent and easy to read

- __Material Card__
    - Cards based on Google's Material Design specification are used for both the exam summaries and resource pages. These are a common design element in web development and they intuitively structure related information. This was a natural choice to organize this related content.
    > 

- __Footer__
    - The footer section will contain discaimers ensuring that students udnerstand that this site is not endorsed by the IB nor is there any gurantee as to the accuracy of the content.
    - Attribute credit for images used. The images are used legally, but their creators require attribution on the page they are used in. The footer is an appropriate place for this.
    > Have trust in the websites and feel safe using it

- __Images__
    - Images were chosen to have gentle, pleasing colors that are not distacting and yet coordinated.
    - Images were chosen to relate to the content they are placed with. 
    
    #### Landing Page Images
    An illustration of happy students was used as the hero image in order to project what the website is ultimately trying to acheive, happy students.
    #### Exam Structure Page Images
    + An illustration of head with gears was used for Question 1 because these are memorization questions
    + An illustration of lego blocks was used for Question 2 because this is an application quetion. Legos seemed a good metaphor.
    + An illustration of a pencil was used for Question 3 because these questions require a more extended response.
    + An illustration of an essay was used for Question 4 because this is an essay question.
    #### Exam Resources Page Imagees
    + An illustration of an article was used for article resources
    + An illustration of a presenter was used for tutorial resources since this implies instruction.
    + An illustration of a director's scene cutter with the play button was used for image resources.
    + An illustration of a report was used for summary type resources since reports imply summaries.

>Have pleasing overall visual experience with a color scheme that is consistent and easy to read.
- __Responsive Design__

### Features left to implement
Without JavaScript, the site is necessarily static. the following features would be benefecial to add:
* A sidebar on the exam structure page would be useful to navigate through the sections and to let users know their location on the page.
* An About page to display the author's qualifications. This would increase trust in the site's content.
* A timed sample exam to let students know what they can experience. The sample exam responses could be sent to their teachers for commentary.
* A rating system for users to rate the quality of the resources. 
## Testing
<!--A section on testing different screen sizes would be appropriate. -->
### Validator Testing
### Unfixed Bugs

## Deployment

## Credits
w3schools for info on layout ideas
CSS Grid and Flexbox
Scribna for design principles
Any image creating software, Canva, etc
Meteral Card
Drop shadow
### Content
### Media

<!-- 
Better would also be a section on UX/UI.
The sections here should be:
Site Goals
Technologies used
Design choices
User stories
Wireframes
Database structure(PP3, PP4, PP5)
Anything else you want to add that relates to UX/UI
-->