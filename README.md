# GAMERZ4US

**MileStone project 1: Code Institute HTML/CSS Essentials.**

A small styled website for a gaming scoiety to link all gamers to one platform where it links (by clicking the links in the games page) to the desired platform service of their choice, while being able to contact the team for any inqiries.

In short explaination:
- Increase in players joining the one service
- have all platforms available to view content on the one website linking to original platform sites

For this Code Institute student project a live version demo via github pages can be found **[here](https://markk0042.github.io/Gamerz4Us.io/)**

![Design](https://github.com/markk0042/GAMERZ4US/images/Previewofhomepage.png)

## UX

Ideal UX design was to be as clear and less confusing as possible, with simple layout along with providing options to the users.


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


## Features

This website has a collapsable navbar where on mobile devices it grows smaller and fitting smaller device screens,
the footer also implements the same idea where goes smaller using css and renders to smaller screens to fit the content within the footer.

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

1. [W3C-HTML-Validator] (https://validator.w3.org/) :This was used to validate the HTML to ensure that all elements and text markup were fully correct and functioning, by coping and pasting into webtool and then pasting back into source code to fix errors given.
2. [Jigsaw-W3-CSS-Validator](https://jigsaw.w3.org/css-validator/validator): This was used to validate the CSS to ensure that all styles were fully correct and functioning, by coping and pasting into webtool and then pasting back into source code to fix errors given.
3. [Web-formatter-tool](https://webformatter.com/css) : This was used to correctly apply indentation to your code when it becomes messy, by copying and pasting into the web tool and indents within seconds, then pasting back into source code.














reference of assistance used {
styles:
https://stackoverflow.com/questions/69753794/how-to-position-hero-image-on-a-webpage
https://www.geeksforgeeks.org/css-layout-horizontal-vertical-align/
https://iqcode.com/code/css/css-text-larger-on-hover
https://iqcode.com/code/css/change-icon-size-css
https://www.geeksforgeeks.org/css-layout-horizontal-vertical-align/
https://stackoverflow.com/questions/39099295/make-div-stick-to-bottom-of-page

nav:
https://codepen.io/MinzCode/pen/bGexzXw

footer:
https://codepen.io/matheusalmeida/pen/aeLMMr

images source :
https://www.pexels.com/photo/black-gaming-console-194511/

card container :
https://www.codeinfoweb.com/2021/03/Responsive%20Cards.html

}


validator tools used :

https://jigsaw.w3.org/css-validator/validator
https://webformatter.com/css
https://validator.w3.org/

















This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. It's perfectly ok to use this template as the basis for your project submissions.

You can safely delete this README.md file, or change it for your own project. Please do read it at least once, though! It contains some important information about Gitpod and the extensions we use. Some of this information has been updated since the video content was created. The last update to this file was: **September 1, 2021**

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
