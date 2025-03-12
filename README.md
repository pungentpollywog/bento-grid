# Bento grid

![Design preview for the Bento grid coding challenge](./preview.jpg)

## Instructions 

- Fork and clone this project.
- Create a **dev** branch to work in.
- Follow the requirments listed below.
- Have fun!
- When you're ready, push up your changes and open an Merge Request (MR) requesting to merge your changes from the **dev** branch into your **main** branch.

## Requirements

- Create **bento.html** and **bento.css**
- Build out this bento grid and get it looking as close to the design as possible. 
  - Reference the `style-guide.md` for specifics on layout, colors, and typography. 
- Use CSS Grid to layout the grid.
- Make sure it looks good on different device sizes (at least mobile and desktop).
  - Bonus: design a grid for tablet size as well.
- Use semantic HTML elements.
- Use CSS Variables.

### Expected behaviour

The two components in the left column on desktop are placed at the bottom on mobile. This is a good opportunity to practice your CSS Grid placement skills.

### Hint

It's okay to mix layout modes (i.e. you may want to use a flex container within a grid track.)

### Using fonts

(See assets/fonts/ folder for DM Sans font.)

Here's an example of how you would add the font as a "font face" in your CSS. 

```css
@font-face {
  /* Declare it as a font-family */
  font-family: "DM Sans";
  src: url(./assets/fonts/DMSans-VariableFont.ttf);
}

body {
  /* using the new font family */
  font-family: "DM Sans";
}
```
### Media queries

[Targeting Media Features](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries#targeting_media_features)

[Range Syntax](https://css-tricks.com/the-new-css-media-query-range-syntax/)


## Where to find everything

Your task is to build out the project to the designs inside the `/design` folder. You will find both a mobile and a desktop version of the design. 

The designs are in JPG static format. Using JPGs will mean that you'll need to use your best judgment for styles such as `font-size`, `padding` and `margin`. 

All the required assets for this project are in the `/assets` folder. The images are already exported for the correct screen size and optimized.

There is also a `style-guide.md` file containing the information you'll need, such as color palette and fonts.


**Have fun building!** 🚀
