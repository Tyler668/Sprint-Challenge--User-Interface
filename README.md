# Sprint Challenge: User Interface and Git - Multi-Page Website
#Tyler Gilchrist

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored User Interface and Git. During this Sprint, you studied Semantic HTML, CSS Fundamentals, CSS Flexbox Module, and Git. In your challenge this week, you will demonstrate proficiency by creating a multi page website that has some missing HTML elements as well as CSS specificity problems that need to be solved.  You will also create an additional web page that will be linked to from a navigation you will build.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in user interface and your command of the concepts and techniques in semantic HTML, CSS fundamentals, CSS flexbox module, and git.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons and your project manager.

## Description

In this challenge, you build a missing header (navigation and image) on the home page, update some CSS styling on the home page, and create an additional page (About) which will link from the navigation you created.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution screen shots of the home and about pages:

[Click here for the home page example](https://tk-assets.lambdaschool.com/39a49225-8ac9-43da-aa90-514fd60ae99a_sprint-challenge-ui-home-example.png)

[Click here for the about page example](https://tk-assets.lambdaschool.com/ede1bb1a-63ff-4801-8c02-3efa2f603190_sprint-challenge-ui-about-example.png)

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. If you were to describe semantic HTML to the next cohort of students, what would you say?

Semantic HTML consists of HTML tags and markups that give the content on the page meaning. An example of a NON semantic tag might be a <div>, which doesn't give the browser any information about the contents of the tag. Semantic HTML on the other hand would be something like <header>, <footer>, <nav>, <table>, etc. All of these tags queue us in on what and where the content might be. 

2. Name two big differences between ```display: block;``` and ```display: inline;```.

-Display: inline is unable to have its height and width modified while display: block can.
-Display: inline takes up only the space needed to fit, display: block takes up the full width available and creates space above and below.

3. What are the 4 areas of the box model?

-Content
-Padding
-Border
-Margin

4. While using flexbox, what axis does the following property work on: ```align-items: center```?

This works on the vertical axis (Y)

5. Explain why git is valuable to a team of developers.

Git is similar in function to something like Google Drive, but with extra functionalities. It allows multiple people to work on one piece of software, each branching out in different directions and working on different parts. The strength of git is the ability to commit / save an infinite amount of accessible change logs that can be reverted to at any time in the event someone breaks the code. Once changes are pushed to github, specific changes can be reviewed and assessed for merging with the base code. In summation; Git is a safety net for the development team to all try their own thing with no negative consequences.

You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Project Set Up

- [X] Create a forked copy of this project.
- [X] Add your project manager as collaborator on Github.
- [X] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [X] Create a new branch: git checkout -b `<firstName-lastName>`.
- [X] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
- [X] Push commits: git push origin `<firstName-lastName>`.
 
Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [X] Add your project manager as a reviewer on the pull-request
- [ ] Your project manager will count the project as complete by merging the branch back into master.
 


## Minimum Viable Product

Your finished project must include all of the following requirements:

### Home Page

[Review the provided design file for the home page](design-files/home.png).  Notice the navigation and header images are missing.

* [X] Build the HTML and CSS to create the missing navigation and header.
* [ ] Link the `About` navigation item to the [about.html](about.html) page

You will also notice there are 10 boxes on the home page that need background colors.  Use this list below to correctly style each box:

* [X] box1: `teal`
* [X] box2: `gold`
* [X] box3: `cadetblue`
* [X] box4: `coral`
* [X] box5: `crimson`
* [X] box6: `forestgreen`
* [X] box7: `darkorchid`
* [X] box8: `hotpink`
* [X] box9: `indigo`
* [X] box10: `dodgerblue`

### About Page

[Review the provided design file for the about page](design-files/about.png). You have been provided the HTML wrapper, footer, and page content for the about page. Create the rest of the missing HTML and CSS to match the design file.

* [X] Copy and paste your home page navigation and header into the about page
* [X] Update the header image with the about page image
* [X] Link the `Home` navigation item back to the `index.html` page.
* [X] Build the rest of the about page layout to match the design

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [X] Build a page of your choosing from the navigation items.  Come up with content and images that fit the theme.  
* [X] Introduce CSS animations to your site.
* [ ] Build a contact page and create a form with several inputs of your choosing
* [ ] Add responsive breakpoints to your code by using media queries
