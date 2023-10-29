# Frontend Mentor - Results summary component solution

Click here[Results summary component challenge on Frontend Mentor](https://monumental-speculoos-59ea87.netlify.app) to view my site!!!

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshot

![Mobile view](<Screen Shot 2023-10-29 at 6.14.29 PM.png>)
![active-state button](<Screen Shot 2023-10-29 at 6.14.38 PM.png>)
![Desktop view](<Screen Shot 2023-10-29 at 6.14.13 PM.png>)

### Links

- [Live Site URL](https://monumental-speculoos-59ea87.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Below are clearer class names at a glance. Still a work in progress, but I'm improving

```html
<div class="desktop-container">
  <section class="results-section">
    <header class="results-section-header">Your Result</header>
    <div class="results-section-score">
      76 <span class="out-of-total">of 100</span>
    </div>
    <div class="results-section-text-container">
      <div class="results-section-text">
        <div>Great</div>
        <span class="results-section-percentage">
          You scored higher than 65% of the people who have taken these tests!
        </span>
      </div>
    </div>
  </section>

  <section class="summary-section">
    <h3 class="summary-section-header">Summary</h3>

    <div class="reaction-category">
      <span
        ><img src="./assets/images/icon-reaction.svg" alt="bolt-icon" />
        Reaction</span
      >
      <span class="summary-section-test-scores"
        >80<span class="out-of-total"> / 100</span></span
      >
    </div>

    <div class="memory-category">
      <span>
        <img src="./assets/images/icon-memory.svg" alt="brain-icon" />
        Memory</span
      >
      <span class="summary-section-test-scores"
        >92<span class="out-of-total"> / 100</span></span
      >
    </div>

    <div class="verbal-category">
      <span>
        <img src="./assets/images/icon-verbal.svg" alt="speech-bubble-icon" />
        Verbal</span
      >
      <span class="summary-section-test-scores"
        >61<span class="out-of-total"> / 100</span></span
      >
    </div>

    <div class="visual-category">
      <span>
        <img src="./assets/images/icon-visual.svg" alt="eye-icon" />
        Visual</span
      >
      <span class="summary-section-test-scores"
        >72<span class="out-of-total"> / 100</span></span
      >
    </div>
    <button class="continue-button">Continue</button>
  </section>
</div>
```

Below is some CSS that I was new to using: gradients

```css
.results-section {
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  background: linear-gradient(
    180deg,
    rgba(119, 85, 255, 1) 20%,
    rgba(47, 44, 233, 1) 100%
  );
  height: 45rem;
  border-radius: 0 0 70px 70px;
  text-align: center;
}
```

### Continued development

Working on using relative units of measurement rather than hardset ones for ease of use on diff screen sizes

### Useful resources

- [CSS Tricks](https://www.css-tricks.com)

## Author

- Website - [Click here to view site](https://monumental-speculoos-59ea87.netlify.app)
- Frontend Mentor - [@LBuchananCates](https://www.frontendmentor.io/profile/lbuchanancates)
