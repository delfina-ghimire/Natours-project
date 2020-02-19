# Principle

Three pillars of efficient html and css

1.  Responsive Design

- Fluid Layouts
- Responsive & flexible images
- Media Queries
- Correct Units
- Desktop first vs Mobile first

2.  Maintainable and scalable code

- clean
- Easy-to-understand
- supports future growth
- resuable
- css architecture to organize files
- naming convention: BEM
- structured HTML

3.  Web Performance

- less HTTP requests
- DRY code
- compress code
- Use CSS preprocessors
- Less image & compressed image whenever necessary

## Concepts used:

1. COMPONENT-DRIVEN DESIGN

- components are building blocks that we use to build our interfaces.
- Modular Building Blocks that make up interfaces held together by layout of page.
- Re-usuable across intra and inter projects.
- Independent, allowing us to use them anywhere on the page.

2.  BEM - Block Element modifier
    eg:
    block{}
    block**element{}
    block**element--modifier{}

        Block: Stand alone component that is meaningful on it's own.

        Element: Part of a block that has no standalone meaning.

        Modifier: A flag that we can put on a block or element in order to make         them different from regular block or an element.

3.  7-1 pattern
    It is CSS architect to create logical folder or file structure introduced by Hugo Grauod for our CSS where :

- 7 different folders for partial sass files (or less depending on size and scope of project)
- 1 main Sass file to import all other files into a compiled css stylesheet.

The 7 folders:
i. base/
for basic product definations
ii. components/
one file for each component
iii. layout/
for Overall layout of project
iv. pages/
for styles for specific pages of the project
v. themes/
for different visual themes
vi. abstracts/
for codes that doesn't output any css such as variables and mixins
vii. vendors/
for third party css

## What I learned

advance CSS functionalities
propper way to use commomly used css functioanlities
css animation and really handy css animations
pseudo classes:
:link - use in the links
how css works behind the scenes i.e how CSS is processed in browser
building custom grid
Advanced Selectors
