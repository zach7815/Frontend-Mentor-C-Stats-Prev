# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./snaphots/desktop_screenshot.png)

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Before this project I hadn't really played around with the pseudo element ::after or added a gradient overlay to an image using CSS.
To see how you can add code snippets, see below:

```html

```

```css
.cover {
  position: relative;
}

.cover::after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 99.2%;
  background: linear-gradient(rgba(170, 92, 219, 0.5), rgba(170, 92, 219, 0.5));
  opacity: 0.75;
  border-radius: 0 5px 5px 0;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

To continue my develoment I think I next need to look at more complicated used cases of flexbox, and build some projects using grid. Then move on building a project that requires Javascript.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Centering anything with CSS](https://www.freecodecamp.org/news/how-to-center-objects-using-css/) - This resource helped me remind myslef how to center things with CSS for this project.

- [Applying a gradient cover to images](https://www.youtube.com/watch?v=mT10ZJdlh9Y) - This is a short video, that showed me one way of how to apply a gradient colour to an image.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)
