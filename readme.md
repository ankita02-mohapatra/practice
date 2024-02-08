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
       <p style="backgroundcolor:yellow">Today we started CSS</p>
       </body>    
   2.Internal CSS-:
      <head>
      <style>
         h1{
            color:red;
         }
         p{
            backgroundcolor:blue;
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