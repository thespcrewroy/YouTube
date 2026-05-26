# UI / UX Design Tutorial: Wireframe, Mockup & Design in Figma

<p align="center">
  <a href="https://www.youtube.com/watch?v=c9Wg6Cb_YlU">
    <img 
      src="https://img.youtube.com/vi/c9Wg6Cb_YlU/maxresdefault.jpg" 
      alt="Watch the video" 
      width="600"
    />
  </a>

## Wireframing
- A visual blueprint of how a website will work and the pages themselves
- Works as a schema for the functionality of a system
- You can sketch it on a piece of paper, an ipad, or on a software
- Keep a consistent header and footer throughout all webpages
- Avoid redundant markups or labels

### Terminology and Symbols
* **Hero Banner:** big gigantic image that runs behind the website
* **Slider Image:** dots at the bottom and arrows on the side
* **Image:** draw a box with a cross through it
* **H1/H2/H3 Header:** box that is scribbled in
* **Description:** a bunch of straight lines
* **Button:** represented with a rectangle and a ‘B’
* **Section:** large encompassing rectangle
* **Darker Color Section:** section drawing with diagonal lines accross top edge
* **Logo:** draw a clock

### Site Map
- Gives your website directions so you know what pages you are building
- Start with home page
- Write out the most core pages
- You can branch out subpages
- If some pages are linked to others, you can draw arrows to show that

<p align="center">
  <img src="https://github.com/thespcrewroy/YouTube/blob/main/assets/sitemap.png" alt="Sitemap" width="800" />
</p>

### Home Page
- Usually represents the design we are going to utilize for the rest of the pages
- Make the page at least 12 columns
- **Header:** Cntainst navigation information. Create basic representations of the logo and menu
- **About Us:** image, large title, and descriptions about the website, and button if the user wants to learn more
- **Testimonials/Sponsors:** title and images of various sponsors
- **Contact Form:** a heading, couple text boxes, and a button. Include a bit of information underneath about buisiness contacts (phone/email)
- **Footer:** darker color with copyright info

<p align="center">
  <img src="https://github.com/thespcrewroy/YouTube/blob/main/assets/home.png" alt="Home Page" height="600" width="300" />
</p>

### Features Page
- The page that really has to promote your product/website
- Contains more photos, text, and call to actions to engage the customer
- **Title Section:** below the hero banner and will eventually be themed

<p align="center">
  <img src="https://github.com/thespcrewroy/YouTube/blob/main/assets/features.png" alt="Features Page" height="600" width="300" />
</p>

### Contact Us Page
- Phone Number
- Email
- **Map:** points to the location of the company
- **Contact Form:** placed to the left of the map

<p align="center">
  <img src="https://github.com/thespcrewroy/YouTube/blob/main/assets/contact.png" alt="Contact Us Page" height="600" width="300" />
</p>

### Mobile Version
- A lot longer than the actual home page
- Add slightly different elements
- Add a button for the menu
- Add a second button for interaction to call or email the service/business

<p align="center">
  <img src="https://github.com/thespcrewroy/YouTube/blob/main/assets/mobile.png" alt="Mobile Page" height="600" width="200" />
</p>

### Navigation
- Draw arrows from one page to the other
- The bar in the home page title banner will take us to the features page
- The button in the “About Us” section will take us to the Features Paged

<p align="center">
  <img src="https://github.com/thespcrewroy/YouTube/blob/main/assets/navigation.png" alt="Navigation" height="800" width="900" />
</p>

## UI Layout

- More professional version of wireframe
- Closer step to creating a full website design
- Will not have:
  - colors
  - images
  - content
- We are designing the UI around Bootstrap framework’s row and column system
- The more content you put into a design, the more padding you want to have from the borders so that everything stays consistent

# Banner

## Figma Setup

- Create a new figma file:
  - drafts → “+” → new design file
- Name your file
- Create a new canvas:
  - Frame → Desktop → Desktop
- Change width and height to:
  - 1980 × 1980
- Change the name of the first layer to:
  - “Homepage”
