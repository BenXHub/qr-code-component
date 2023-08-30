# QR Code Component Challenge

This is a solution to the QR Code Component challenge on Frontend Mentor. Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of Contents

- [Overview](#overview)
- [Built with](#built-with)
- [Author](#author)

## Overview

![QR Code](images/DesktopQRCode.png)
![QR Code](images/MobileQRCode.png)

Improve your front-end skills by building projects. Scan the QR code to visit Frontend Mentor and take your coding skills to the next level.

## Built with

- HTML
- CSS

### Font

```css
@font-face {
    font-family: 'Outfit-ExtraBold';
    src: url('dist/fonts/Outfit-ExtraBold.ttf');
}

@font-face {
    font-family: 'Outfit-Light';
    src: url('dist/fonts/Outfit-Light.ttf');
}
```

### CSS Styles 

```css
* {
    margin: 0;
    padding: 0;
}

body {
    background-color: #6B8EAB;
}

.container {
    background-color: #FFFFFF;
    width: 18%;
    height: auto;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    padding: 20px 20px 10px 20px;
    border-radius: 20px;
}

.qrcode-image img {
    max-width: 100%;
    height: auto;
    border-radius: 10px;
    margin-bottom: 1rem;
}

.details {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
}

.details b {
    font-family: Outfit-ExtraBold, Arial, sans-serif;
    color: #00008B;
    font-size: 20px;
}

.details p {
    font-family: Outfit-Light, Arial, sans-serif;
    font-size: 15px;
    margin-top: 1rem;
    color: #D3D3D3;
}

.attribution {
    font-family: Outfit-Light, Arial, sans-serif;
    display: block;
    flex-direction: column;
    align-items: center;
    text-align: center;
    margin-top: 1rem;
    font-size: 12px;
}

.attribution a {
    text-decoration: none;
    color: #00008B;
}

@media (max-width: 600px) {
    .container {
        width: 80%;
        margin: auto;
    }

    .qrcode-image img {
        margin-bottom: 0.5rem;
    }

    .details b {
        font-size: 24px;
    }

    .details p {
        font-size: 18px;
    }
}
```

### Author

- Author - [Benjie Mondia](https://github.com/benjamineke)
- Challenge by [Frontend Mentor](https://www.frontendmentor.io?ref=challenge)