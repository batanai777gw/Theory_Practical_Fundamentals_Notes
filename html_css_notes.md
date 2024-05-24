# Theory_Practical_Fundamentals_Notes
Web Development Technologies | HTML &amp; CSS Fundamentals of Software Development

# Notes:
Topics : HTML & CSS [TODO: add home page to browse through all html file]

1. HTML
Hypertext Markup Language
- Describes structure of a web page
-- Contains elements
    - Elements describe how to render content
    - Elemenets are enclosed in Tags
-- Tags surround and describe content
    - start tag - text in angle brackets (i.e <body>)
    - end tag - Text with leading slash in angle brackets (i.e </body>)
    - Tags must be properly nested
--Attributes contained inside tags refine the operation of the tag
    - Format is: <tagname att1="value", att2="value"....>

# HTML - Simple HTML web page [exercise-1] -> completed

# HTML - Basic Tags
- <html></html> - Surround the entire document
- <head></head> - Sorround header material (titles, css info, etc.)
- <body></body> - Contains the main content of the page
- <p></p> - Hold a single paragraph that the browser will typeset.
- <h1></h1>, <h2></h2>, ... - Hold a heading line that is used to mark sections of a document for the reader

# HTML - More Basic Tags
- Links - These mark a hyperlink around link text. When click by user, 
browser loads the page in the HREF attribute.
    - Format <A HREF="url target">Text for link</A>
        - Only 'Text for link' will show up on page.
    - Target attribute, indicates which window/tab should be used for the linked page.
        -target="_self" - Default. Place the content in the current tab
        -target="_blank" - Place the content in a newly created tab

# HTML - More Basic Tags
- <IMG> - Will display an image
    - Image file must be in a popular graphics format(gif,jpg,png,svg,jpeg,etc)
    - Format :
    <IMG src="url for image file", width=#, height=#, alt="Text to display">

# HTML - More on Links
---- page 12, 13

# HTML - Lists [page 14]
- Supports:
    - <UL></UL> - Unordered List
    - <OL></OL>  - Ordered List
    - <LI></LI>  - Encloses a single list item

# HTML - Example: Lists[exercise-2] -> completed

# HTML - Adding styles to lists
- UL takes a style attribute to customize the list
    - list-style-type
        -circle
        -square
        -disc
        -none

# HTML - Example: Adding styles to lists[exercise-3] -> completed

# HTML - Formatting Tags
- <b></b>   - Bold Text
- <strong></strong> - Important text (similar ro bold)
- <i></i>   - Italic text
- <em></em>  - Emphasized text(similar to Italic)
- <mark></mark> - Marked Text
- <small></small>   - Small Text
- <del></del>   - Deleted Text (stroked text)
- <ins></ins>   - Inserted Text
- <sub></sub>   - Subscript Text
- <sup></sup>   - Superscript Text

# HTML - Example: Formatting Tags[exercise-4] -> comepleted

# HTML - Comments
- Comments are contained in <!--    -->
- Example:
    <!-- This is a comment and does not affect rendering of the page -->


# HTML - Styles
- Style information can be included in tags with the 'style='attribute
- Format : <tag style="attr1:value1; attr2:value2"> text text text </tag>
    - attr1 & attr2 are style property names
    - value1 & value 2 are values to attach to the properties
- Most common style attributes:
    - background-color: for background color
    - color : for text color
    - font-family : for text fonts
    - font-size : for text sizes
    - text-align : for text alignment
<p style="background-color:green; color:red"> Paragraph Text. </p>
- Using CSS (Cascading Style Sheets) is actually much easier and less error prone

# HTML - Tables
- HTML Supports creating tables
    - Tags:
       - <table></table>    - Encloses the entire contents of the table
       - <tr></tr>          - These bracket a 'row' of data cells
       - <th></th>          - These tags support a row used specifically for column heading
       - <td></td>          - These tags go around data for a specific cell
       - <caption>          - This defines a table caption

# HTML - Example: Tables[exercise-6] -> completed

--page 23/65 [Day 1] : Target 4 hours/day on each tech
--practice