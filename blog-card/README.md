# Blog Card (HTML + CSS)

A small UI challenge built with **only HTML and CSS**.  
The goal is to practice **semantic HTML**, **Flexbox layout**, and **card styling** (spacing, border radius, shadow, typography) plus **button states** (hover + focus).

## Screenshot

![Result Screenshot](/blog-card/img/result.png)

## Built With

- HTML5
- CSS3
- Google Fonts: Noto Sans

## What I Practiced

- Using **semantic HTML** for meaningful structure:
  - `article` for the card container
  - `figure` for the image media section
  - `header` for the badge + title grouping
- **Flexbox** for layout and spacing:
  - column layout with `gap`
  - aligning button text + icon
- Card UI styling:
  - padding + spacing (`gap`)
  - border radius
  - box shadow
  - responsive image with `object-fit: cover`
- Button interactions and accessibility:
  - hover styles (color + underline)
  - keyboard focus style using `:focus-visible`
  - note: Sass-style nesting (`&:focus-visible`) requires a build step, so plain CSS uses full selectors
