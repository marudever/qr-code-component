# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Links

- [My Soludtion](https://github.com/marudever/qr-code-component)
- [Live Site URL](https://marudever.my.id/qr-code-component/)

## My process

### Built with

- HTML
- CSS Flexbox
- Mobile-first workflow

### What I learned

I'm using Flexbox to make the content/qr-component align both horizontally and vertically. Also to make the component consistent in mobile and desktop, I just using max-width here. 

How I make the component sizes the same:
```html
<section class="container">
    <div class="qr-component">
      <div class="qr-component-wrap">
        <!-- img and text -->
      </div>
      <div class="attribution">
        <!-- .... -->
      </div>
    </div>
  </section>
```
```css
.qr-component-wrap {
    max-width: 370px;
    /* .... */
}
```
and here the code for making the component align center horizontal and vertical:
```css
.qr-component {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
```

### Continued development

Well there is two things that still not comfortable:
1. I just feel my HTML could be more less
2. In my CSS, I think there could be another way to make it easier.
Summary, sometimes when I write the code, I always think a better solution with less code. But I don't know what that is, because I also think this is the best solution that I can make.

## Author

- Frontend Mentor - [@marudever](https://www.frontendmentor.io/profile/marudever)
- GitHub - [@marudever](https://github.com/marudever)
- Twitter - [@marudever](https://www.twitter.com/marudever)