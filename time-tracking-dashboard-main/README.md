# Frontend Mentor - Time tracking dashboard solution

This is a solution to the [Time tracking dashboard challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/time-tracking-dashboard-UIQ7167Jw). Frontend Mentor challenges help you improve your coding skills by building realistic projects.
## Table of contents

- [Frontend Mentor - Time tracking dashboard solution](#frontend-mentor---time-tracking-dashboard-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My Process](#my-process)
    - [Built with](#built-with)
    - [What I Learned](#what-i-learned)
    - [Continued Development](#continued-development)
    - [Useful Resources](#useful-resources)
  - [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Switch between viewing Daily, Weekly, and Monthly stats

### Screenshot

![](<./design/time-tracking-dashboard-webview(desktop).png>)

### Links

- Solution URL: [GitHub](https://github.com/AnshShrivastava70/Front-End-Challenges/tree/main/time-tracking-dashboard-main)
- Live Site URL: [Live](https://your-live-site-url.com)

## My Process

### Built with

- Semantic HTML5 markup
- Tailwind CSS for styling
- Flexbox & CSS Grid for layout
- Mobile-first workflow
- Vanilla JavaScript for interactivity
- JSON for dynamic data fetching

### What I Learned

This project helped me reinforce several important concepts, including:

- Using **semantic HTML tags** to improve accessibility and structure.
- Fetching data from a **JSON file** using the `fetch()` API and dynamically rendering content.
- Revisiting and applying concepts I had forgotten, such as **DOM manipulation, event handling, and working with Tailwind CSS classes dynamically**.
- Strengthening my understanding of **CSS Grid and Flexbox** for responsive layouts.

Here are a few code snippets that I’m proud of:

```html
<!-- Example of a semantic HTML structure -->
<article>
  <header>
    <h3>Work</h3>
    <button class="menu-btn">
      <img src="./assets/images/icon-ellipsis.svg" alt="menu" />
    </button>
  </header>
  <p>32hrs</p>
  <footer>Last Week - 36hrs</footer>
</article>
```

```js
// Fetching data from a JSON file and updating the UI dynamically
async function fetchData() {
  try {
    const response = await fetch("./assets/data.json");
    jsonData = await response.json();
    generateCards();
  } catch (error) {
    console.error("Error Fetching Data: ", error);
  }
}
```


### Continued Development  

This project helped me improve my skills in **semantic HTML, fetching data from a JSON file, and dynamically updating the UI using JavaScript**. However, there are still some things I want to work on:  

- **Better Handling of Fetch Requests** – Learning how to optimize API calls to make the app more efficient.  
- **Managing State in JavaScript** – Improving how I update and manage data in my projects.  
- **Using Tailwind CSS More Effectively** – Exploring more Tailwind classes to write cleaner code.  
- **Making My Projects More Accessible** – Ensuring buttons and other interactive elements work well for all users.  

I’ll focus on these areas in my future projects to keep improving.  

---


### Useful Resources  

- [MDN Web Docs – Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API) – Helped me understand how to get data from a JSON file.  
- [Tailwind CSS Documentation](https://tailwindcss.com/docs) – A great guide for styling with utility classes.  
- [JavaScript.info – Async/Await](https://javascript.info/async-await) – Made it easier to understand how to use async/await properly.  

These resources were very useful, and I’d recommend them to anyone learning JavaScript, APIs, and Tailwind CSS. 🚀  


## Author

- Frontend Mentor - [@AnshShrivastava70](https://www.frontendmentor.io/profile/AnshShrivastava70)
- GitHub - [@AnshShrivastava70](https://github.com/AnshShrivastava70)


