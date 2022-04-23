# Learning SASS, SCSS

- [x] Sass partials
- [x] Sass Variables and css custom properties
- [x] Sass and BEM
- [x] Sass mixins
- [x] Sass map
- [x] Sass functions
- [x] Nesting and BEM
- [x] Helper/Utility classes
- [x] px to rem converter function
- [x] px to em converter function

##  notes
- CSS variables are called custom properties
- CSS custom properties can be put in `html`, `:root`, and `body` selectors for global use
- you can manipulate css custom properties by javascript and you cannot do that with sass variables
- BEM : B => block, E => element, and M => modifier 
- BEM helps to make class names unique, and if you change the name of the block you don't have to change the name of all the selectors related to it 
- rows and columns are also called tracks
- use `border:solid` or `padding:1px` to kill margin collapse # refer to _grid.scss
- Sass maps are built-in sass module
- Sass maps similar to objects and dictionaries
### BEM : block access modifier => a methodology use to name classes in a big project
- block: a standalone entity that's meaningful on its own
- access: a part of a block that has no standalone meaning and is semantically tied to its block
- modifier: a flag on a block or element that are used to change appearance or behavior
- `class="block__element--modifier"`
  - block => block
  - element => element
  - modifier => modifier
-  
#### the link of the great tutorial
[click me](https://youtu.be/jfMHA8SqUL4)