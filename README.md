# HIKE IRELAND

Milestone Project 3 - Backend Development - Code Institute 

## Demo 

A live demo can be found [here](https://hike-ireland-project.herokuapp.com/)

## UX 

### Strategy 

Hike Ireland - is as per the name a website with informaiton on Hikes around Ireland. It's a 
website that allows hikers, walkers, ramblers and everyone else in between to come together and 
share details on the wonderful hikes in Ireland. 

This website is for everyone that is looking for a simple, easy to 
understand and easy to navigate website with details on hikes in Ireland. This is achieved by 
having a simple, clear funcitonal easy to understand website. Visitors will want to come back 
time and time again to gather information, provide information and learn more about hikes all over Ireland. 

### User Stories 

#### Visitor Goals 

* As a visitor, I want to understand the main purpose of the site. 
* As a visitor, I want the site to be simple to navigate.
* As a visitor, I want to quickly find information about hikes. 
* As a visitor, I want register an account so that I can add, update, edit and delete information I have provided.  
* As a visitor, I want the site to be visually appealing.
* As a visitor, I want the sire to be accessible and responsive on all devices. 

#### Site owner goals

* As a site owner, I want this site to be responsive so that visitors can have a good experience on all devices. 
* As a site owner, I want visitors to find this site visually appealing.  
* As a site owner, I want visitors to enjoy and interact with the site.
* As a site owner, I want visitors to return to the site and provide information on hikes. 
* As a site owner, I want to create a community where hikers come together and share information. 

### Scope

* For users, the site owner wanted to create a website that acts as a one stop shop for details on 
hikes around the Country, currently there are no such sites where hikers, walkers etc can gather required information 
all in one place. 

### Structure 

* In order to meet the expectation of "Hike Ireland" users,  the website aims to stick to convention 
in its layout and architecture.

* There is a header  and footer section on each page, with a "Hike Ireland" heading. Clicking on this
 heading will take the user back to the landing page of the website and this is, as mentioned above, 
an expected and understood convention. 

* There is a Log In / Registration Feature which enabes users to create an account and create, update, edit and delete
hiking posts. 

* All elements of the website are easily discoverable and aim to ensure that the user can get to their desired destination within 
3 clicks. 

* The colouring, theme and terminology used throughout the website is consistent.

* The website is interactive and provides lots of feedback to the user. 

* The architecture of this website has been carefully considered with the user in mind and allows for ease of movement through the content. 

* Information on this section has been inspired by the information on [Code Institute](https://learn.codeinstitute.net/ci_program/diplomainsoftwaredevelopment)

### Skeleton 

All wireframes were created using [Balsamiq](http://balsamiq.com)

Please find full PDF versions of wireframes and sketches below:

* [Mobile Wireframe](https://github.com/MWatty/hike_ireland/blob/main/static/assets/wireframes/HIKE%20IRELAND%20-%20MOBILE.pdf)
* [Tablet Wireframe](https://github.com/MWatty/hike_ireland/blob/main/static/assets/wireframes/HIKE%20IRELAND%20-%20TABLET.pdf)
* [Desktop Wireframe](https://github.com/MWatty/hike_ireland/blob/main/static/assets/wireframes/HIKE%20IRELAND%20-%20DESKTOP.pdf)

### Surface 

#### Design 

 * The overall design of the website is  simple. The site owner wants the user to simply navigate and 
understand what is on offer without being inundated with information. Clear text and imagery are used to achieve this. 

#### Colour 

* A palette of Blacks, Greens, Greys and Whites are used throughout. The use of such colours is to relfect the green in the land and 
also to allow the imagery of the hikes to take centre stage. 

* When choosing the colours the [Colour Picker Tool](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Color_picker_tool) was used to assist.

#### Typography

* Mukta was chosen as this is a simple and unfussy font which will be clear and easy to read. 
This was chosen using [google fonts](https://fonts.google.com/)

* font-family: 'Mukta', sans-serif;

#### Images 

* All images used throughout the website have been carefully chosen to ensure the theme of the website is maintained throughout. 
Of course, users can upload their own images when adding posts which may lead to some differences in overall styling.  

### Final Project Variations 

#### Navigation Bar

* The navigation bar was amended from what was originally planned. 
* The style used is much more simplistic and there is no text and the search bat has been places underneath. 
* The reason for this is to keep the site clean and minimalist looking. 
* A home button was also added to the navigation to ensure that the user always has the option to return to the main landing page. 

#### Main Container Landing Page

* There was a slight deviation on the landing page initially it was planned to have 3 cards per row, but 2 cards were deemed to be more aesthetically pleasing that 2 and it allowed more space for the imagery to take centre stage. 
* A background image was also applied throughout the website playing on the theme and also streamlining the movement between pages. 

#### Footer 
 
* The footer was amended to be be more simplistic and more angular rather than having all items in a central position. 


#### Individual Hike Page 

* This was not included as it was deemed unnecessary and burdensome for the user, instead it was decided to use the card reveal to provide the information about the hikes that is required. It also allows for some user interactivity by clicking on the cards. 

#### Profile Page

* Within this page it was decided to follow through with the card format thus keeping a sense of familiarity for the user throughout. 

#### Edit Hike 

* The edit hike page was amended to mirror the add hike page allowing the user to edit any parts of the hike they wish to. 


## Features 

### Existing Features 

*	This website is responsive on all device 
*	There are interactive elements throughout the website 
*	This website is linked to a MongoDB database
*	Users have to log in or register to Add, Update and Delete Hikes. 

### Landing Page

* A navigation bar is, as expected, located across the top of the page, this notifies the user of the home page, log in and registration 
* There is a search function should the user wish to search for an hike by name or location. 
* There is also a card deck with details of the hikes that have been uploaded and the user can gather details from here. 
* The footer container links to social media and a copyright symbol. 

### Log In / Registration 

* These are standard simple log in / registration pages allowing the user to simply move navigate between each.

### Profile Page

* This page identified the user 
* Shows the hikes the user has added 
* A button on this page prompts the user to add more hikes 
* Also allows the user to edit or delete hikes taking them to an edit page or confirming a deletion should they wish to do so. 

### Add Hike 

* A form is is used here to gather information from the user, once complete this is uploaded to the maing landing page and the users profile. 

### Edit Hike 

* This is the same form format as above, although the fields have been populated with the information already inputted onto the system 

### Features left to implement

* An interactive map of Ireland showing the exact locations of the hikes 
* User reviews of the hikes
* Additional features such as what available in terms of facilities near the hikes i.e toilets, campgrounds etc 
* A shopping feature could be added 
* A weather feature of the current weather in each of the locations. 

## Technologies Used 

### Languages

* [HTML5](https://www.graycelltech.com/why-use-html-5/) was used as this is the latest Hypertext Markup Language and this is the standard language for describing the contents and appearance of Web Pages.

* [CSS](https://www.w3schools.com/css/css_intro.asp) is used to define styles for web pages, including the design, layout and variations in display for different devices and screen sizes.

* [JavaScript](https://www.w3schools.com/js/DEFAULT.asp) is used to program the behaviour of webpages.

* [Python](https://www.python.org/) is used to ensure interaction between the webpages and the database. 

### Libraries 

* [Materialize](https://materializecss.com/) is a design language that combines the classic principles of successful design along with innovation and technology. Google's goal is to develop a system of design that allows for a unified user experience across all their products on any platform.

* [Google-Fonts](https://fonts.google.com/) were used to style the website fonts and ensure they complimented each other.

* [Balsamiq](https://balsamiq.com/) used to create the wireframes. 

* [Font Awesome](https://fontawesome.com/) was used to add font icons to the website. 

* [JQuery](https://jquery.com/) was used to make the use of JavaScript on the website easier. 

### Version Control 

* [GIT](https://git-scm.com/) was used as version control in utilising [Gitpod](https://gitpod.io) to add code, commit and push to [GitHub](https://github.com).

* [Gitpod](https://gitpod.io) was used as this is an open source platform for automated and ready to code development environments that blends into your existing workflow.

* [GitHub](https://github.com) was used as a hosting platform for version control.

### Tools and Other Resources 

* [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools) was used to edit pages and diagnose problems quickly. 

* [Browserling](https://www.browserling.com/) was used for cross browser testing.

* [Am I responsive](http://ami.responsivedesign.is) was used to create a mock up.

* [Web Formatter](https://webformatter.com/html) used to correctly indent files. 

## Testing 

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project. 

* [WC3 Markup Validation Serivce](https://validator.w3.org/#validate_by_input) - [Initial Results with error](https://github.com/MWatty/hike_ireland/blob/main/static/assets/validation%20screenshots/HTML%20Validation1.png "Initial Results with error")
 & [Results with no errors](https://github.com/MWatty/hike_ireland/blob/main/static/assets/validation%20screenshots/HTML%20Validation%202.png "Results with no errors")

* [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) - [Results](https://github.com/MWatty/hike_ireland/blob/main/static/assets/validation%20screenshots/CSS%20Validation.png "Results")

JShint was used to detect errors and potential problems within the JavaScript Code. The only issues identified in JShint as per 
the results below related to the use of 'let' which are is available in ES6, this is not a cause for concern. 

* [JShint](https://jshint.com/) - [Results Screenshot](https://github.com/MWatty/hike_ireland/blob/main/static/assets/validation%20screenshots/JS%20Validation.png "Results Screenshot ")


### Testing User Stories from User Experience (UX) Section

#### Visitors 

 1. As Visitor, I want to understand the main purpose of the site. 

    1. Upon entering the site, users are greeted by the navigation bar with the title and lots of images, ensuring clarity on the purpose of the site, 
    2. The user has three options, explore the hikes that are already there or log in / register. 
    3. In a simple click the user can explore the hike information that is available. 

![Landing Page](https://github.com/MWatty/hike_ireland/blob/main/static/assets/website%20screenshots/Landing%20Page.png "Landing Page")


 2. As a visitor, I want the site to be simple to navigate.

    1. Upon entering the site, there are simple navigation options in the nav bar. 
    2. Everypage can be reached within 3 clicks. 
    3. The website is intuitive to the users needs and there is a flow to the navigation process. 

![Profile Page](https://github.com/MWatty/hike_ireland/blob/main/static/assets/website%20screenshots/Profile%20Page.png "Profile Page")

 3. As a visitor, I want to quickly find information about hikes. 

    1. Upon entering the site, there are cards on display with hike details. 
    2. Without logging in or registering users can discover details relating to the hink.
    3. Using the card reveal users can gather more in depth informaiton about the available hikes. 

![Hike Details](https://github.com/MWatty/hike_ireland/blob/main/static/assets/website%20screenshots/HIke%20Details%20.png "Hike Details")

 
4.  As a visitor, I want register an account so that I can add, update, edit and delete information I have provided. 

    1. Upon entering the site, the user has clear option to log in to their account. 
    2. New users also have the option to register their account.
    3. Once logged in / registered the user can update, edit and delete their hikes. 

![Log In  Page](https://github.com/MWatty/hike_ireland/blob/main/static/assets/website%20screenshots/Log%20In.png "Log In Page")


5.  As a visitor, I want the site to be visually appealing.

    1. Upon entering the site, the user is met with a beautiful abckground image, this is carried throughout the site. 
    2. Users can also add their own images to the site.  
    3. A pallette of greens are used throughtout to add to the attractiveness of the site and marry with the theme. 

![Profile Page](https://github.com/MWatty/hike_ireland/blob/main/static/assets/website%20screenshots/Profile%20Page.png "Profile Page")

6.  As a visitor, I want the sire to be accessible and responsive on all devices.

    1. The website has been designed to be responsive on all devices.  

![Ipad Page](https://github.com/MWatty/hike_ireland/blob/main/static/assets/website%20screenshots/Ipad.png "Ipad Page")



#### Site Owner 

1.  As a site owner, I want this site to be responsive so that visitors can have a good experience on all devices.

    1. The website has been designed to be responsive on all devices. 
    

![Iphone Page](https://github.com/MWatty/hike_ireland/blob/main/static/assets/website%20screenshots/Iphone%20.png "IphonePage")

2.  As a site owner, I want visitors to find this site visually appealing.  

    1. The users are met with beautiful imagery throughout the site. 
    2. There is also a colour theme throughout inclusive of fonts designed to be appealing to the user.  
   

![Delete Page](https://github.com/MWatty/hike_ireland/blob/main/static/assets/website%20screenshots/Delete%20HIke%20.png "Delete Page")

3.  As a site owner, I want visitors to enjoy and interact with the site.

    1. Users can utilise the search function. 
    2. Users can create and a profile to update, create and delete hikes.  
    3. Flash messages appear when users update, create or delete hikes all adding to the interactivity of the site.  

![Flash Page](https://github.com/MWatty/hike_ireland/blob/main/static/assets/website%20screenshots/Flash%20Message%20.png "Flash Page")

4.  As a site owner, I want visitors to return to the site and provide information on hikes. 

    1. In order to encourage users to return there is a log in function where they can view their own profile.  
    2. Users are also encouraged to register an account.  
    3. The simplicity of the forms aim to encourage returning to the site.  

![Edit Hike Page](https://github.com/MWatty/hike_ireland/blob/main/static/assets/website%20screenshots/Edit%20Hike.png "Edit Hike Page")

5.  As a site owner, I want to create a community where hikers come together and share information. 

    1. Upon entering the site, users are encourage to create an account with the aim of encouraging users to create hikes. 
    2. Users can also access all of the hikes created by other users.  
    3. Users can quickly get a snapshot of hikes and will be encourage by its simplicity of the add function to add their own hikes. 

![Add Hike Page](https://github.com/MWatty/hike_ireland/blob/main/static/assets/website%20screenshots/Add%20Hike%20.png "Add Hike Page")


### Further Testing

* The Website was tested on Google Chrome, Firefox, Opera Microsoft Edge and Safari browsers.
* A large amount of testing was done to ensure that all pages were linking correctly.
* Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.


#### Devices 

Tested the game functionality on the devices listed below: 

* Mac Book Pro 
* iPhone 11 
* Honor 10 
* Lenovo Laptop (Windows 10) 

#### Issues identified during testing 

* Label / Placeholder on the search bar was not fitting on screens below 320px created media query to remove label/placeholder. 

* 

### Features Tested 

## Deployment 

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://https://github.com/MWatty/Hike-Ireland)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
   - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com/MWatty/Hike-Ireland) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps.

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/MWatty/Hike-Ireland)
2. Locate the "Fork" Button and Click it. 
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/MWatty/Hike-Ireland)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

### Creating Collections in MongoDB

1. Login to your MongoDB account
2. Create a **cluster**
3. Create a **database**
4. Create required **collections** in the database named.

### Setting Up the Environment Variables
1. Create a file called **.gitignore** in the root directory of your project
2. Add the following text in your .gitignore file: **env.py**
3. Create a file called **env.py**. This will contain all your environment variables
4. Create your own personal secret key and password. In **env.py** add the following text and replace **YOURPASSWORD**, **YOUR-CLUSTER-NAME**, **YOUR-DATABASE-NAME** and **YOURSECRETKEY**    

### Run the App 
1. Open your terminal window in your IDE
2. Type in **python3 app.py** to run the app

### Heroku Deployment
1. Create a Heroku account
2. Create a new app and select your region
3. In the terminal window of your local IDE type **pip3 freeze --local > requirements.txt** to create a requirements.txt file. This file is needed so that Heroku knows which files needs to be installed
5. In the terminal window of your local IDE type **python app.py > Procfile** to create a Procfile. This file is needed so that Heroku knows which file is needed as its entry point to get the app up and running
6. In the terminal window of your local IDE type in **heroku login** or **heroku login -i** and fill in your heroku credentials and password
7. Commit all your files and type in the same terminal window **git push heroku master**. Now all your files are committed to Heroku
8. Go back to your Heroku account and go to **settings**
9. Click on **Reveal Config Vars** to reveal the keys and the values
10. Set the keys and values as follow:
    (**KEY: VALUE**)
    - IP: 0.0.0.0
    - PORT: 5000
    - MONGO_DBNAME: YOUR-DATABASE-NAME
    - MONGO_URI: mongodb+srv://root:**YOURPASSWORD**@**YOUR-CLUSTER-NAME**.2qobt.mongodb.net/**YOUR-DATABASE-NAME**?retryWrites=true&w=majority
    - SECRET_KEY: YOURSECRETKEY
11. Click on **Open app** in the right corner of your Heroku account, the application will open in a new window
12. The live link is available from the address bar

## Credits 

### Content 

* Content was written by the developer Maura Watkinson. 

### Code 

* Code on labelling of add hike page https://stackoverflow.com/questions/22720769/how-can-you-change-the-color-of-a-label-in-a-form

### Media 

### Other 
* <i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

### Acknowledgements 





