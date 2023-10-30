# Frontend Mentor - Results summary component solution

[Click here](https://monumental-speculoos-59ea87.netlify.app) to view my site!!!

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Use the local JSON data to dynamically populate the content

### Screenshot
<img width="378" alt="score card mobile view" src="https://github.com/LBuchananCates/results-summary-card/assets/100169368/824f13ba-7063-4d01-9f1c-5c987293a3fc">
<img width="869" alt="score card desktop view" src="https://github.com/LBuchananCates/results-summary-card/assets/100169368/a70c7025-bdf6-4d22-996c-d84ab7eeab7e">
<img width="366" alt="active state button" src="https://github.com/LBuchananCates/results-summary-card/assets/100169368/4c7324ed-a14e-4006-a0f3-c915eb58356c">

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
