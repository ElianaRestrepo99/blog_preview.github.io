# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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

--it's a preview card about a greg hoper blog. looking and observing the texture of the card giving it life and good presentation.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./design/Actives-status.png.)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

--My development process for the graphics card was very subtle, learning to give color lines, shadows, image textures.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->

  <link rel="icon" type="image/png" sizes="32x32" href="./assets/images/favicon-32x32.png">

  <link rel="stylesheet" href="./style.css">
  
  <title>Frontend Mentor | Blog preview card</title>
 
</head>
<body>

  <section class="container">
      <div>
        <img src="./assets/images/illustration-article.svg" alt="">
      </div>

      <div>
        <h2> Learning</h2>

        <p>Published 21 Dec 2023</p>

        <h1>HTML & CSS foundations</h1>

        <p class="published-at">These languages are the backbone of every website, defining structure, content, and presentation.</p>

        <ul>
          <li><img src="./assets/images/image-avatar.webp" alt=""></li>
          <li>Greg Hooper</li>
        </ul>
        
      </div>
  </section>

```css

@import url('https://fonts.googleapis.com/css2?family=Figtree:ital,wght@0,300..900;1,300..900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Figtree:ital,wght@0,300..900;1,300..900&display=swap');

*{
    padding: 0; 
    margin: 0;
    box-sizing: border;
}

ul{
    list-style-type: none;
}


body{
    background-color: hsl(47, 88%, 63%);
    padding: 3rem 1rem;
    font-family: 'Figtree';
}

@media(min-Width: 768px){
    body{
        padding: 0;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        height: 100vh;
    }
}

.container{
    max-width: 350px;
    margin-inline: auto;
    background-color: #fff;
    padding: 1rem;
    border: 1px solid black;
    border-radius:  1rem;
    box-shadow: 10px 10px 0px black;
}

.container div:first-child img{
    width: 100;
    border-radius: 1rem;
}

.container div:nth-child(2) h2{
    display: inline-block;
    background-color: hsl(47, 88%, 63%);
    font-size: 1rem;
    padding: 3px 8px;
    border-radius: 3px;
    margin: 1.5rem 0 1rem;
}

.container div:nth-child(2) p.published-at{
    margin-bottom: 1rem;
    color: black;
}

.container div:nth-child(2) h1{
    margin-bottom: 1rem;
}

.container div:nth-child(2) h1:hover{
   color:  hsl(47, 88%, 63%);
   cursor: pointer;
}

.container div:nth-child(2) p{
    margin-bottom: 2rem;
    color: hsl(0, 0%, 50%);
}

.container div:nth-child(2) ul{
    display: flex;
    align-items: center;
    gap: 1rem;
}

.container div:nth-child(2) ul li:nth-child(2){
    font-weight: bold;
    font-size: 1rem;
}


.attribution { 
    font-size: 16px; 
    text-align: center; 
    margin-top: 1rem;
    color: rgb(14, 8, 8);
}

.attribution a {
     color: hsl(0, 9%, 40%); 
    }



```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
