# June-2024-Hackathon
- StIgma Free is an app to read and interact related to sexual health, the first version of the app will be related to sexually transmitted diseases.
- You will be able to read about the diseases, be able through thoughtfully choosen question see if you are at a risk of having a disease and recommended measures.
- You will be able to be anonymous or register to get more help, you will be able to get suggestions related to both health professionals and tests, but we are not a doctors clinic so we will not suggest treatments.

<img src="assets/images/amiresponsive.png" alt="Responsive Screens">

## Meet the Development Team
* [Jad Nehmeh](https://www.linkedin.com/in/jnehmeh/)
    * Scrum Master, Code Institute Alumni.*
* [Johan Plym Arkert](https://www.linkedin.com/in/)
    * Code Institute Student.*
* [Stephanie Bell](https://www.linkedin.com/in/stephanie-bell-529a362b/)
    * Code Institute Student.*
* [Amir Shkolnik](https://www.linkedin.com/in/amirshkolnik/)
    * Code Institute.*
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

How STD Free fills the needs:
- You can see the coloured tea on the pictures right at the landing page and also on the Contact Form.
- About Tea has some short information about the different coloured tea.
- The Contact Us page makes it possible to contact us.
- Easy to reach everything form the header and you can find our social media in the footer, you also see the footer all the time.


### Business Goals
The Business Goals are:
- Spread awareness of the more uncommon tea colours.
- Get in touch with other tea drinkers that are not satisfied with your normal tea.
- If enough people will be aware the bigger chance that you will find the more rare tea in your city.

### User Stories
1. As a curious tea drinker I expect to find out about different kind of tea.
0. I expect to get in touch with other people with my interest in more rare tea colours.
0. I expect to be able to have a reference so I can spread awareness myself


### Existing Features

- __Header__
  - Header has a menu with a nav bar or text on bigger screens and the website name in h1.

<img src="assets/images/header.png" alt="Header">

- __Navigation Bar__

  - The navigation bar can be found on all 3 pages and is fully responsive, it will turn between a bar or buttons depending on the size of the screen.
  - The bar will be visible even if you scroll down. 

<img src="assets/images/navbar.png" alt="Nav bar">

- __The landing page images__

  - The landing page or "Home" has 8 different coloured tea on it, with 1-2 pictures in a row depending on screen size and it is fully responsive in image size also. 
  - This page will make the visitor see all kind of colours on tea that they might not know that it existed.

<img src="assets/images/landingpage.png" alt="Landing Page">

- __About Tea__

  - About Tea page will give a short description of the different coloured tea. 
  - I have put different coloured background behind every div related to a specific tea colour, it should be the same main colour as the tea but with a more friendly palette. 

<img src="assets/images/abouttea.png" alt="About Tea">

- __Contact Us__

  - The Contact Us page has a contact form and a background picture that is fully responsive. 
  - The form has a background with an opacity to make it see through while still making the text easy to read. 

<img src="assets/images/contactus.png" alt="Contact Us">

- __The Footer__ 

  - The footer can always be seen and has logos with links to Facebook, YouTube, Instagram and X. 
  - The footer is both responsive and all the links works.

<img src="assets/images/footer.png" alt="Footer">

### Thoughts behind my choices

- I wanted it to be easy with few choices, 1 to add workout and 2 to exit the app.
- I wanted all 4 inputs to be connected to each other and therefore appear when previous is filled in.
- I decided that Exercise should only have limitation on amount of characters and that I don't want it empty, so a value always exist even if
it's just a space, it is still a real value, I didn't want to limit any kind of characters because some people might want to have a number or a
special sign, even a space might be something you want but I want the user to atleast be active in choosing the space.
- For sets, reps and weight I am forcing a number, because it must be a number even if it's 0, for example weight 0 can be your bodyweight, while
0 reps could be that you can't complete a whole rep and 0 sets that you don't want to count it as a set, I don't think minus is possible on the
other hand in strenght training so therefore all minus numbers will become plus in the worksheet.
- The Google Sheets is used so you can store your data.


### Google Sheets

- Data is uploaded to Google Sheets https://docs.google.com/spreadsheets/d/1I0pcPtlLThLbg1K50S_jZvfNzl-dlxeSda_ch4YiTQI/edit#gid=0 
- I added data for 2 exercises so it is possible to see data before it is testet by Code Institute, so I would think that it will be more exercises
added in the future by external parties.

<img src="assets/images/google_sheets.png" alt='Google Sheets'>


### Features Left to Implement

- I wanted to make an event information, also to get links from every picture on Home to the correct line in About Tea, make buttons change colour when marked, creating a couple of icons and maybe something more that I haven't thought about.

## Testing 

I have tested all links and buttons including navbar and they all work, the form also work and requires an email in email field, one of the radio buttons and the name fields filled in, but checkbox is optional.
I have tested on Chrome, Firefox and Edge without a problem, checked on many different sized from about 280p to 2000 px wide and 400px to about 2000 px high and didn't find any problems with the responsiveness.


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

- Both got code and got inspired by Code Institutes Love Running Project and Coders Coffeehouse Project, including header and nav-menu.
- Also got help, inspiration and support from my mentor Rory Patrick and help with code from a few Tutors at Code Institute.
- Got inspiration and some help from our Slack Team Group especially Lorenz.
- Template for this README is taken from Love Running and from my mentors project Horizon.


### Content 

- Information is taken from tea pages and Wikipedia during the years.
- All html and css was taken from the Code Institute education, big part from Love Running, Coders Coffeehouse and their Tutors
- The icons in the footer and the menu-bar were taken from [Font Awesome](https://fontawesome.com/)

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