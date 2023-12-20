# Frontend Mentor - Interactive rating component solution

This is a solution to the [Interactive rating component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screen qshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Select and submit a number rating
- See the "Thank you" card state after submitting a rating

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

- I first started with building the structure of the project swith HTML
- Next I defined the css styles
- Lastly i connected everything together with JS andmade sure when i pressed "submit" the first part of the form vanished and only the second part of the form was displayed

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Vanila JS

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html

```

```css
This psudoe element adds a default margin of 0,
padding of of 0 aand borderbox to my project *,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

```js
This code mremoves the hidden property on my "thankyou" message bring ing onto the page and removes the rate message from the page. It does this when i click the submit button

submitButton.addEventListener("click", () =>{
  thanksContainer.classlist.remove("hidden")
  mainContainer.style.display = "none"
})

When using .querySelecter to select a class always remeber to start the class with "." as you would with css

Use .getElementByID to select an id when naming a const
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

- Continue working on CSS and JS documentation

### Useful resources

- [Example resource 1](https://www.youtube.com/watch?v=cQnUopEeZgw) - This video helped me with the thinking process of the project

## Author

- Website - [Durand Dyer](https://github.com/daebecodin)
- Frontend Mentor - [@daebecodin](https://www.frontendmentor.io/profile/daebecodin)

## Acknowledgments

[my-boy-josia](https://github.com/jlucas10)
