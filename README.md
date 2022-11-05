<img src="app/images/banner.svg" style="width:100%">
.





# Webook - Single Page Education Website

This is a solution of a [Thapa Technical Codefest](http://thapacodefest.thapaonlineclass.com/).
The Problem Statement is to make a single page Online education website ( only frontend work ). I am Smruti ranjan nayak Btech 1st Year Studet in CSE Branch. I complete this problem below solution you saw every single function, code, and feature. in a few months, I had designed many components or websites, this is my first codefest or hackathon challenge to develop my skills.
<br/>
in this project, I learned many things as I had never designed or coded a FAQ section and I had designed this website in Figma first then I had code.


here is the [Figma file](Webook.fig)

<br/>

## 🖥️ Challenge Description : 

<br/>
This challenge is absolutely made for those who love to code websites and make the website look modern, sleek, user-friendly, responsive n many more. You have to create a single page of the Online Education Website using any preferred language you want. You have to only code the front-end part, no back-end code is needed.

Ex. Navbar, Header section, Services/Features, Courses, FAQ, Contact, Footer, etc.

- Single Page Online Education Website
- Only Front-End Code (Any Language)
- Make it responsive on all devices

<br/>

# 🌍 Solution : 

<br/>

### Demo : [link](https://webook.netlify.app/)

<br/>

## 👩‍💻 Tech Stack

**Client:** 
```Html, Css , Scss and Javascript```

**Server:** ``` netlify```

## 📁 File Strutcture : 

```
|   index.html // Index Html File 
|   README.md  // Readme File 
|   Webook.fig // Figma File 
|
\---app // All Files or Images 
    +---images
    |   |   ba1.png
    |   |   causal.png
    |   |   menu-alt.png
    |   |   menu-x.png
    |   |   preloader.gif
    |   |
    |   \---logo
    |           Favicon.svg
    |           logo.svg
    |
    +---js
    |       script.js // Main Javascript file 
    |
    \---scss
        |   style.css // Main Style CSS File
        |   style.css.map
        |   style.scss // Main Style SCSS File 
        |
        +---components // Here present all of components 
        |       _about.scss
        |       _banner.scss
        |       _classes.scss
        |       _contact.scss
        |       _courses.scss
        |       _expert.scss
        |       _faq.scss
        |       _features.scss
        |       _footer.scss
        |       _header.scss
        |       _index.scss
        |       _preloadder.scss
        |       _subscribe.scss
        |
        +---global // Here present all Default Html code and Color Codes 
        |       _boilerplate.scss
        |       _colors.scss    // All Colours file 
        |       _fonts.scss     // Font File 
        |       _images.scss    // Images url File 
        |       _index.scss
        |       _typography.scss
        |
        \---util
                _breakpoints.scss // Media Query Function 
                _functions.scss   // Some function 
                _index.scss
```

<br/>


## 🌐 Color Section

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Primary Color | ![#08d9d5](https://via.placeholder.com/10/08d9d5?text=+) hsl(179, 93%, 44%) |
| Blue Color | ![#00aab3](https://via.placeholder.com/10/00aab3?text=+) hsl(183, 100%, 35%) |
| Light Blue Color | ![#72cacf](https://via.placeholder.com/10/72cacf?text=+) hsl(183, 49%, 63%) |
| Secondary Color | ![#393e46](https://via.placeholder.com/10/393e46?text=+) hsl(217, 10%, 25%) |
| Background Color | ![#212730](https://via.placeholder.com/10/212730?text=+) hsl(216, 18%, 16%) |
| White Color | ![#ffffff](https://via.placeholder.com/10/ffffff?text=+) hsl(0, 0%, 100%) |
| Darkish White Color | ![#c7c7c7](https://via.placeholder.com/10/c7c7c7?text=+) hsl(0, 0%, 78%) |

```css

:root{
    --primarycolor:hsl(179, 93%, 44%);
    --blue:hsl(183, 100%, 35%);
    --lightblue:hsl(183, 49%, 63%);
    --secondarycolor:hsl(217, 10%, 25%);
    --Backgroundcolor:hsl(216, 18%, 16%);
    --white:hsl(0, 0%, 100%);
    --darkishwhite:hsl(0, 0%, 78%);
}

```

- if you intrest change color code as you prefer then go the `    app > scss > global > colors.scss  `

<br/>

## 🔠 Font Section : 

- in this project i had used [Outfit](https://fonts.google.com/specimen/Outfit)
    - Font-weight : 400 600 800;

```html
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;600;800&display=swap" rel="stylesheet">
```

```css
:root{
    --outfit:'Outfit',sans-serif;
}
```

- if you intrest change font family as you prefer then go the `app > scss > global > fonts.scss`

<br/>

## 🌄 Images :
<br/> 

```css
:root{
    --toggleimg:url(../images/menu-alt.png);
    --toggleactiveimg:url(../images/menu-x.png);
    --preloadder:url(../images/preloader.gif);
    --featuresimage:url('https://images.unsplash.com/photo-1605711285791-0219e80e43a3?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1469&q=80');
}
```

<br/>

# 💻 Screenshot : 

![Screenshot](screenshot-pc.png)


<br/>

