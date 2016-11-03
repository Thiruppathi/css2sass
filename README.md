# css2sass

## Branding & Typography Changes

### Step 1 - Scss Conversion
Rename page.css to page.scss; Generate .scss using a [tool](http://css2sass.herokuapp.com/)

### Step 2  Nested Structure removal - Debugging the .scss
Remove nested structure where required from page.scss

### Step 3 - Branding - Extract Colors and Variablize
[Extract](https://hex.corvidworks.com/) colors from css; 
Create _variables.scss;
Create color variables in _variables.scss
Use these color-varaibles in page.scss

### Step 3 - Typography - Extract Fonts and Variablize
As of now, I'm not sure about automatic font extraction from css using a tool. 
Can do a simple Find in an IDE for a CSS and Variablize them;

Import these font-variables in _variables.scss
Use these color-varaibles in page.scss

## Layout & more
- Create variables for layout properties such as padding, margin etc.,
- Create variables for z-index properties, which can be used in tooltip, modal, modalContainer, etc.,
- Create mixins

## Task Runners
- gulp can help in automating scss compilation

## Auto Generate - Style Guide 
- Auto generate Style Guide based on the values present in scss and html templates.
