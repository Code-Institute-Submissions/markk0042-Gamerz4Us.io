# GAMERZ4US

**MileStone project 1: Code Institute HTML/CSS Essentials.**

A small styled website for a gaming scoiety to link all gamers to one platform where it links (by clicking the links in the games page) to the desired platform service of their choice, while being able to contact the team for any inqiries. It is based on sending out each month free content codes to users, updates on games, reviews etc, in the about us section it mentions that a forum will take effect soon which will be one of the main features other than the free content.

In short explaination:
- Increase in players joining the one service
- have all platforms available to view content on the one website linking to original platform sites

For this Code Institute student project a live version demo via github pages can be found **[here](https://markk0042.github.io/Gamerz4Us.io/)**






I have used Figma to design this website in a prototype design, Desktop design found here:

Desktop:

- [Main](/Figma-Design/main.png)

- [Platform-Page](/Figma-Design/Platforms.png)

- [Contact-Page](/Figma-Design/contactpage.png)

Mobile:

- [Main](/Figma-Design/Main-landing-page-mobile-design.png)

- [Platform-Page](/Figma-Design/Platform-mobile-page.png)

- [Contact-Page](/Figma-Design/mobile-contact-design.png)

This is an screenshot example of what to expect from the website GAMERZ4US
![Design](/images/Design-image-website.png)



## UX (User Design)

* As a frequent user, I would like easy navigation rather than having to scroll for long periods
* As a user of this site, I would like to know its purpose when landing on the page first hand
* As a user I would like to be able to connect to the social media services
* As a user I would like to be able to contact the team via the website
* As a user I would like to have the option of visiting different platforms or see the list of different platforms



## Wireframes

The wireframes for Gamerz4US was created on figma, [Figma](https://www.figma.com/?fuid=) The finished site for now varies slightly from the wireframes created on figma due to changes in developments that happened during the creation process.



## Site Structure

GAMERZ4US has 3 pages. The main page is the landing page on arrival to the website [Home Page](index.html).The second page [Games Page](games.html) this page is the page that will list the different platforms for users to visit and view releases etc. The third page [Contact Page](contact.html) will advertise a contact form to get in touch with the website team for sign up process, queries of looking for general information etc.


## Design Choices

* ### Typography 
- The overall fonts chosen for this website project was Kanit and sans-serif, if the font "Kanit" is not appliable it will fall back to the standard sans-serif.

* ### Color Scheme
- The colors chosen were to make different elements standout and make key area pop to the eye, for example the navbar is white with a hover attribute and an underline colored styled attribute with the footer following suit with the same styles, the form element has a style of yellow in the input fields when hovered upon to highlight the area the user is in.



## Features

GAMERZ4US is a site that is easy to use and navigate with links and pages liking to one another, it contains features that the user(s) would probably be familiar with, such as a navigation bar, footer, links and contact form.


## Existing Features  
  * ### Navigation Menu

  
















### Website Strategy

The key aim was to enable easy access to other services linking everyone to the one place for these platform services, while having a clean responsive mobile friendly website using CSS and HTML with no frameworks.



### Scope 

For gamers I wanted to provide them with easy access and nice design where they dont have to scroll for long periods of time being able to be directed to the service the want or like to learn more about.



### Skeleton

By using the website mock up building tool I used Figma to design a skeleton version of the website to design towards that end goal.

[GAMERZ4US] ()
[Device-Responsive-Design] ()



### Surface 

The colors of a white nav bar and footer and also text were used to stand out against the blue background images and also the balck and white image on the contact page. I used the blue backgrounded image because it isnt sensitive to the eye, text and fonts appaear easy to the eye and it has a 'cool vibe' to it rather than a color thats eye popping like yellow or red.

The fonts used were Kanit and sans-serif globally to make all text the same and also give it a nice style thats easy to read.

## Technologies

1. HTML - *To create a basic standard webpage*
2. CSS - *To design and add styles to the basic webpage and help it standout*



### Features left to Implement to the website

I would in the future after completing the Full Stack course, like to add in a sign in/ sign up feature where the users can create personal accounts and have user names etc, I would also add in a forum section for each genre with a search function to search games by title and also a section where videos/ images could be posted similar to a redit styled website but for gamers only to use, where all gamers can join and become one community all in one place.



## Testing of the Website

When designing the website the links in the navbar were set up and then tested after designing them, the buttoms and footer also has the same style design and element attributes also all were tested befoore designing and after designing with css to ensure they are all working correctly, and that they all also open with a _blank attribute anf=d go to the desired http address also. The form on the contact page has been tested with being filled out with the required information and also pressing submit and everthing works as planned. 

when the screen size changes smaller the navbar collapses into a burger icon menu with a drop down section added into it, and when the cards on the games page is rendered on a smaller screen the cards become smaller and render to fit on small screen devices and change size due to screen reolution. The footer adjusts to smaller screens by aligning the footer elements along the left hand side of the page for mobile friendly devices creating a cleaner less squashed, more tidier appearance.




## Bugs Found

A error I found on the form element was that there was a action with post and also and empty ID element where it cause the form when filled out to return an error 404 then a 501 error, HTML W3 validator was used and this became clear, when removed and corrected the form fills out and submits well now.



### Footer Responsivness to Mobile design

When the footer was used in the developer tools section the footer became overlapped with the cards and the footer pushed up too far up the screen to resolve this I used :

- Media Quries - I used a min and max screen media query and added margin top and bottom styles and also reduced padding to make it fit more nice on the responsive screens and also changing its height property also.



Validator Tools Used:

1. [W3C-HTML-Validator](https://validator.w3.org/) :This was used to validate the HTML to ensure that all elements and text markup were fully correct and functioning, by coping and pasting into webtool and then pasting back into source code to fix errors given.
2. [Jigsaw-W3-CSS-Validator](https://jigsaw.w3.org/css-validator/validator): This was used to validate the CSS to ensure that all styles were fully correct and functioning, by coping and pasting into webtool and then pasting back into source code to fix errors given.
3. [Web-formatter-tool](https://webformatter.com/css) : This was used to correctly apply indentation to your code when it becomes messy, by copying and pasting into the web tool and indents within seconds, then pasting back into source code.


## Deployment

This assignment/ Project was Deployed on guthub pages directly from the master branch and along with the theme jekyll.
the main page for github pages to load was named index.html as this is needed for the browser to read and deploy the website correctly.

To view this page from the github terminal:
- `python3 -m http.server`
- A blue button should appear to click: _Open Browser_.
- A new browser window should appear
- Dont Forget to clear cache if having issues loading CSS and HTML.

to remove or cut ties with github and its repositories in the terminal inside github write:
- `git remote rm origin`



## Credits and Acknowledgements

### Media

- All photos were used or taken from the free images based website [Pexels](https://www.pexels.com/photo/black-gaming-console-194511/).


### Acknowledgements of assistance of work used in this project

- For the navbar I used assistance from [Code-Pen](https://codepen.io/MinzCode/pen/bGexzXw): I found it difficult creating a navbar using vanilla css and html so I used navbar assistance form code pen listed above, and chnaged styles according to my website needs.

- For the Footer I used assistance from [Code-Pen](https://codepen.io/matheusalmeida/pen/aeLMMr) in mobile design and also colums and structures as with plain CSS and HTML I found this difficult to complete, I changed fonts, colors, links and added css and styles to fit the website I was creating as a assignment.

- For the card section I tried muyltiple ways to complete this but when trying different methods it was disrupting my other stylea and elements. I used assistance from [Code-Info-Web](https://www.codeinfoweb.com/2021/03/Responsive%20Cards.html) for the cards I changed the images, added styles and colors and font sizes, I also added hover psuedo attributes and also links to sources and also border radiuses etc.

For assitance with styles in css i used the following:

1. [Stack-Over-Flow](https://stackoverflow.com/questions/69753794/how-to-position-hero-image-on-a-webpage): Positioning images on a Webpage.
2. [Geeks-For-Geeks](https://www.geeksforgeeks.org/css-layout-horizontal-vertical-align/):
Aligning Elements.
3. [iqcode](https://iqcode.com/code/css/css-text-larger-on-hover):
Hover Psuedo attributes.
4. [iqcode](https://iqcode.com/code/css/change-icon-size-css):
Font Awesome Icon Sizes.
5. [Stack-Over-Flow](https://stackoverflow.com/questions/39099295/make-div-stick-to-bottom-of-page):
Footer sticking at bottom of page.
6. [Fotor](https://www.fotor.com/design/project/7c966b89-9976-46de-89d3-64b506228fa2/collage):
Used Fotor.com to create a design image for my read me file to show case the design for an image preview before the website is viewed on github page using the link above.
7. [Pexels](https://www.pexels.com/): Free image source for websites and projects.
8. [Figma-Prototype-Design](https://www.figma.com/?fuid=): Used to create a template design of the website design.
9. [W3schools](https://www.w3schools.com/): For pretty much assistance on the whole project with design tips and tricks to styling with CSS and HTML write ups.
10. [Font-Awesome-Icons](https://fontawesome.com/icons): For cool Icons for design process.
11. [Google-Fonts](https://fonts.google.com/):For fonts designing and styling.