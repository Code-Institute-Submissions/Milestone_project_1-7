# Milestone Project 1
## Pulze Gaming League Responsive Website Project 
### Background 
This Milestone project creation is the last step of learning and study from the first three modules of the Full Stack Developer Course, HTML, CSS & User Centric Frontend Development, to build a mobile-first fully responsive website. In this case for the fictional company "Pulze". 

![alt text](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/screenshots/screenshot-hero.PNG "Hero-shot index.html")

The Website provides the user with the ability to look for tournaments, sign up for a specific day, region and game.

### Functionality 
The project uses the Bootstrap Framework combined with flex to create a multi-page fully responsive, Desktop-First approach Website. It is completely within the scope of the guidelines of the milestone requirements and does not use any back-end functions or  any custom javascript. With that in mind please note that although this website contains "forms" i.e. modals on the event.html and a contact form on contact.html they do not alert anyone that a sign up has been created and will not populate any server database.

Both forms hold data validation and all fields residing within are set to required ensuring information submitted is of the correct format.

The fonts used throughout the site were imported into the HTML of each page from Google Fonts and are called 'Roboto' and "Press Start 2p".

As described above, this project went outside the original brief and is based on the needs of a real-life local company and will be used to fulfill a considerable gap in their entry stake into the marketplace. Given this, the functionality of the website will evolve over time to incorporate a Merchandise store, interactive Video Tours, and Online bookings & payments

### Technologies Used
+ HTML ~ main Language used to structure the individual pages of the website.
+ CSS ~ styling language used to format and visually build upon the accompanying HTML.
+ [Bootstrap Framework](https://getbootstrap.com/) ~ Used as the core structuring layout building blocks of the website, ensuring responsive size display.
+ [Gitpod](https://www.gitpod.io/) ~ Gitpod was used as the preferred IDE for this project.
+ Gitpod Terminal ~ Used to commit to local repository and further push to Github Repo ensuring version controlling of the project build.
+ [Git](https://git-scm.com/) ~ Version control system for tracking changes to your coding projects.
+ [Github](https://github.com/) ~ Used to host the deployed website and repository of all previous versions of the build.
+ Google Chrome Developer Tools ~ Used as the core test phase throughout the project build life, testing the responsiveness of elements and CSS visuals.
+ [Pexels](https://www.pexels.com/) ~ Online Free stock imagery. Used to provide the hero shot images.
+ [Fontawesome](https://fontawesome.com/) ~ for icons 
+ [Freepnglogos](https://www.freepnglogos.com/) ~ used for images that of the logo from the games that are shown on the Webpage
+ [Balsamiq](https://balsamiq.com/) ~ used to create the wireframes for this project

### User Experience (UX) 
#### User Stories 
+ As a visitor of the site I want a clear overview of games that are offered. So that I can see if the offers draw my interest
+ As a visitor I want to see links to social accounts from "Pulze", so I can see how many people are following and using "Pulze" and get more trust.  
+ As a visitor i want an easy way to navigate to the events/tournaments offered by "Pulze"
+ As a visitor interested joining a tournament I need to understand easily which tournament starts where?(region) when? (time) and how many people can join. (Party size). To make a decision for what tournaments I might want to sign up to. 
+ As a visitor I want to able to sign up for a tournament, to participate on the tournament.
+ As a visitor I want to get more information on the benefits I might have when using this Service, to make a decision for or against the usage.

#### Design
##### Colour Scheme
the main colors used for this Project are white (#fafafa) neon-pink (#ff6ec7) and a dark grey (rgba(15, 15, 15, 1)). Throughout the page text-shadow is used to give e.g. headlines a bright look that builts a strong contrast to the dark grey background. 
![example of text-shadow ](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/screenshots/headline-shadow-screenshot.PNG "example of text-shadow")

##### Typography
The Roboto font is the main font used in this project. It provides a natural reading rhythm giving the webpage a nice look while also bringing accessibility in terms of easy to read text. As a Fallback Sans-serif was used, in case the font doesn't load to the webpage correctly.

Press Start 2P is a bitmap font based on the font design from 1980s Namco arcade games. It was used mostly for headers. It gives the webpage an arcade feeling, which suits the theme "gaming" perfectly. The reason for the scarce usage of this font was to keep the easy readable. As a Fallback Sans-serif was used, in case the font doesn't load to the webpage correctly.

##### Imagery
Images for the hero shots were used to create a striking effect that gains the users/visitors attention. Game logos were used to show what kind of games are offered on the webage.
 
##### Wireframes
A Desktop First approach was used for the design of the wireframes.  This aproach was used because the webpage revolves around esport and gaming. Users likely use their desktops or notebooks to visit the site. 
 + Home Page Wireframe : [Desktop](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/lp_desktop.pdf)    [Mobile](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/lp_mobile.pdf)
 + Event Page Wireframe : [Desktop](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/event_desktop.pdf)    [Mobile](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/eventpage_mobile.pdf)
 + About Page Wireframe : [Desktop](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/about_us_desktop.pdf)    [Mobile](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/about_us_mobile.pdf)

### Testing
The W3C Markup Validator and W3C CSS Validator Services were used on every page of the project to ensure there were no syntax errors.
+[HTML Validator](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/screenshots/screenshot-html.PNG)
+[CSS Validator](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/screenshots/css-validator.PNG)

#### Testing User Stories from User Experience (UX) Section
1. As a visitor of the site I want a clear overview of games that are offered. So that I can see if the offers draw my interest
+ On the hero shot the user can see a notable  [button](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/screenshots/btn-games.PNG) in the hero section. When clicking on the button the user will be sent to the games overview section. 
![games overview section ](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/screenshots/choose-your-game.PNG "games overview section")

2. As a visitor I want to see links to social accounts from "Pulze", so I can see how many people are following and using "Pulze" and get more trust.  
+ Social links are shown on the landing page. For this an extra section was created.
![social links section ](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/screenshots/join-us.PNG "social links section")
+ Because this section is just on the landing page, social links are also provided in the footer. So Visitors can access the "Pulze" social media accounts from everywhere
![footer of the page with social links](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/screenshots/footer.PNG "footer of the page with social links")

3. As a visitor i want an easy way to navigate to the events/tournaments offered by "Pulze"
+ The event page can be easily reached via the navigation bar
+ the visitor can also get to the event page by clicking on the game images provided on the landing page
+ On the event page the user can use to button in the hero shot to automatically scroll down to the events

4. As a visitor interested joining a tournament I need to understand easily which tournament starts where?(region) when? (time) and how many people can join. (Party size). To make a decision for what tournaments I might want to sign up to. 
+ Right before the user comes to the tournament cards, the user first sees the region section. A color was used to show a specific region.
![region section on event page](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/screenshots/region.PNG "region section on event page")
+ The tournament cards use the same colors to indicate the region for the tournament. In the card the user can find more information on time and party size. Because the cards are sorted by weekdays, the user is always able to know when a tournament takes place.
![tournament cards](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/screenshots/tournament-cards.PNG "tournament cards")

5. As a visitor I want to able to sign up for a tournament, to participate on the tournament.
+Each tournament card has a "Join" button. When a user clicks on one of these buttons a contact form opens up.
+Because this project is focused on HTML & CSS only. The user needs to fill out the form, while also stating which game he wants to play, at which region and at which day. Other information that are asked in this form are a name, email and the party-size, if the user wants to play together with friends in a premade party.
![modal form view](https://github.com/Gonzo2500/Milestone_project_1/blob/master/documentation/screenshots/modal.PNG "modal form view")


