# Notes and guides

## HTML
### Tags:
Tags: Way to insert elements in html file
- **head**: Contains metadata
- **title**: title in browser
- **body**: contains the content of the page
- **heading tag**: From 1 to 6 ex. **h1 h2... h6**
- **p**: for paragraphs
- **strong** or **b**: for bold text
- **em** (emphasis) or **i**: for italics text

#### Lists
- **ol**: Order lists
- **ul**: Unorder lists
- **li**: Elements of lists

#### Div an Span
Div and Span are used for group together to applying css inside for adding style

- **Div** is like a module that share same characteristics
- **Span** is like a Div but in a specific line

#### Atributes
- **img** for insert images
    - alt atribute generate an alternative text when an image is not appearing
- **a** with **href** for insert a link

#### Tables
- **table**: tag for start a table
- **thead**: First/Header raw of table
- **th**: Elements placing inside of header raw
- **tr**: table rows
- **td** or table cells: Elemens correspond to each column

#### Forms
- **Input**: For add information for generating an action
    - **type**: Could be like _email_, _passwords_, _submit_, _text_, _color_
    - **placeholder** versus **value**: It is common to use element placeholder for no adding text to the input, it's just and indication that it's dropped when you type
    - **required**: for determine and element that has to be completed for sending the form
- **Actions**: Arrives yow to another site
- **Labels**: Are used for name or label inputs, it often used with elemnt "for" for giving a name and the used in element "id" in some "input" tag
- **Selections**: like type _radio_, _select_ and _option_ (s) tags and _textarea_ for delimit text to type

**comment code:** <!-- Anything here is a comment-->

Sources for learning HTML:
- w3schools.com
- developer.mozilla.org

## CSS
Help you to stylish your page

Usually you conect a file of css inside a html file using **"link"** tag and linking with the path in _"href"_ attribute

### **Common structure or formato for css:**

_selected tag{_
    _property: value;_
_}_

### **Some properties you can apply stylish in css:**
- **Color:** you can use Color name (red, blue, purple) or use RGB (mixes of Red, Green, Blue) or hexagesimal (Most common used). You can use rgba (a = alpha for give transparency - value between 0 and 1)
- **background**: you define if is a color or and image, its size...

### Selectors
Selectors are common used for selecting subsets or code elements and apply specific styling. Ids starts with "#" in css
- **ids**: are used to target single elements
- **classes**: to target groups of elements. Classes start with "." in css
- **"*"**: Selects all elements. Usually overwrite classes. It is not usually used.

For more deep knowledge about selectors visit (Selectors)[https://www.w3schools.com/cssref/css_selectors.asp]

### Specificity
Defines the hierarchy of CSS styling and what type of tagss overrule others.

### Fonts
- You can chose _font-family_ for stablish type of font you want for all text or specific text
- em is the relationship with _font-size_ you define: 1em = 16 px --> 2em = 32 px
- Also, you can chose _font-style_ as _italic_, _font-weight_ as _bold_, _text-aling_ as _center_.

#### Sources for dowloading fonts
1. (Fonts Google)[https://fonts.google.com]
2. (Font Library)['https://fontlibrary.org']

### Box Model
This is the order:
1. Margin
2. Border
3. Padding
4. Content

You can specify the _top, bottom, left and right_ of each one before


**commet code:** /* Anything here is a comment */


### Bootstrap   
It is a Framework with predesing components of CSS and HTML
- Bootstrap has deafult classes you can use easyly
- Inside row class, we have the following forma:
    - col-ScreenSize-NumberOfColumns
    ej. col-md-6

![Columns in Bootstrap]("../files/columns_bootstrap.jpg")

## Javascript (Js)

It is a Programming Language. Let you interact with websites among other things.

- In Js the function for print in console is **Alert**
- For comment in Js you use double slash ("//")
- In Js there is not a distiction between number types, they are just numbers (Not like other languages that distingue Integers, Floats...)
- Other data types are: String, Numbers, Boleans (true, false), undefined, null...
- You can concatenate strings using + 
- string.lenght is the method for calculate lenght of a string or list


### Variables:
The way to call a variable is like follow:
- var varName = value;
   - ej. var bankAccount = 100

Notes: 
- Undefined means you create something but you do not defined it
- Null means actually you assing nothing to a variable for example
- console.log("text") is the way to print in the console
- prompt is the way to display a form for input something

