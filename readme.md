HTML:
   HTML stands for hyper text markup language.
   We use html for creating structure of the website.
   We called html as a markup language because it contain skelliton structure of the web page.
   All html are written in tag lines.

h: Heading 
   Heading is range from h1-h6.

p: paragraph
br:Line break(Single tag)
hr:Horizontal line
src,height,width,alt are the attribute of image tag.
href:
   href for hyper reference(reference to the another page/element).
   _self:-Own page
   _blank:-New page

HTML Formatting:
   <mark>-marked text
   <b>-bold text
   <i>-italic text
   <em>-emphasized text
   <ins>-inserted text
   <del>-deletion text
   <sub>-subscripted text
   <sup>-superscripted text

HTML Table:
   HTML table gives us a table like structure where we can insert our Data in row and column format.
   <table>-main tag
   <tr>-table row
   <th>table heading
   <td>-table data

HTML List:
   List are of 2 types:
      Unordered list:-<ul>
      Ordered list:-<ol>

   My hobbies are...
   1.Watching cricket
   2.Singing
   3.Riding

HTML block level element:
   HTML contain 2 types of block level element to specify the structure of a web pages.
      1.<p>-paragraph
      2.<div>-division

HTML Forms:
   HTML Forms provides a form like structure so that we can give our data by use these forms.

Input types are:
   <input type="text">
   <input type="password">
   <input type="submit">
   <input type="checkbox">
   <input type="radio-button">
   <input type="time">
   <input type="color">
   <input type="date">
   <input type="url">
   <input type="search">
   <input type="week">
   <input type="email">
   <input type="image">
   <input type="month">
   <input type="range">
   <input type="file">
   <input type="tel">
   <input type="number">

  8-02-24
*************************

CSS:
   CSS stands for cascading style sheet.
   Used CSS for designing and styling the web pages.

   syntax:
       h1{
         color:red
       }
       h1-:selector
       red-:value
       color-:property
   Basically CSS are of 3 types:
       1.Inline CSS
       2.Internal CSS
       3.External CSS

   1.Inline CSS-:
       <body>
       <h1 style="color:red">Today is thursday</h1>
       <p style="background-color:yellow">Today we started CSS</p>
       </body>    
   2.Internal CSS-:
      <head>
      <style>
         h1{
            color:red;
         }
         p{
            background-color:blue;
         }
      </style>
      </head>
   3.External CSS-:
      It is a linkage to the outer CSS file to our main HTML element.

     index.HTML:
      <head>
      <link rel="stylesheet" href="style.CSS>
      </head>
      <body>
      <h1>Today is a beautiful day</h1>
      </body>
     style.CSS:
       h1{
         color:red;
       }

   CSS selector are of 5 types:-
      1.ID selector
      2.Class selector
      3.Universal selector
      4.Group selector
      5.Element Selector
     Selector means selecting a element which we have to designed.

   1.ID selector-:
       ID selector are those selector which unique design / we select only one element in HTML file.
       It is denoted by"#".  
      HTML:
      <html>
      <head>
        <link rel="stylesheet" href="style.css>
      </head>
      <body>
       <h1 id="demo"> Today is tuesday</h1>
       <h1>We learn CSS</h1>
       <h1>We write code....</h1>
      </body>
      </html>

      #TAT{
         color:green;
      }
      h1{
         color:red;
      }
   2.Class selector:-
      We use class selector for repeating the similar design in multiple times.
      "."property we used to specify the class selector in our css file.
      <html>
      <head>
         <link rel="stylesheet" href="style.css">
         <title>Class selector</title>
      </head>
      <body>
         <h1 class="demo" >today is thursday</h1>
         <h2>learn css</h2>
         <p>Today is a good day</p>
      </body>
      </html>

      style.css
      .demo{
         color:red;
         text-align:center;
      }  

   3.Universal selector:-
     We use Universal selector to design whole html page in a single page.
     "*" property we used to specify the class selector in our css file.

   4.Group selector:-
     We used Group selector  to create one design in which we have selected the tags.
     Group selector we used by creating the group.

   5.Element Selector:-
     By selecting one single  single element we have to design is called the element selector.

VERSION CONTROL SYSTEM:-
   git and github are those open source version control system.
   We used version control system to store our code, share our code and collaborate our projects with each other.
   example of VCS is git,github,gitlab...

  9-02-24
********************

Typography:-
--------------------
  <b>
  <i>
  <u>
  <small>
  <big>
  <em>
  <del>
  <strong>
  <sup>
  <sup>

Colors in CSS:-
--------------------
  RGB - (Red,Green,Blue)
  HEX - (#0-9,A-F)
  HSLA - (Hue,Saturation,Lightness,Alpha)   alpha(0-1)
  HSL - (Hue,Saturation,Lightness)
  RGBA - {Red,Green,Blue,Alpha}

Text properties:-
--------------------
  color
  line-height
  letter-spacing
  text-transform
  text-decoration
  text-indent

Border property:-
--------------------

Font properties:-
--------------------
  font-family
  font-size
  font-style
  font-weight
  font-variant

12-02-24
-----------------------
Display properties:-
-----------------------
   inline:-Takes only the space required by the element.
   block:-Takes full space available in width.
   inline-block:-similar to inline but we can set margin and padding.
   none:-to remove element from document flow.

Practice set-3:-
1.Create a webpage layout with a header ,a footer,& a content area containing 3 divs.
set the height & width of div to 10px.
2.add border to all the divs.
3.add a different background color to each div with an opacity 0.5
4.give the content area an appropriate height.

Position property:-
-----------------------
  static:-default position
  relative:-element is relative to itself.
  absolute:-positioned relative to its closest position ancestors.


z-index:-
--------------
It indicates the stack level of element , overlapping element with a larger z-index cover those with a similar one.
  z-index : auto
  z-index : 1/2/.....
  z-index : -1/-2/.....

 Background image:-
 ---------------------
 used to set an image as background

 background image : url("image,jpg");

 background-Size:-

 background-size:cover;

Practice set-4:-
-------------------
Create the following layout using the given html.
1.Give the div a height,width & some background image.
2.Use the appropriate position property for the element to place it at the right end of the page,(The div should not move even on scroll)
3.Use z-index to place the div on the top of page.


Flexbox (flexible box):-
---------------------------
It is a one dimensional layout method for arranging item in rows or columns.

Flexbox direction:-
----------------------------
It sets roes flex items are placed in the flex container.

  flex-direction:  row;
  flex-direction:  row-reverse;
  flex-direction:  column;
  flex-direction:  column-reverse;

Flex properties:-
-------------------
  justify-content : alignment along the main axis
                    (flex-start (default), center , flex-end, space-evenly ,space-between , space around)
   flex-wrap : (wrap, wrap-reverse , nowrap );
   align-items : alignment along the cross axis.
   align-content : alignment of space between & around the content along cross-axis.
   align-self : alignment individual along the cross axis.

Practice set-5:-

1.Create a navbar with 4 option in the form of anchor tags inside list items. Now, use flexbox to place them all spaced equally in a single line.
2.Use flexbox to center one div inside another div.
3.Which has higher priority  - align-item or align-self