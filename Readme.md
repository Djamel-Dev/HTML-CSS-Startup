> ## Prepare your project files

1. Create the main folder CSS JS and Asset and html file.
2. in CSS folder create your css file.
3. in CSS folder create css file called [normalize.css](https://github.com/necolas/normalize.css/blob/master/normalize.css) for reset the default css parameters.
4. in JS folder create your js file.
5. Finally linked with html file by using this code line:

- in head tag put `<link rel = "stylesheet" href = "./CSS/normalize.css" />`.
- in head tag again put `<link rel = "stylesheet" href = "./CSS/style.css" />`.
- in last line in body tag put `<script src = "./JS/script.js"></script>`.

> ## Include Google Font

1. Click this link [Google fonts](https://fonts.google.com/).
2. Choose your fonts are you want.
3. Then select the different weight.
4. Copy the html links are generated and put it them in the head tag.

- Example:
  `<link rel="preconnect" href="https://fonts.googleapis.com">`
  `<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>`
  `<link href="https://fonts.googleapis.com/css2?family=Marhey:wght@400;500&family=Roboto:ital,wght@1,100;1,300&display=swap" rel="stylesheet">`

5. Copy the css code are generated and put it them in css code (body selector).

- Example:
  ` p { font-family: 'Marhey', cursive; font-family: 'Roboto', sans-serif; }`

> ## Include the icons

> > ### In my project i use [fontawsome](https://fontawesome.com/) open source icons.

You can use any icon framework in the same way.

> > > #### Prepare Files

1. Go to [fontawsome.com](https://fontawesome.com/).
2. Then download fontawsome packages [click hir](https://github.com/FortAwesome/Font-Awesome).
3. Then extract the zip file than copy the **Webfont** folder and put it them in your project.
4. in fontawsome go to css folder an copy all.min.css and put it them in your project (CSS folder).
5. in fontawsome go to js folder an copy all.min.js and put it them in your project (JS folder).

> > > #### Call Files

6. in last line in body tag put `<script src = "./JS/all.min.js"></script>`(your html file).
7. in head tag put `<link rel = "stylesheet" href = "./CSS/all.min.css" />` (your html file).

> > > #### Test icons

1.  Go to [fontawsome.com](https://fontawesome.com/) and choose a free icon and copy the html code example: `<i class="fa-solid fa-globe"></i>`.
2.  put it them in your html file.
    - Note: this icons used like a text for example you can change the color using this code in css : i {
      color: red;
      }

# **Good Luck**