- Copy paste your wireframe svg file and put it to the side of the canvas as a reference

## Grid Layout

- Layout Grid → Columns → change to 12
- Type → Center
- Width → change to 90
- Gutter → change to 15

## Slide Banner Box

- Box → Square → Drag over the canvas
- change box height to 800
- Change hex color to:
  - EEE

## Header Box

- Make it 930 by 60
- Make it go from 0 column to end of 9th column

## Circle Logo

- Make sure there is one column space between logo and header
- Circle logo is 2 columns wide
- Circle logo has equal length and width

## Logo Text

- Put it in center of the circle logo
- Make the font 48
- Change hex color to:
  - 999

## Grouping

- Group logo text and icon:
  - select text and icon and hit Command + G
- Rename the group to:
  - “Logo”

## Header Navigation

- Add the different section text to the header and evenly space them

## Active Navigation Box

- Create another box and put it over the home
- Make it same height as heading box but a width of 152
- Change hex color to:
  - 66666666
- Change “Home” hex color to complete white

## Chevron Icons

- Go to font awesome and download:
  - chevron-left-solid.svg
- Drag and drop the chevron left into the Figma
- Resize it to:
  - 40 × 64
- Put it to the far left
- Reduce its color to:
  - 33% opacity
- Copy and paste a 180 degree rotated chevron on the right

## Slider Dots

- Create a dot at the bottom to represent the slides
- Copy and paste 2 more dots spread apart by:
  - 10 pixels
- Make the first dot hex color:
  - 666666

## Hero Title Example Text

- Make it bold
- Make it 72 font
- Align it with last column on left side

## Hero Sub-Title Description

- Copy and paste Hero Title Example
- Move it below Hero Title Example
- Make it 42 font
- Make it regular weight
- Make it 66% opacity

---

# About Us

- Copy and paste rectangle from banner background below the banner background
- Change hex color to:
  - F1F1F1

## Image Placeholder

- Create a square frame to represent the image
- Make it 4 columns wide
- Place it at the center of the about us section on the left side

## Title & Subtitle

- Copy and paste hero title and subtitle text to the right of the square frame
- Allow a one column gap between it and the square frame
- Make the margin between title and subtitle less than before
- Make title 60 size

## Description

- Create a text box below subtitle and extend it till last column for description
- Copy lorem text into text box as a placeholder description

## Read More Button

- Copy the picture frame square
- Place it below the description
- Make its height 60
- Make it three columns in length

### Button Text

- Add “Read More” text onto button
- Make text white
- Make button:
  - “666666” color

## Finishing Touches

- Change the “About Us” section background to solid white
- Group entire About Us section together
- Change names of elements to make it more clearer which is which
- Lock the group into place
- Group the “Hero” section together excluding the header bar
- Group the header bar together as:
  - “Menu”
- Pull the logo outside the Hero section as we are going to reuse it in other pages

---

# Sponsors

- Increase height of page to:
  - 2600
- Copy and Paste “About Us” section to y-coordinate 1600
- Remove description and read more button
- Put the title and subtitle at the top of the section
- Center align the title and subtitle
- Make the image box the width of 2 columns
- Copy the box across from one side to the other
- Reduce section height to:
  - 490
- Apply the same tint as the hero section to sponsor section
- Increase background size to:
  - 630
- Center the title, subtitle, and image frames on the y-axis

---

# Footer

- Use the darker home box frame from the title bar as the frame for the footer
- Expand the canvas height to:
  - 3050
- Expand the footer height to:
  - 820
- Get the items/icons from Font Awesome

---

# Copyright

- Make a box frame at the bottom
- Set its height to:
  - 100
- Set its hex color to:
  - 333333

---

# Mobile Version

- Select a new frame and choose the latest iPhone Pro Max version

# Banner Page

- Remove the title bar and add a hamburger bar
- Remove the slider buttons as you can just use your fingers

- The rest of the mobile design is just copying over elements from the PC design but making it smaller and more akin to an iPhone UI

---

# Mockup

- Add in elements to personalize the UI Layout
