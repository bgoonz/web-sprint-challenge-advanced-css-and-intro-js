
# Sprint Challenge: Advanced CSS and Intro to JavaScript - Influential Artists




## Introduction

In this challenge, you will use a data set of artists to build an "influential artists" webpage. This data comes from a set of "50 influential artists" on [Kaggle](https://www.kaggle.com/ikarus777/best-artworks-of-all-time). We have reduced the data to just 20 artists to make it slightly easier to work with. You are free to work with the full data set as a stretch goal.

### Commits

Commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question. In addition, you may also review these questions with your mentor)

Please answer the following questions below, you may edit the readme file to include your answers below the question.

1. How would you describe acessibility on the web to someone new to programming?


> Wenb design is no longer a fringe area of technology made by programmers for programmers. Today the user base of the web counts  blind, color blind, people who are otherwise visually impared, as well as those who are Deaf or hard of hearing, in addition to people coping with physical or mental disibilities among their ranks. In this ever evolving ecosystem we can no longer rely on color to be the driving force in sharing information. We must also take into account the content of a picture rather than assuming it will speak for it's self in the face of ever greater adoption of screen readers as a means to consume online media. These considerations are just the tip of the iceberg but the fact of the matter is that web developers must be fully cognicent of these considerations in order to provide a quality web experiece. 


2. Talk about 3 different things you can do to ensure your website is accessible. 


1.) Use the alt attribute to describe the content of images.

2.)Ensure sufficient contrast between text and it's background so that color-blind users may still discern the shape of text if not the color.

3.)Make your website navigation formulaic and predictable so that anyone who frequents other websites will not have to adjust their mental model of website structure to interact with your product.



3. How would you explain the concept of a variable to someone new to programming?

In my mind a variable is a sort of reference or identifier used to refer to the state in computer in a certain location in memory. In reality these locations or buckets if you will are referenced by hexidecimal numbers and ultimatly in binary to the transistors of the computer but in order to productivly interact with them human developers have implemented a layer of abstraction between the raw memory addresses referenced in machine code and the arbitrary variable names given to them by programmers developing in a high level language.



4. What is the purpose of using functions in code?

Functions allow us to isolate a simple repeatable block of code and use it to preform a dedicated task whenever nessicitated by the design process regardless of the sequence of steps undertaken leading up to it's invocation. Functions provide modularity (DRY code) where as the alternative would be repeating the logical steps dictated by the function every single time it's dedicated purpose arises in the overall code base.




You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set-Up

Follow these steps to set up your project:

1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
NOTE: Tests will run for the JavaScript portion of this challenge only
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test:watch` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Task 2a:  Minimum Viable Product - Responsive Design

*Before you jump in, take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built. During this time, [Review the provided design files](design/). You have been provided all content necessary in the [index.html file](index.html) and basic styling in the [index.css file](css/index.css).*

* [ ] Add a viewport meta tag to the head of your index.html page.
* [ ] Add responsive breakpoints to your code for 500px such that your styles match the [mobile design file](design/Mobile.png).

### Task 2b: Minimum Viable Product - JavaScript

Navigate to `index.js` and complete the MVP challenges. Note that you need to scroll past data (or collapse data in VScode) to find the challenges below.

### Task 3: Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ ] Website is responsive at multiple breakpoints and looks good in-between breakpoints because student is using responsive units of measurement where appropriate. Student is using most semantic HTML for each element on page and has included ARIA roles where applicable (More research may be required to implement ARIA roles)  
* [ ] Student demonstrates and can explain a deep understanding of basic programming concepts when walking Team Lead through the explanation of their code.
* [ ] Use advanced array methods (.map, .reduce, .filer) to refactor your MVP code (create an array of all artists born in the 1900s with .filter, for example) - do this seperate from your MVP tasks


## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Styling with HTML and CSS](https://www.w3schools.com/html/html_css.asp)

## Submission format

Please see canvas for cohort specific submission instructions 
