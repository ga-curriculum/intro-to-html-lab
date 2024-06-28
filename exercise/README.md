# ![HTML Lab - Exercise](./assets/hero.png)

## Introduction

This lab provides an opportunity to practice creating and nesting HTML elements, along with gaining more familiarity with how block and inline elements interact in the browser. 

### A quick note before you dive in

If you get stuck during the lab, we recommend revisiting the lesson materials first. They're designed to provide you with the information and examples that will help you complete the exercises.

## Lab Exercises

Before we get started, let's set up our boilerplate. Inside of `index.html`, type a `!` and press `Tab` to create the standard HTML boilerplate. Update the document's title to "HTML Lab."

### Exercise 1: Create a header

Inside the page's `body`, create a new `header` element. This `header` element should contain: 
- an `h1` with the text "This is a title!"
- an `h2` with the text "This is a subtitle!"

### Exercise 2: Create a navigation bar

Below the `header`, create a new `nav` element. This `nav` element should contain the following anchor elements: 
- a link to [https://developer.mozilla.org/en-US/](MDN's home page) with the content text "MDN".
- a link to [https://github.com/](GitHub's home page) with the content text "GitHub".
- a link to [https://generalassemb.ly/](General Assembly's home page) with the content text "General Assembly".

### Exercise 3: Create a section for a button

Below the `nav`, create a new `section` element. This `section` element should contain: 
- an `h3` element with the text "This section has a button!"
- a `p` element with the text "This is a button:", with a `button` element that displays **inline** (The button should occupy the same line as the preceding text). The `button` should have the text "Click me!", but it does not need to preform any actions when clicked. 

### Exercise 4: Create a section for an unordered list

Below the previous `section`, create a new `section` element. This new `section` element should contain: 
- an `h3` element with the text "This section has a list!"
- a `ul` element, which contains three list elements: 
  - The first `li` element should contain the text "This is the first list item". 
  - The second `li` should contained the text "This is the second list item". 
  - The third `li` should contained the text "This is the last list item and it has a link". Wrap the word "link" in an anchor element, and give it an `href` attribute with the url of [http://www.google.com](Google's home page). 

### Exercise 5: Create nested divisions

For this exercise, we'll be using [Lorem Picsum](https://picsum.photos/) to generate placeholder images. By perusing the documentation, we can see that grabbing a random image from the site is fairly straightforward. We concatenate the base url `https://picsum.photos/` with a number that represents a pixel size, such as `500`. 

We can then add that URL to the `href` attribute of an `img` element, and we'll get back a randomized image that is 500x500 pixels in size. 

Below the previous `section`, create a `div` element. This new `div` element should contain two `div` elements. 

The first child `div` should contain: 
- a `p` element with the text "These photos are inside a nested div!
- two images that grab a 200x200 pixel photo from Lorem Picsum. Each `img` element should also include an `alt` attribute with the text "placeholder photo". 

The second child `div` should contain: 
- a `p` element with the text "This larger photo is inside another nested div!"
- an image that grabs a 400x400 pixel photo from Lorem Picsum. The `img` element should also include an `alt` attribute with the text "large placeholder photo"

### Exercise 6: 

Below the parent `div` element, create a `footer`. This `footer` element should contain: 
- an `h4` with the text "I'm a footer". 
- a `p` tag with the text "Author: ", followed by a link to your personal GitHub account. 