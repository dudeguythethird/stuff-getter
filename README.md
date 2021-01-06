# Stuff Getter

This project (LINK) is a simple clicker/ incremental game (in the style of *Cookie Clicker* or *Tap Tycoon*). Its main aim is to provide a fun experience of interactive growth for the player. It must achieve this with only HTML, CSS, and Javascript (JQuery). 

A clicker/ incremental game is a genre in which, initially, the only avenue for interactivity offered to the player is to simply click, either a button or anywhere on the screen. Doing this accrues a resource. Different iterations of the genre choose different resources, usually for thematic reasons. *Adventure Capitalist* has dollars, *Adventure Communist* has potatoes, *Cookie Clicker* has… well... cookies. The conceit of these games is their simplicity, which almost always builds into ludicrous levels of complexity. As the games go on, they offer the player various items that they can buy with their accrued resources. These, usually, will allow the gathering of further resources. The amount of resources the player has will increase exponentially. 

You might be wondering what the goal of all this is. Why keep collecting? In many of these games there is no goal. You are just collecting for collecting's sake; watching the numbers go up is, *supposedly* its own reward. Some have argued that this goalessness makes the genre a parody of gaming in general, by exposing the essentially hollow nature of video games. After all, what other genre can truly claim to reward you outside of the context of the game itself? Aren’t all video games just another iteration of watching the numbers go up?

