# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Order summary card solution](#frontend-mentor---order-summary-card-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
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

- See hover states for interactive elements

### Links

- Live site URL: https://ayoub-ahabchane.github.io/order-summary-component-main/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

This challenge taught to me that, in order to make steady progress, it is vital for the developer to prepare themselves mentally, and take time to develop a thorough and structured approach where concerns are separated, so that they are not boggled down mid-way by some conceptional detail that they could have addressed early on. Ultimately, coding is only the final lap in the race.

I also got to practice Grid after spending countless hours watching Jen Simmons preach about it. I know, there improvements to be made but hey, this is my first time so cut me some slack.

![](/screenshots/grid-screenshot.jpg)

To see how you can add code snippets, see below:

```css
.plan-info {
  display: grid;
  border-radius: 0.8em;
  grid-template-columns: max-content 1fr max-content;
  row-gap: 0.3em;
  column-gap: 1.2em;
  padding: 1.5em 1.4em;
  margin-bottom: 2em;
  background-color: var(--primary-3);
}

#music-icon {
  grid-column: 1 / 2;
  grid-row: 1 / 3;
  align-self: center;
}

.plan-tier {
  grid-column: 2 / 3;
  grid-row: 1 / 2;
  align-self: flex-end;
  font-weight: 900;
  color: var(--neutral-3);
}

.plan-pricing {
  color: var(--neutral-2);
  grid-column: 2 / 3;
  grid-row: 2 / 3;
  align-self: flex-start;
}

.plan-change {
  grid-column: 3 / 4;
  grid-row: 1 / 3;
  align-self: center;
  font-weight: 700;
  color: var(--primary-2);
}
```

### Continued development

I still have a long way to go in speaking fluent HTML/CSS. Thankfully, I came across Frontend Mentor just in time. The variety in the types of chanllenges available will help me highlight the gaps in my foundational knowledge that will make the process of translating my ideas into code a lot more seamless.

### Useful resources

Jen Simmons and Kevin Powell are my main sources of knowledge thus far. Check out their youtube channels as I'm sure there's something there for you.

## Author

- Frontend Mentor - [@ayoub_ahbchane](https://www.frontendmentor.io/profile/ayoub-ahabchane)
- Twitter - [@ayoub-ahabchane](https://www.twitter.com/ayoub-ahabchane)

## Acknowledgments

Love you all <3
