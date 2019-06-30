# ROAD RUNNER SOCIETY

I choose to create a presentation site for an association that I started 10 years ago with some of my friends. Its main activity is based in a rural area in the North of Romania called Valea Chioarului in Maramures County.
Road Runner Association has the mission to promote artistic and cultural experiment as a lifestyle and support sustainable and responsible development in the rural areas. Most of the association projects and actions focus on rural revival through educational, touristic and cultural events.

## UX

The site has a simple and logic structure and it is easy to navigate. I planned it more like a presentation site with a single call to action for the possibility of volunteering. Usually, people find out about Road Runner Society from other sources, even from friends or directly participating in one of the projects. That means that most of the users have a minimum knowledge about the association before entering the site.

### Structure and Design objectives

- to present the scope and mission of the association aswell as some of the fields of interest and activities

- to make a written and visual description of the area where the association developed most of its projects. Also, to show the impact that these actions had to Durusa village, its basecamp

- to provide description, details and status of the running projects

- to make a short brief of the most longevive project of the association with a 10 years history: Durusa Summerhills festival

### User Stories

- As a new visitor, I want to easily navigate and to find clear and simple written information doubled with visual representation.
- As a participant at the festival, I want to find out more about the association activity.
- As a company owner, I want to find out if my company's fields of interests are the same with the ones of the association and to make a first contact in order to start a collaboration.
- As a possible volunteer, I want to have a more general view of the association and a posibility to sign in for a volunteering session in one of their projects.

#### Wireframes

- [Mobile](https://ibb.co/album/dbdYLa)
- [Ipad](https://ibb.co/album/n0SSfa)
- [Desktop](https://ibb.co/album/bus4RF)

#### Mock-ups

- [Mobile](https://ibb.co/album/b38dmF)
- [Ipad](https://ibb.co/album/fTYYLa)
- [Desktop](https://ibb.co/album/iyLf0a)

## Features

### Existing features

At the top of each page, on the left, there is a logo linked to the Home page and on the right a responsive navigation bar with four buttons. For mobile devices I used a toggle button. At the bottom of each page there is a footer with two social links, contact details and copyright. On smaller than medium devices the items go one on top of each other.

#### Home

Home button contains the first page of the site. Content is structured in 3 parts. The first two consists in a picture each and text that describes the scope and mission of the association and makes a short introduction to the village. The third part is an album carousel with pictures from the village. On smaller than medium devices, content goes one on top of each other, starting with the picture.

#### Projects

Projects button contains information about three ongoing projects of Road Runner. Each of them is structured in a section that contains a represantative picture, name, text about, a project status with a progress bar and a button that opens a modal. Modal contains a form and it gives the oportunity to the user to apply for volunteering. On smaller than medium devices, each of elements of the section goes on top of each other in this order: image, text, project status, button.

#### Summerhills

Summerhills button contains information about the most succesfull project. It has three sections, first with a picture, title and some short description of the event. Also, here can be found a button with a link that goes to a separate site for the festival. Second and third sections contain a video each and a description text.

#### Contact

Contact button has a simple structure. It contains a screenshot for a map that shows the location of the village, contact details like adress, phone number and e-mail and a form contact.

### Features left to implement

- an alert that opens a page with the latest informations regarding projects
- a Shop page that will contain for sale items made by the members of the association. Money raised through this shop will support projects
- collecting information for the contact form inside contact page and modal
- interactive map
- posibility to switch into three other languages: romanian, german and french

## Technologies used

In this project I used:

- HTML (HyperText Markup Lanhuage)
- CSS (Cascading Style Sheets)
- [BootstrapCDN](https://getbootstrap.com)
- [GoogleFonts](https://fonts.google.com)
- [Fontawesome](https://fontawesome.com)
- [Git](https://git-scm.com)
- [VSCode](https://code.visualstudio.com)
- [jQuery](https://jquery.com)
- [popper.js](https://popper.js.org)

Other tehnologies used:

- [AdobeXD](https://www.adobe.com/ro/products/xd.html) for wireframes and mock-ups

## Testing

The code was checked with both of the following validators

- [W3CMarkupValidator](https://validator.w3.org)
- [W3CJigsawCSSValidator](https://jigsaw.w3.org/css-validator/)

The project was developed with the constant use of Chrome Developer Tools in order to ensure responsivness on all devices. The site functionality was contantly checked in the following browsers:

- Chrome
- Mozzila Firefox
- Opera
- Safari
- Internet Explorer 11

### Manual testing on elements and functionality of each page

1.Navbar
i.Visit home page from a bigger than medium device(md).
ii.Hover over each navbar buttons to see of the effects work.
iii.Click on each button to check if they have functionality and if they are linked to the correct page.
iv.Using Chrome Developer, alter the screen to smaller than medium sizes to see if the navbar is responsive.
v.Click on the toggler button to check if the dropdown menu activates.
vi.Hover on each button to see if the effects work.
vii.Click on each button to check if they have functionality and if they are linked to the correct page.
viii.On all screen sizes, click on logo to ensure that it is linked to the Home page.

2.

## Deployment

This site was developed using VScode, committed to git and pushed to GitHub with the built-in functionality in VScode. From there it was deployed to GitHub Pages from its GitHub repository.

### To deploy this page to GitHub Pages from its GitHub repository the following steps were taken

1. Logged into my GitHub account (<https://github.com/vladoprea).>
2. Go to Repository tab.
3. Click the repository called "road-runner-society"
4. Go to the "Settings" tab at the top of the page and click it.
5. Scroll down the "Settings" page to the "Github Pages" section.
6. In the "Sources" subsection select "Master Branch" from the drop-down menu currently labelled none. This refreshes the page and publishes the project.
7. Scroll down again to the GitHub pages to find a link to the deployed site.
8. The website is published here: (<https://vladoprea.github.io/road-runner-society/)>

### To run project locally

To clone this project from GitHub:

1. Follow this link to the Project GitHub repository
2. Under the repository name, click "Clone or download"
3. In the Clone with HTPPs section, copy the clone URL for the repository.
4. In your local IDE open Git Bash.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type git clone and then paste the URL you copied in Step 3.
7. git clone (<https://github.com/USERNAME/REPOSITORY)>
8. Press Enter. Your local clone will be created.

## Credits

### Media

- all the photos were taken from the Road Runner Society facebook page and are under the association copyright
- ARCA through Fazakas Miklos for the youtube video in the Summerhills page
- Road Runner Society has the copyrights for the vimeo video in the Summerhills page
- Texts from Home page and Summerhills page were taken from the (<https://summerhills.ro)> site which is property of Road Runner Society

## Acknowledgements

I have used many useful resources. Most importants are:

- [StackOverflow](https://stackoverflow.com)
- [W3Schools](https://w3schools.com)
- [CodeInstitute](https://codeinstitute.net)
- [Academind](https://www.youtube.com/channel/UCSJbGtTlrDami-tDGPUV9-w)
- [AnnaGreaves](https://www.youtube.com/watch?v=zDpCejbl1sU&feature=youtu.be)
- [UXDesign](https://uxdesign.cc)

I would like to thank :

- Maranatha Ilesanmi my mentor who guide me through this project and provided punctual, solid and useful feedback.
- [Slack](https://code-institute-room.slack.com/messages) comunity for providing solutions to every question I had.
