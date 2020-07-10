# Sprint Challenge: User Interface and Git - Multi-Page Website

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored User Interface and Git. During this Sprint, you studied Semantic HTML, CSS Fundamentals, CSS Flexbox Module, and Git. In your challenge this week, you will demonstrate proficiency by creating a multi page website that has some missing HTML elements as well as CSS specificity problems that need to be solved.  You will also create an additional web page that will be linked to from a navigation you will build.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction. Your work reflects your proficiency in user interface and your command of the concepts and techniques in semantic HTML, CSS fundamentals, CSS flexbox module, and git.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons and your project manager.

## Description

In this challenge, you build a missing header (navigation and image) on the home page, update some CSS styling on the home page, and create an additional page (About) which will link from the navigation you created.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution screen shots of the home and about pages (found in the design-files folder):

[Click here for the home page example](https://tk-assets.lambdaschool.com/39a49225-8ac9-43da-aa90-514fd60ae99a_sprint-challenge-ui-home-example.png)

[Click here for the about page example](https://tk-assets.lambdaschool.com/ede1bb1a-63ff-4801-8c02-3efa2f603190_sprint-challenge-ui-about-example.png)

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your Team Lead

1. If you were to describe semantic HTML to the next cohort of students, what would you say?

    HTML is a lot like a novel. When you pick up a book, there's all this text that your reading. Thats straight up HTML. But there's a lot of work that went into the book that you're not seeing directly, but that was intentionally thought through. All the grammar. When titles are before main content and there's paragraphs and there's different sections. Unlike a novel, we actually mark-up a lot of these things for a couple reasons in HTML. First, we include them for folks using accessability readers, folks who might not be actually seeing that spiffy layout you've made, but only hearing it, or reading it in huge font with a totally custom layout for example. Well, they're reader will find all these chunks of text, and will only know what they are if we include them in the HTML. This means actually tagging all the text and images with a 'semantic' or 'meaningful' tag. Like putting "title," "header," "squirell section," etc. We even label the images so that folks know what we were displaying. Secondly, this helps ourselves and other coders down the line by know what on earth we were thinking. Plus we can do fun stuff with Semantic HTML in CSS later.

2. Name two big differences between ```display: block;``` and ```display: inline;```.

    ```display: block;``` changes the nature of the container to act more like a <div>. Meaning that container will take up the full width of the parent container (or page if there is no parent container), forcing itself on a new line & whatever is after it down onto the next line.
    ```display: inline;``` meanwhile changes the container to act more like a <span>. This container will now only take up the width needed to contain whatever is inside it, potentially leaving room for other bits before and after it on the same line.
    The difference is much like a paragraph and a sentence. Block will be it's own independent paragraph, whereas inline will be a sentence in a paragraph with more sentences around it.

3. What are the 4 areas of the box model?

    Content is what we've put between the tags in the HTML (or the img itself). It's the text or other bit we wanted to display.
    Border is the box that goes around that content. It can be styled to all sorts of lines/dimensions or even left invisible.
    Padding is the space between the Content and the Border. It can be given a background, which will show that it completely fills the border and goes behind the content.
    Margin is the space outside of the border where it's "pushing" against other elements.
        In Taja's analogy, Content is all the bones and squishy bits inside our bodies. Border is our skin, Padding is that lovely stuff that keeps us warm & squishy (Fat), and margin is our personal bubble that you better not invade.

4. While using flexbox, what axis does the following property work on: ```align-items: center```?

    The Cross-axis

5. Explain why git is valuable to a team of developers.

    It shows that we've been working with all those thousand commits we've pushed. Real hard workers we are. ha. ... ha. ... ha.
    But seriously, it does a wonderful job of version control so that folks (including ourselves) can revert back to prior versions in case something isn't quite working right.
    Git also allows us to start with the main code, and instead of everyone tweaking it simultaneously for utter chaos, make branch copies that we work on. Later someone can choose to merge the work we've done on the personal branch with the main branch to update the main code in a more controlled & systematic way. Much safer & good for avoiding breakage.
    There's also the benefit of having git sync beautifully to a cloud storage point where code can be saved in case a computer spontaneously combusts or is stolen by crazed apocalyptic zombies. Best to be prepared. Or in case someone exploes a blender full of boiling red jello all over their laptop. Not that I've done such a thing and had to deal with a gunked up trackpad & odd red spots for years afterwards, but you know, it could have happened to someone. Hypothetically speaking.

You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Project Set Up

- [x] Create a forked copy of this project.
- [x] Add your Team Lead as collaborator on Github.
- [x] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [x] Create a new branch: git checkout -b `<firstName-lastName>`.
- [x] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
- [ ] Push commits: git push -u origin `<firstName-lastName>`.

Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your Team Lead as a reviewer on the pull-request
- [ ] Your Team Lead will count the project as complete by merging the branch back into master.



## Minimum Viable Product

Your finished project must include all of the following requirements:

### Home Page

[Review the provided design file for the home page](design-files/home.png).  Notice the navigation and header images are missing.

* [x] Build the HTML and CSS to create the missing navigation and header.
* [x] Link the `About` navigation item to the [about.html](about.html) page

You will also notice there are 10 boxes on the home page that need background colors.  Use this list below to correctly style each box:

* [x] box1: `teal`
* [x] box2: `gold`
* [x] box3: `cadetblue`
* [x] box4: `coral`
* [x] box5: `crimson`
* [x] box6: `forestgreen`
* [x] box7: `darkorchid`
* [x] box8: `hotpink`
* [x] box9: `indigo`
* [x] box10: `dodgerblue`

### About Page

[Review the provided design file for the about page](design-files/about.png). You have been provided the HTML wrapper, footer, and page content for the about page. Create the rest of the missing HTML and CSS to match the design file.

* [x] Copy and paste your home page navigation and header into the about page
* [x] Update the header image with the about page image
* [x] Link the `Home` navigation item back to the `index.html` page.
* [ ] Build the rest of the about page layout to match the design

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

Note: Please make sure you are using flexbox to layout your website. Floats, inline-block, tables, etc, should not be used for layout.

## Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [x] refactor your HTML, make sure it's indented properly, clean, readable, you have written appropriate comments where necessary and that all attributes (required and encouraged) are filled out correctly.
* [x] Ensure your CSS is organized and readable, you've seperated your code by section and that you are using descriptive class names and adding classes in your HTML where styles repeat rather than rewrting the same styles over again
* [ ] Use a flex item property of your choice when laying out a section of your website, ensure you can explain how and why you've used this property
