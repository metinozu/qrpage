# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
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

### Screenshot

![Alt text](../Screenshot_1.png)

## My process

### Built with

- HTML5 
- CSS

### What I learned

It is my first challenge and I am starting to learn how to code in HTML/CSS and also learning why I should use packages because just HTML/CSS making it hard to write. It was a simple project -I have some mistakes tho- so I did not use any packages to make it faster.

Also It is my first time to write a README.md and I am figuring out why this things are important

In this challenge I learned how to use pictures and how to use font styles.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="style.css">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div class="bg">

        <div class="div">
            <img class="image" src="C:\Users\ah-me\Desktop\qr-code-component-main\images\image-qr-code.png" alt="qr">
        </div>
        <div class="h1">
            <h1>Improve your front-end skills by building projects</h1>
        </div>
        <div class="h2">
            <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
        </div>
    </div>
</body>
</html>
```
```css
body{
    background-color: lightblue;

}

.image{
    border-radius: 30px;
    width: 360px;
    height: 360px;
    position: relative;
    margin: auto;
    padding: 10px;
}

.bg{
    width: 380px;
    height: 570px;
    background-color: white;
    position: relative;
    margin: auto;
    border-radius: 30px;
}

.div{
    position: relative;
    margin: auto;
}

.h1{
    font-family: 'Outfit', sans-serif;
    text-align: center;
    font-weight: 700;
}

.h2 {
    color: gray;
    font-family: 'Outfit', sans-serif;
    text-align: center;
    font-size: 15px;
    font-weight: 400;
}
```


### Continued development

I am still not comfortable with using CSS. I am doing my designs on Figma and it is way easier. But when it is about the making menu and basic websites HTML/CSS could make it easier to use.

### Useful resources

- [Example resource 1](https://chat.openai.com/chat) - This is ChatGPT. I am afraid to lose my job to this code but it helped me so much when I need some help. About text size and aligns I did not figured them easily. So I asked to the ChatGPT and it helped me

## Author


- Frontend Mentor - [@metinozu](https://www.frontendmentor.io/profile/metinozu)