Whatever the answer to these questions may be, my aim is to create a simple version of one of these, with just a few avenues for higher interactivity (beyond just clicking). This project will heavily rely on an [online guide](https://www.youtube.com/watch?v=d-AbDEwpp6g&list=PLEyTwruuVAqlEvj8QxTFdVPc6_AwpgF2w&ab_channel=TanktotGames) for making this type of game. However, there are a variety of ways that I will be deviating from it, like by using JQuery.
 
## UX


This project aims to provide light distraction to anyone who might need it. That means the project doesn’t really have a target demographic for the simple reason that there isn’t any particular type of person that I wouldn’t want using it! If you want a little light amusement in your day, come on in. 

This may seem like it entails very little UX wise. However, it does suggest certain requirements. The idea is that this project is supposed to be amusing to a wide audience. That means that the theme can’t be alienating to certain sections of society. It should also be somewhat amusing. That’s why I went with the resource simply being called “stuff”. In this case, the resource is named something highly generic, which is both comedic and un-alienating. 

I also don’t want my users to have to jump through any hoops to start playing. As a result, the game is presented on one page, with an optional contact form beneath it. After all, simplicity is the name of the game with clickers.

### * User Story 1 (User new to the concept of clickers)

As a user of this site, I am looking for a brief distraction. For whatever reason I end up on Stuff Getter. I am new to clickers, so I don’t immediately know what I’m looking at. However, a large, brightly colored button invites me to click it to “get stuff”. I try this and immediately notice that my current stuff total is now 1. The more I click the more stuff I get. Wondering what the point of “getting stuff” is, I cast my eye down the page and notice several more buttons in a section called “spend stuff”. The first says that I can get an “auto stuff getter” for just 50 stuff! That sounds like a challenge, so I get clicking and buy it. Now I am getting stuff automatically. There are several more objects I can buy too. Maybe I play for a bit more and buy them. Maybe I leave the tab open for a while and allow the auto stuff getter to do its thing.  Either way, I play for a little bit longer and eventually get bored and move on with my day

### * User Story 2 (User who has played clickers before)

I go through exactly the same steps as above but faster. Essentially, I’ve seen these before and I know what is likely to happen. I probably get bored a bit faster as a result, however, I have still been lightly entertained. 

### * User Story 3 (Developer)

I play through a certain amount of the game’s progression as outlined above and eventually realise that there are some interesting features that could easily be added to the project. I want to suggest that to the developper. I notice a sentence at the bottom of the screen that is inviting me to scroll down and do just that. So I scroll down, fill in the form with my idea and maybe check out the game developer’s github and/or linkedin, which are also linked to. 
 
### Wireframe Mockups

Final design differs slightly from what is shown below: 

![Phone formatted wireframe](/assets/wireframes/phone-wireframe.png)

![Tablet formatted wireframe](/assets/wireframes/tablet-wireframe.png)

![Desktop formatted wireframe](/assets/wireframes/desktop-wireframe.png)

<!--Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
- As a user type, I want to perform an action, so that I can achieve a goal.

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in a separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.--->

## Features

My site only features one page, that is split into two distinct sections, each the height of the view port. This effectively creates 2 pseudo-pages: the game and the contact form. The exact features of each are discussed below:

### Existing Features

#### Game

1. An animated “get stuff” button that, when clicked, awards the user with 1 stuff, as counted below.

2. A save button to allow the user to manually save their progress, they can also do this with the keyboard shortcut ctrl + s.

3. A reset button that allows the user to completely reset their progress, including all stuff got and any buildings, or click multipliers they may have bought. If clicked, they will be asked to confirm their intention to reset.

4. A shop with a variety of items the player can buy:
    1. A “stuff getter”, that provides you with one stuff per second automatically.
    1. A “stuff factory”, that gives the player 5 stuff per second automatically.
    1. A stuff “investment bank”, that gives the player 70 stuff per second automatically. 
    1. An item that multiplies the power of click by 3. (Items a-d can be bought multiple times however, their price will increase after each purchase. As item D increases your clicking power exponentially, its price increases very drastically too.)
    1. A very expensive item (cost 1 billion stuff), that serves as a victory condition, although one can keep playing after acquiring it. 

5. The total number of stuff getters, factories, investment banks, and overall stuff per second is also communicated to the player. 

These features work in tandem with one another to create a sense of progression and growth for the player. They also provide a concrete goal (the victory item) which may help some players who find these types of games quite aimless, while not sacrificing the infinite nature of the genre. 

#### Contact form

1. A fillable name, email address and idea suggestion box. A user, if they want to suggest a feature can scroll down the page, fill in the form and hit submit. This automatically sends a formatted email to one of my email addresses.

1. A page footer that includes generic copyright information, as well as links to my (coding relevant) social media pages. These will help anyone who wants in touch with me, in a professional context, do so with ease. 

### Features Left to Implement

* Achievements (pop awards for completing certain actions).
* More buildings/ items.
* Better art and animations.

<!---

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Another feature idea --->

## Technologies Used

* HTML5
    * This project uses HTML5 to provide structure and content to the site.
* CSS3
    * This project uses CSS3 to provide styling, layout and basic interactivity to the structure and content defined by HTML5.
* JavaScript
    * This project uses JavaScript to define the game’s internal logic.
* [Bootstrap](https://getbootstrap.com/)
    * This project uses the Bootstrap framework to simplify creating dropdowns, buttons, a grid layout, and other CSS/JavaScript functionality.
* [Google Fonts](https://fonts.google.com/)
    * This project uses Google Fonts to allow the adding of more interesting fonts to the project.
* [Font Awesome](https://fontawesome.com/)
    * This project uses Font Awesome to allow the inclusion of icons.
* [JQuery](https://jquery.com)
    * The project uses **JQuery** to simplify DOM manipulation.
* [EmailJS](https://www.emailjs.com/)  
    * Provides an easy to implement back end for email sending. 



<!---
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

-->

### Bugs

* Bug discovered where the number of factories the player had acquired were not loading from cookies. I eventually realised that this was because I had omitted to add a line of code to get that value to save in the first place. Bug fixed by adding the required lines (both to the saveGame and loadGame functions):
```Javascript
function saveGame() {
var gameSave = {
...
factories: factories,
... }
localStorage.setItem("gameSave", JSON.stringify(gameSave));
}
```
```Javascript
function loadGame() {
...
if (typeof savedGame.factories !== "undefined") factories = savedGame.factories;
...
}
```

* Bug discovered where Jquery .click event handlers were not calling the relevant functions. Initially, wrote these event handlers like: 
```Javascript
$(".get-stuff").click(addToScore());
```
* This didn't work, it turned out, because this is not how you are meant to call a function in JQuery, you do not need the brackets after the function's name, if you are not passing in any values. Now, my .click functions all look like:
```Javascript
$(".get-stuff").click(addToScore);
```
* I had some difficulty getting the footer to stick to the bottom of the page. Normally, I would use one of [these](https://css-tricks.com/couple-takes-sticky-footer/) methods. However, my site also has a design that ties the height of it's content to the height of the device's view port. In essence, it mimics having multiple pages on only one page, by having 2 sections both with height= viewport height, with content on them dynamically reformatting to accommodate the relevant screen. This means that any method that involves setting the height of the main content of the page to some amount other than viewport height would defeat the objective of this design. Luckily, this design choice also opened up a simple solution to the sticky footer conundrum: putting the footer within the second <section> and, making it's position absolute, it's containers relative, and it's bottom, left, and right 0:

```CSS
.page-2 {
    position: relative;
}

.footer {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
}
```

<!--

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here. -->

## Deployment

This project is deployed on GitHub pages. I deployed it by:

1. Going to the settings menu of my GitHub project.
1. Scrolling down to the GitHub Pages section.
1. Selecting the master branch source and the appropriate folder (root).
1. Pressing save, waiting for the page to reload.
1. Waiting a few minutes for pages to get set up, afterwards a link was provided: **ADD LINK WHEN DONE**
1. I can push any further pages to the project from Git Pod (my development environment) by using the ‘git add’, ‘git commit’, and ‘git push’ commands in the CLI.
More info on GitHub pages: https://pages.github.com/

Ultimately, there will be no differences between the deployed and development versions.

### How to run this project locally

1. Create a [GitHub](https://github.com/) account.
1. Using Chrome, install the gitpod [browser extension](https://www.gitpod.io/docs/browser-extension/).
1. Restart the browser after installation.
1. Log in to GitPod with your GitHub account.
1. Go to the project [repository](https://github.com/dudeguythethird/clicker-game) on GitHub.
1. Click the green git pod button, this will trigger a new workspace to be created in GitPod with the project in it.

### Cloning this project

Want to make some changes to this project and develop on your own version?

1. Got to this GitHub [repository](https://github.com/dudeguythethird/clicker-game).
1. Under the name, click the ‘code’ drop down, then clone or download.
1. Copy the URL in the HTTPS section.
1. Go to your local IDE and open the terminal.
1. Navigate to the folder you would like to clone the code in.
1. Type “git clone ” then paste the URL you copied in step 3.
1. Press enter!
<!---
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

--->
### Media

- [The background image](https://www.freepik.com/vectors/background), from kjpargeter.

### Acknowledgements

- I received inspiration for this project from X -->

