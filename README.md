# Js Clock

<!-- Summary -->

<!-- This is a solution to the [NameOfTheProject]( URL of it). Frontend Mentor challenges help you improve your coding skills by building realistic projects. -->

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

<!-- ![](./DesignScreenshots/DesktopScreen.png)
![](./DesignScreenshots/MobileVersion.png) -->

### Links

- Live Site URL: [Live Site URL:](https://errazakallah-clock-js.netlify.app/)

## My process

==> HTML :
Created circle with with classes [clock => clock face => hand * 3 + hand for each task]

==> CSS :
Styled the circle and the hands to make them inside the clock
applied transform : rotate (deg) !! the place of transform-origin by default is 50% of the x axis
applied transform-origin : 100%
applied transform : rotate (90deg) to make it looks nice and at 00:00 by default
applied transition : all 0.4s + transition-timing-function : to something make it looks nice

==> Js
created setDates() + setInterval(function, time in milliseconds) for this function
setDates => get the date => get seconds
now we have seconds! what we should do to make them show up on screen! => turn them to degrees :)
secondsDegrees => (( seconds / 60) \* 360) + the offset which is 90°
select the second-hand => .style.transform = `rotate (#{secondsDegrees})`

### Built with

<!-- Info -->

- Mobile-first workflow
- Semantic HTML5 markup
- CSS custom properties
- Flex box

### What I learned

<!-- I learned more about  -->

## Author

<!-- - Website - [](NotAvailableForNow) -->

- Twitter - [@Rezzak_48](https://twitter.com/Rezzak_48)
