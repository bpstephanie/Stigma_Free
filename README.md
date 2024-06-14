# June-2024-Hackathon
- StIgma Free is an app to read and interact related to sexual health, the first version of the app will be related to sexually transmitted diseases.
- You will be able to read about the diseases, be able through thoughtfully choosen question see if you are at a risk of having a disease and recommended measures.
- You will be able to be anonymous or register to get more help, you will be able to get suggestions related to both health professionals and tests, but we are not a doctors clinic so we will not suggest treatments.

<img src="assets/images/amiresponsive.png" alt="Responsive Screens">

## Meet the Development Team
* [Jad Nehmeh](https://www.linkedin.com/in/jnehmeh/)
    * Scrum Master, Code Institute Alumni.*
* [Johan Plym Arkert](https://www.linkedin.com/in/johan-plym-arkert/)
    * Code Institute Student.*
* [Stephanie Bell](https://www.linkedin.com/in/stephanie-bell-529a362b/)
    * Code Institute Student.*
* [Amir Shkolnik](https://www.linkedin.com/in/amirshkolnik/)
    * Code Institute Student.*
* [Sophie Tigerholm](https://www.linkedin.com/in/)
    * Code Institute Student.*
* [Alexander Åberg](https://www.linkedin.com/in/alexander-åberg)
    * Code Institute Student.*

---
**TABLE OF CONTENTS**
* [USER EXPERIENCE](#UX)
    * [Visitor Goals](#visitor-goal)
    * [Business Goals](#business-goals)
    * [User Stories](#user-stories)
* [Existing Features](#existing-features)
    * [Page Layouts/Features](#page-related-1)
    * [Page Layouts/Features](#page-related-2)
    * [Page Layouts/Features](#page-related-3)
    * [Page Layouts/Features](#page-related-4)
    * [Page Layouts/Features](#page-related-etc.)
* [Thoughts behind our choices](#thoughts-being-our-choices)
* [Database](#database)
* [Features Left to Implement](#features-left-to-implement)
* [Testing](#testing)
    * [Validator Testing](#validator-testing)
    * [Unfixed and fixed Bugs](#unfixed-and-fixed-bugs)
* [Quality Score through Google Devtools Lighthouse](#quality-score)
* [Deployment](#deployment)
* [Credits](#credits)
* [Content](content)
* [Media](#media)
* [Wireframe](#wireframe)
* [Diagram](#diagram)
* [Technologies Used](#github-projects)
* [Colours & Text](#colours-text)
* [Agile](#agile)
* [Kanban](#kanban)
* [Future Development, Iteration and Implementation](#future-development-iteration-and-implementation)
* [Technologies Used](#technologies-used)
    * [Languages Used](#languages-used)
    * [Frameworks Used](#frameworks-used)
    * [Databases Used](#databases-used)
    * [Libraries and Packages Used](#libraries-and-packages-used)
    * [Programmes and Applications Used](#programmes-and-applications-used)
* [Data Structure](#data-structure)

---


# UX
### Visitor Goals
The expected visitor is:
- Visitors that wants to understand more about sexual health and sexual transmitted diseases.
- Visitors that believe that they or someone else has a sexual transmitted disease.
- Visitors that wants to get a suggestion about the next step for their sexual transmitted diseases

Visitors goals are:
- Read facts about the sexual transmitted diseases.
- Go through the quiz to strenghtening or weakening the belief they or others are affected by a sexual transmitted disease.
- Get suggestions what to do including tests and contacting health professionals.

How STIgma Free fills the needs:
- You can get information about different infections.
- You can do a quiz to find out if you have an increased risk of being infected.
- The page is easy to use to get the information you need and you get recommendations to get tests or contact health professionals.


### Business Goals
The Business Goals are:
- Spread awareness of sexually transmitted infections judgement free.
- Get people to be able to contact our partners in the helath care industry.
- If enough people will be aware the bigger chance that we will eradicate the infections.

### User Stories
1. As a person with an active sex life I would want to protect my sexual health.
0. I expect to be able to find out if I am in a risk of having an STI or not.
0. I will be able to read up on STI's to prevent it from spreading to me.


### Existing Features

- __Header__
  - Header has a menu with a nav bar or text on bigger screens and the website name in h1.

<img src="assets/images/header.png" alt="Header">

- __Navigation Bar__

  - The navigation bar can be found on all pages and is fully responsive, it will turn between a bar or buttons depending on the size of the screen.
  - The bar will be visible even if you scroll down. 

<img src="assets/images/navbar.png" alt="Nav bar">

- __The landing page images__

  - The landing page or "Home" has a questionnare and some short information about the STI's with a button on each to read more, which will take them to the correct section in the info page. 

<img src="assets/images/landingpage.png" alt="Landing Page">

- __Info__

  - Info has information about different sexually transmitted infections.

<img src="assets/images/abouttea.png" alt="About Tea">

- __Team__

  - The Team page has information about the team, with pictures, short quotes and links to LinkedIn and GitHub.

<img src="assets/images/contactus.png" alt="Contact Us">

- __The Footer__ 

  - The footer has contact information and a trademark.

<img src="assets/images/footer.png" alt="Footer">

### Thoughts behind our choices

- We wanted to make an inclusive and stigma free site for sexually transmittes infections.
- We used rainbow related colours in a more pastell version to show that we accept everyone and
that we don't judge and the pastell version is to make it friendlier and more open to the eyes.
- Our direction to LGTBQI+ is because the community is more stigmatized and therefore less likely
to find out about infections in time.


### Google Sheets

- Data is taken from https://docs.google.com/spreadsheets/d/1WbLvIHAxbtCMGZuvHieJsoPTi4rfxFQwe68zECg8iXQ/edit?gid=0#gid=0
- In the future we want to make the sheet connected to make updates easier

<img src="assets/images/google_sheets.png" alt='Google Sheets'>


### Features Left to Implement

- We have many ideas for the future, mainly to connect to partners.

## Testing 

-


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?showsource=yes&doc=https%3A%2F%2Falexanderaberg.github.io%2Fbattleship%2F#cl177c14).
- CSS
  - No errors but 1 warning were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Falexanderaberg.github.io%2Fbattleship%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv) it got validated as CSS Stage 3 +SVG, the warning I ignore because I want the color and background-color to be the same, because I don't want the text to be seen before clicking a square!
- JS
  - No errors was returned for JS, but 16 warnings, 8 undefined cariables and 3 unused variables when passing through the official [(Jigsaw) validator](https://jshint.com/) I will need to work on them in the future.
- Python
  - No errors were returned when passing through the official [PEP8 Python Validator](https://pep8ci.herokuapp.com/#).


<img src="assets/images/validator-html.png" alt='Validator html'>
<img src="assets/images/validator-css.png" alt='Validator css'>
<img src="assets/images/validator-js.png" alt='Validator js'>
<img src="assets/images/validator.png" alt='Validator Python'>

### Unfixed and fixed Bugs

- Solved all known bugs, except for the blue background behind the submit button in the form on the Contact Us page on phones (tested on iPhone 13 Pro), it looks correct in Google Dev Tools.
- I Had some issues with fixing the header and did it with the help of a tutor same thing with photos on larger screens which you can see in the css.
- I did much trial and error with forms, pictures, header and footer and went through many colours on About Tea until my mentor suggested that I use the tea colour as background which made it possible to have text and background fit together better, I also did choose black as background for menu bar and contact form, the contact form I still wanted to see the background through which I sorted with the help of opacity.
- I also got some help from my slack team for the header.

- I would say that the header is by far what I had biggest problems with and the responsivness on larger screens for images on home.

### Quality Score through Google Devtools Lighthouse

- Lighthouse testing on Chrome Incognito to prevent cookies and background cache to slow down.

<img src="assets/images/lighthouse-index-phone.png" alt="Lighthouse Index Phone">
<img src="assets/images/lighthouse-index-computer.png" alt="Lighthouse Index Computer">
<img src="assets/images/lighthouse-abouttea-phone.png" alt="Lighthouse About Tea Phone">
<img src="assets/images/lighthouse-abouttea-computer.png" alt="Lighthouse About Tea Computer">
<img src="assets/images/lighthouse-contactus-phone.png" alt="Lighthouse Contact Us Phone">
<img src="assets/images/lighthouse-contactus-computer.png" alt="Lighthouse Contact Us Computer">


## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 
  - You can either copy the link for Code or Open in a new repository or see the live version under Deployment to the right under github-pages.
  - In GitHub you can open every seperate file including html. css. images and even favicons and see the folder structure.
  - It is possible to check the commit history in github-pages under Deployment to the right

  - Link to the live version of the project can be found here: - https://github.com/AlexanderAberg/Different-Coloured-Tea.git

  - The app was deployed to GitHub pages and Heroku. The steps to deploy are as follows: 
  - Copy the repository from GitHub to your own GitHub to have it on your GitHub.
  - Create a new app in Heroku, name it and choose your region before pushing button to create app.
  - In the next page press settings, scroll down to Config Vars and pust the button, here you add CREDS in KEY and copy and paste everything inside creds.json to Value, 
  you also add another var and put in PORT in KEY and 8000 in VALUE.
  - You will now push Add buildpack just below Config Vars, there you choose Python and press the button to add it, you will get back to settings where you
  press button to add buildpack again to add another buildpack and choose nodejs and add it also, make sure to have Python above nodejs in settings by moving it if needed.
  - Now you go up to switch to Deploy in the tab and here you press the GitHub icon with the GitHub text to connect to GitHub and after that press Connect to GitHub button below.
  - You will get a name choice where you choose your GitHub and search for the correct respository and then press connect.
  - You will now be able to press Enable Automatic Deploys to make changes come automatically so do that, but press also Deploy Branch to get access already after about 30 seconds,
  after the 30 seconds give or take depending on your internet speed and computer you can press view and now you have access to use the app.
  - Now you will also be able to find the deployment in GitHub including all commits that was done after the deployment

  - Link to the live version of the project can be found here: - https://strength-workout-app-d0e61c3ce59a.herokuapp.com/ and to the gitHub page here : https://github.com/AlexanderAberg/strength-workout-app


## Credits 

Favicon from  <a href="https://www.freepik.com/icon/herbal-tea_10812632#fromView=search&page=1&position=54&uuid=24e50b5d-d56e-4b71-a971-f5a242ddc937">Icon by Satawat Anukul</a> and generated through https://favicon.io/favicon-converter/ 

- STI information from 1177, RFSL, NHS and internetmedicin.se


### Content 

- STI information from 1177, RFSL, NHS and internetmedicin.se


### Media

- The photos used on the home is from https://www.freepik.com black tea from https://www.freepik.com/author/8photo red and blue tea from https://www.freepik.com/author/azerbaijan-stockers Ooolong tea from https://www.freepik.com/author/jcomp green, white, yellow tea and icon for Favicon from the site owner and purple tea from https://bluetea.co.in/blogs/news/purple-tea-the-perfect-floral-tea# I have permission to use all of them for this project, and converted Favicon here https://favicon.io/favicon-converter/ 
- Responsive mockup from https://ui.dev/amiresponsive?url=https://alexanderaberg.github.io/Different-Coloured-Tea/ 

### Wireframe

- Used Balsamiq for Wireframe, the Wireframe has some content that is missing in the project because of lack of time, see also Features Left to Implement in this README, the pictures became also better than expected so therefore will wireframe for home have more images on row and different setup than the actual project also the wireframe is not to scale especially computer.

<img src="assets/images/wireframe-phone.png" alt="Wireframe for Phone">
<img src="assets/images/wireframe-tablet.png" alt="Wireframe for Tablet">
<img src="assets/images/wireframe-computer.png" alt="Wireframe for Computer">

### Diagram

- Used Lucid Chart for a diagram of how the app is supposed to be built up.

<img src="assets/images/lucid-chart.png" alt='Lucid Chart'>

### Technologies Used

- HTML - For how the website with the pages is built and planned 
- CSS - For all the styling
- Images  - Freepik for Pictures except for purple tea that I got from bluetea mentioned in media
- Fonts - From Google Fonts
- Icons - From Fontawesome 
- Education Tool- From the people at Codeinstitute
- Wireframe - From Balsamiq 
- Favicons - Icon from freepik and converted with Favicon.io
- Mockup - Generated at amiresponsive 
- Colours I mostly tested what fit together and got help from Lighthouse in Google dev tools to see if I should adjust further 
- Google Devtools to check responsiveness and to check Lighthouse for Accessibility
- GitHub for storing the project and deploying it
- Gitpod for project development

### Colours & Text

- Did choose dark colours for header, footer, menu etc. to fit with the pictures and wanted the background of the h2 in Home and the form in Contact Us to have opacity so you can see through without covering the images completely.
- The colour for About Tea is pastel colour to make it friendlier to the eyes compared to sharp colours, the white and black doesn't really exist as pastel so I tried to make them friendlier also which you can see on the colours and in the css picture below.
- Used Font style that is seperate between the logo, h1 and h2 compared to h3 and text with backup font for browsers without the font, the text colour in general is supposed to fit very well with the background colours that is why the background colour for tea has white text except for black that instead has white text.

<img src="assets/images/colours.png" alt="Pastel Colours">
<img src="assets/images/colours.png" alt="Pastel Colours">