# Youth Aflame Social Club

## A Social Club for the Youth in the Stolberg City and around

Youth Aflame Social club is an association established to bring together the Youth of Stolberg-Germany
for one common mission and goal. Youth Aflame Social Club was established in 2020 by the Youth Ministry
within the community. We target young people between the ages of 13-25 years. It is a very interactive
group that helps in the good upbringing of young people. This Website is set up to help advertise the 
group and allow people to get information and sign up for the group.
View the live site [here](https://benohene.github.io/youth-aflame-sc-project/)

![Mockup](docs/readme-images/12-mockup.jpg)

# Features

## HOME PAGE

### Title header with Favicon
* A favicon will be implemented with the Youth Aflame Social clubs emblem.
* This will provide an image in the tab's title header to allow users to easily identify the website if they have multiple open tabs.

![Title with Favicon](docs/readme-images/favicon-title.jpg)

### Navigation Menu
* Contains the various links to all three pages within the website. that is Home, Contact and Signup.
* This will allow users smooth and easy access to all the pages and it is also responsive to device size.
* The active pages always has a buttom border under the page name

![Navigation Menu](docs/readme-images/navigation.jpg)

### Welcome Section
* This landing page has a still image with a message to welcome and introduce the user to the website.
* This will help to immediately show the user what the website is about and help to animate the page.

![Welcome Section](docs/readme-images/welcome.jpg)

### About Section
* This section gives information about the Social group highlighting the mission and goals of the group.
* This information lets the user know what the site is about and also why you must sign up and be part of the group.

![About Us](docs/readme-images/about-us.jpg)

### Activities Section
* This section has four different images corresponding to the activities we have during our meeting times.
* This section highlights the meeting times and the venues and also gives information about what specifically is done during the various meeting times.

![Activities Section](docs/readme-images/activities.jpg)

### Footer
* The Footer section of the page includes a heading that directs visitors to our social media links.
* You can also have quick access to our contact details like telephone number and Email Address
* The footer runs across all the 3 pages and is also responsive to all device sizes

![Footer](docs/readme-images/footer.jpg)


## CONTACT PAGE

### Map
* The map gives information about our location and you can click the map to have access to google directions.

![Map](docs/readme-images/map.jpg)

### Contact form
* For more information about the group, the contact form allows users to contact the groups by providing the following data;
    * First Name **required**
    * Last Name **required**
    * Email **required**
    * Message **required**

![Contact forms](docs/readme-images/contact-form.jpg)

* After successfully sending the message, you will be greeted by a nice image with a thank you message.

![Thank you](docs/readme-images/thank-you.jpg)

### Contact details Section
* This section gives information about our name, address, telephone number and email.

![Contact details](docs/readme-images/contact-details.jpg)

# SIGN UP PAGE

### Sign-up form
* The form allows visitors who want to join the group easy access to do that without travelling to our office.
* the visitor is provided with text input to provide their information. that is Name, Last Name and Email.
* The visitor must therefore choose a membership type and click the JOIN Us button to register.
* The visitor is then greeted with a congratulatory message.

![Sign Up](docs/readme-images/signup.jpg)
![Congrats](docs/readme-images/signed-up.jpg)


## FUTURE FEATURES
* In the future, the contact forms will be links to the organization's email to receive emails from visitors.
* Also the Sign-Up form will be linked with an email to receive details of all those who join the Club.
* Add an Error 404 page with back to the home link for broken links.



# DESIGN
## Wireframe

### Homepage
![Home page](docs/readme-images/home-wireframenew.png)

### Contact Page
![Contact page](docs/readme-images/contaact-witeframe.png)

### Sign-up page 
![Sign up page](docs/readme-images/signup-wireframe.png)

# TECHNOLOGIES APPLIED

* HTML - The structure of the Website was developed using HTML as the main language.

* CSS - The Website was styled using custom CSS in an external file.

* GitHub - The source code is hosted on GitHub and deployed using Git Pages.

* Git - Used to commit and push code during the development of the Website

* Font Awesome - Provides icons used to structures and give details in HTML https://fontawesome.com/ 

* Photoshop - Used to create wireframes and also edit pictures and logo

# TESTING
## Structure and Styling
During testing, the Unicorn Revealer and Wave were used to check for structure and styling error and all were fixed accordingly. All pages were run by the Unicorn revealer and Wave to fix errors.

### Unicorn revealer
![Unicorn Revealer](docs/readme-images/unicorn-test.jpg)

### Wave Web Accessibility
![Wave](docs/readme-images/wave-test.jpg)

* The Wave Web Accessibility help to make sure that all the necessary HTML attributes are used well without errors.

* It was also used to check for color contrast.



## Responsiveness
The Website has been tested and it passed responsiveness for small mediumum and large screens of various devicesce. Ali pagesge have been tested for with a device size of 350px.

The Responsive design was tested manually with [Chrome DevTools](https://developer.chrome.com/docs/devtools/) and also the Microsoft Dev tools. The Website worked perfectly well.

The Website pass its responsiveness and no responsive issues were seen on the following trial device:
* iPhone SE
* iPhone 12 Pro
* Samsung Galaxy S20/S20 Ultra
* Surface Duo

The Website was also tested on [Media Genesis Responsive Checker](https://www.responsivedesignchecker.com/) on various device and the expected result was acheived.

## Coding
The website has been thoroughly tested. All the code has been run through the W3C HTML Validator and the W3C CSS Validator. Some errors were initially detected and fixed

### Home page (BEFORE AND AFTER)
![Error](docs/testing/1index-html-error.jpg)![Fixed](docs/testing/2index-html-errorfix.jpg)

### Contact page (BEFORE AND AFTER)
![Error](docs/testing/3map-contact-page.jpg)![Fixed](docs/testing/4map-contact-pagefixed.jpg)

### Sign Up page (BEFORE AND AFTER)
![Error](docs/testing/5sigg-up-error.jpg)![Fixed](docs/testing/6sigg-up-errorfixed.jpg)

## Lighthouse Test

The site was also tested using the lighthouse option built in Dev Tools in Chrome. It was used to check the following features:

* Performance - How the page performs whilst loading on the browser
* Accessibility - Is the site acccessible for all users and how can it be improved.
* Best Practices - Site conforms to industry best practices.
* SEO - Search engine optimization. Is the site optimized for search engine result rankings.

The result was quiet good. The testing was done one all the pages both on desktop and mobile devices. Below are some sample screenshot;
### On Mobile
![Mobile option for Sign Up page](docs/testing/lighthouse-desktop.jpg)
### Home page
![Lighthouse test on Home Page](docs/testing/lighthouse-index-page.jpg)
### Contact page
![Lighthouse test on Contact Page](docs/testing/lighthouse-contact-page.jpg)
### Sign Up page
![Lighthouse test on Sign Up Page](docs/testing/lighthouse-signup-page.jpg)

## Form Testing

The form on the contact page was tested to ensure it functioned as expected when correct data was input and when incorrect data was input.


### Contact Form Testing
Steps to test:

Navigate to the Youth Aflame Social Club Contact page
Scroll down to the contact form and input the following data:
1. First Name: Benjamin
2. Last Name: Wilson
3. Email: bwilason@yasc.de
4. Message: Write the details of your message
5. Click SEND

User should be redirected to a thank you page confirming your message has been sent successfully.

All input areas are ***required*** to be filled before the form send ing can be successful.


### Sign-Up From Testing

Steps to test:

Navigate to the Youth Aflame Social Club Sign-Up page
Scroll down to the contact form and input the following data:
1. First Name: Benjamin
2. Last Name: Wilson
3. Email: bwilason@yasc.de
4. Click JOIN US

Users should be redirected to a welcome page confirming their data for registration has been sent successfully.

All input areas are ***required*** to be filled before the form sending can be successful.

# DEPLOYMENT
The site was created using the Gitpod and pushed to github to the remote repository.

***Gitpod is an open source developer platform automating the provisioning of ready-to-code developer environments.***

The following git commands were used throughout development to push code to the remote repo:

```git add .``` - This command was used to add all updated file(s) to the staging area.

```git commit -m ???commit message???``` - This command was used to commit changes from the staging area to the local repository queue ready for the final step.

```git push``` - This command was used to push all committed code to the remote repository on Git Hub so it is safe and secure.

### Deployment to GitHub Pages

The site was deployed to GitHub pages. The steps to deploy are as follows: 
1. In the GitHub repository, navigate to the Settings tab 

2. From the menu on left select 'Pages'

3. From the source section drop-down menu, select the Branch: main

4. Click 'Save'

5. A live link will be displayed in blue when published successfully.

![Deployment to GitHub pages](docs/readme-images/10-deployment.jpg)

The Live link can be access by [Clicking Here-Youth Aflame Social Club](https://benohene.github.io/youth-aflame-sc-project/)

## Clone the Repository Code Locally
* Navigate to the GitHub Repository you want to clone to use locally:

1. Click on the code drop down button

2. Click on HTTPS

3. Copy the repository link to the clipboard

4. Open your IDE of choice (git must be installed for the next steps)

5. Type git clone copied-git-url into the IDE terminal

***The project will now of been cloned on your local machine for use.***

# CREDIT

## Content
* [Font Awesome](https://fontawesome.com/). Used for icons.
* [Google Fonts](https://fonts.google.com/) Used for fonts.
* [Google Maps](https://www.google.com/maps) Used for maps.
* Love Running project-Some codes were generated from there.
* [YouTube](http://youtube.com/)The coding of the contact page forms was inspired by a video on Youtube.

## Media
* All images from [Pexels](https://www.pexels.com/).
* Logo was created by me using photoshop.
* Most of the images were edited by me with photoshop.