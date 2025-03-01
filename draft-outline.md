# Draft outline
This is a draft of the course. The topics we'll cover and the order. It will be established and modified based on student needs and how things are going / what people ask for as far as needing things that match the trajectory we're on.
- [Resource for reviewing concepts](https://youtube.com/playlist?list=PLJQupiji7J5efO_Q5VGZcPE4O_TM_HGP4)

## Week 2: Git / Github
- Git lecture + feedback from last assignment
- Slides: https://docs.google.com/presentation/d/1zDuXtOf2EwwG3RzczyohsgU_GC0tfXvGitI9decDr6I/edit?usp=sharing
- Git activity in class
- Exercise to do between Tues and Thurs to jump start on hw

## HTML / CSS fundamentals
### Do for Thurs to get ahead on HW
- Part 1 listed below

## Thursday
- https://github.com/elmsln/edtechjoker/pull/73 -- note that PR's keep piling up commits until they are merged
- Slide deck for Thurs which I will run through quickly https://docs.google.com/presentation/d/1xjySD9ZTVXYW_o9YPrt-wgBHDBM4acaYswaxJ1t83oU/edit?usp=sharing

## Homework
Two-part homework this week; we will have time in class Thurs to start and then Tues the focus will be critique via submissions generated by the class.

### Part 1
- Fork this pen on codepen https://codepen.io/btopro/pen/gOjGpamLinks to an external site.
- Try to make more than 1 meme by duplicating the HTML portion of the code
- Modify the text / image used in the meme on the HTML portion
- Try to modify the font-size using the CSS tab.
- Make a new gist where you try to answer the following questions
  - Provide a Link to your fork of the codepen
  - Can you change the font color? If not, where do you think it is that being set
  - Look at the constructor() what does this do?
  - Look at @media in styles() what does this do?
  - Look at the render method, is this convention "vanilla" (built in) or do you think a library is delivering this?

### Part 2:
- Working with your partner, come up with an agreed upon visual as to how you'd conceive the following problem
- model things after the screenshot / pen and paper copy you came up with

Create a new codepen from scratch and try to create a "card" using a mix of semantic, div and other tags to lay the card out:
- Create a simple “card” using a few SECTION or DIV tags, a Heading for the title, a Paragraph for description of the image an IMG for an image, and a button on the card that says "Details" which links to hax.psu.edu
- Make the image a fixed size via height / width and ensure the card is no bigger than 400px wide (height is weird in CSS, ignore height)
- Use the Border, Margin, and padding attributes in order to space the card to visually be appealing (the internet can help influence something to model, try making things 8px and then 12, then 16 to find what you like, ratios are key)
- Add a media query that only shows the details button when the screen is smaller than 800px (generally a small tablet) but larger than 500px (phone)
- Add a media query that scales the card (and image / items within) when on a screen smaller than 500px (generally considered phone)
- Include the link to this codepen in your gist. If you found particular websites helpful from a tutorial perspective on any of these specific requirements, then include them so we can share with the class.


Submit the link to your gist in Canvas which includes the Part 1 and Part 2 codepen links + any written questions answered + a picture of the mock up you were trying to model the card off of.

> EVERYTHING BELOW HERE IS SUBJECT TO CHANGE
# EVERYTHING BELOW HERE IS SUBJECT TO CHANGE
> EVERYTHING BELOW HERE IS SUBJECT TO CHANGE

## Week 3: Code Review
- We'll dig into the code written the previous week and see different ways of solving the same problem
- I will generate the button and explain how I would approach the card
- I'll do that mean thing where I call out group numbers and ask for answers to things
- You'll work with your partner to implement specific changes brought up in class

- Amazing CSS minion - https://codepen.io/AsyrafHussin/pen/wXjpyB

### JS Fundamentals
- How JS can access and modify HTML and CSS
- VanillaJS vs jQuery, Event Loop and how JS works
- Let's look at template literals (we'll use them later on)
 - I need to learn about them, so Mozilla docs - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals#tagged_templates
   - https://codepen.io/btopro/pen/ExpNyQx?editors=1111 - let's see how this can be used
     - https://codepen.io/btopro/pen/ZEjBObq?editors=1111 - follow up
- Homework watching:
  - https://www.youtube.com/watch?v=cM9KTKQ_4H0
  - https://www.youtube.com/watch?v=yORXfAb2Gvo

## Week 4-5: JS Ecosystem
- Tooling, how people work in industry, different projects (high level)
- Hello world a palooza. Set up a working deployed copy of each, review the code on GitHub. What are the similarities, what are the differences in repo structure? Look at the syntax of a js/template file from each. What is vanilla and what seems to be library specific?

## Week 6-8: Web components (project 1)
- Why web components, understanding how Wcs interplay with other libraries, who’s using them and why
- OpenWC specifically running through the cli and making a new project to collaborate on GitHub. Reading the lit docs
- CSS in ShadowRoot, prop drilling, leveraging existing packages
- Mid-term
- **Thursday prior to spring break there is no class**

## Week 9: Spring Break

## Week 10-11: Micro frontends (project 2)
- Publishing to NPM
- Vercel and project publishing and communication
- Creating an API endpoint to return data
- Creating a basic web component to render data from an end point using fetch to obtain information

## Week 12 – 16: Final Project
- Final projects laid out. Lectures / lessons / code reviews still happen but are more focused on ways of helping pairs complete the project in question.
- Scope / requirements of each project will vary. Students will pick from one of a variety of options
- https://github.com/elmsln/issues/labels/7B
- Check ins / progression expectations each week
- MobX / State management practice
- Routing
- localStorage
- Peformance enhancements

## Week 17: Final project due Tuesday of Finals week
- Class held for last minute office hours / debugging
