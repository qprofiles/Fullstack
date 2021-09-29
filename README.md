# Fullstack



#HTML is a language to learn if anyone wants to work in the web development domain [Web designers, Web Developers]. 
HTML alone is not sufficient for a web developer because HTML only defines the structure of the data that will be rendered on the browser in a webpage, 
to make it visually appealing and to make it functional, we will need to use CSS and Javascript as well.


#Tags, Attributes and Elements
Tags are the primary component of the HTML that defines how the content will be structured/ formatted, 
whereas Attributes are used along with the HTML tags to define the characteristics of the element. 

For example, <p align=” center”>Interview questions</p>, in this the ‘align’ is the attribute using which
will align the paragraph to show in the center of the view.



HTML elements are defined by a starting tag, may contain some content and a closing tag.
HTML elements which do not have closing tags or do not need to be closed are Void elements. For Example <br />, <img />, <hr />, etc.

HTML Entities
In HTML some characters are reserved like ‘<’, ‘>’, ‘/’, etc. To use these characters in our webpage we need to use the character entities called HTML Entities. Below are a few mapping between the reserved character and its respective entity character to be used.

Different types of lists in HTML


HTML layout structure.
Every web page has different components to display the intended content and a specific UI. But still, there are few things which are templated and are globally accepted way to structure the web page, such as:

<header>: Stores the starting information about the web page.
<footer>: Represents the last section of the page.
<nav>: The navigation menu of the HTML page.
<article>: It is a set of information.
<section>: It is used inside the article block to define the basic structure of a page.
<aside>: Sidebar content of the page.

  
Formating tags in HTML
  
HTML has various formating tags:
<b> - makes text bold
<i> - makes text italic
<em> - makes text italic but with added semantics importance
<big> - increases the font size of the text by one unit
<small> - decreases the font size of the text by one unit
<sub> - makes the text a subscript
<sup> - makes the text a superscript
<del> - displays as strike out text
<strong> - marks the text as important
<mark> - highlights the text
<ins> - displays as added text
  
  
  
Different kinds of Doctypes
The three kinds of Doctypes which are available:

Strict Doctype 
Transitional Doctype
Frameset Doctype
  
Meta Tags
  
  significance of <head> and <body> tag in HTML?
<head> tag provides the information about the document. It should always be enclosed in the <html> tag. This tag contains the metadata about the webpage and the tags which are enclosed by head tag like <link>, <meta>, <style>, <script>, etc. are not displayed on the web page. Also, there can be only 1 <head> tag in the entire Html document and will always be before the <body> tag.

<body> tag defines the body of the HTML document. It should always be enclosed in the <html> tag. All the contents which needs to be displayed on the web page like images, text, audio, video, contents, using elements like <p>, <img>, <audio>, <heading>, <video>, <div>, etc. will always be enclosed by the <body> tag. Also, there can be only 1 body element in an HTML document and will always be after the <head> tag.
  
  
iframe and Embed
  
Cell Padding different from Cell Spacing
  
How can we club two or more rows or columns into a single row or column in an HTML table?
HTML provides two table attributes “rowspan” and “colspan” to make a cell span to multiple rows and columns respectively.


Positions
  
  There are mainly 7 values of position attribute that can be used to position an HTML element:

static: Default value. Here the element is positioned according to the normal flow of the document.
absolute: Here the element is positioned relative to its parent element. The final position is determined by the values of left, right, top, bottom.
fixed: This is similar to absolute except here the elements are positioned relative to the <html> element.
relative: Here the element is positioned according to the normal flow of the document and positioned relative to its original/ normal position.
initial: This resets the property to its default value.
inherit: Here the element inherits or takes the property of its parent.

  
  
display HTML elements
inline: Using this we can display any block-level element as an inline element. The height and width attribute values of the element will not affect.
block: using this, we can display any inline element as a block-level element. 
inline-block: This property is similar to inline, except by using the display as inline-block, we can actually format the element using height and width values.
flex: It displays the container and element as a flexible structure. It follows flexbox property.
inline-flex: It displays the flex container as an inline element while its content follows the flexbox properties.
grid: It displays the HTML elements as a grid container.
none: Using this property we can hide the HTML element.


What is the difference between “display: none” and “visibility: hidden”, when used as attributes to the HTML element.
When we use the attribute “visibility: hidden” for an HTML element then that element will be hidden from the webpage but still takes up space. Whereas, if we use the “display: none” attribute for an HTML element then the element will be hidden, and also it won’t take up any space on the webpage.


Link in HTML and explain the target attribute?
HTML provides a hyperlink - <a> tag to specify the links in a webpage. The ‘href’ attribute is used to specify the link and the ‘target’ attribute is used to specify, where do we want to open the linked document. The ‘target’ attribute can have the following values:

_self: This is a default value. It opens the document in the same window or tab as it was clicked.
_blank: It opens the document in a new window or tab.
_parent: It opens the document in a parent frame.
_top: It opens the document in a full-body window.
  
  
There are three ways in which we can specify the styles for HTML elements:

Inline: Here we use the ‘style’ attribute inside the HTML element.
Internal: Here we use the <style> tag inside the <head> tag. To apply the style we bind the elements using ‘id’ or ‘class’ attributes.
External: Here we use the <link> tag inside <head> tag to reference the CSS file into our HTML code. Again the binding between elements and styles is done using ‘id’ or ‘class’ attributes.

  
The anchor tag <a> is used to create a hyperlink to another webpage or to a certain part of the webpage and these links are clickable, whereas, link tag <link> defines a link between a document and an external resource and these are not clickable.


HTML Forms
The HTML form is used to collect the user inputs. HTML provides a <form> tag to create forms. To take input from the user we use the <input> tag inside the form so that all collected user data can be sent to the server for processing. There are different input types like ‘button’, ‘checkbox’, ‘number’, ‘text’, ‘password’, ‘submit’ etc.

Difference between <figure> tag and <img> tag?
The <figure> tag specifies the self-contained content, like diagrams, images, code snippets, etc. <figure> tag is used to semantically organize the contents of an image like image, image caption, etc., whereas the <img> tag is used to embed the picture in the HTML5 document.

The <datalist> tag and <select> tag are different. In the case of <select> tag a user will have to choose from a list of options, whereas <datalist> when used along with the <input> tag provides a suggestion that the user selects one of the options given or can enter some entirely different value

Image Map?
Image Map lets a developer map/link different parts of images with the different web pages. It can be achieved by the <map> tag in HTML5, using which we can link images with clickable areas

  
SVG and Canvas HTML5 element
  
Audio files can be played using HTML5?
  
Which tag is used for representing the result of a calculation? Explain its attributes.
The <output> tag is used for representing the result of a calculation. It has the following attributes:

for - It defines the relationship between the elements used in calculation and result.
form - This is used to define the form the output element belongs to.
name - The name of the output element.
<form oninput = "result.value=parseInt(n1.value)+parseInt(n2.value)">
     <input type = "number" name = "n1" value = "1" /> +
     <input type = "number" name = "n2" value = "2" /><br />
     The output is: <output name = "result"></output>
</form>


Following are the significant new data types offered by HTML5:

Date - Only select date by using type = "date"
Week - Pick a week by using type = "week"
Month - Only select month by using type = "month"
Time - Only select time by using type = "time".
Datetime - Combination of date and time by using type = "datetime"
Datetime-local - Combination of  date and time by using type = "datetime-local." but ignoring the timezone
Color - Accepts multiple colors using type = "color"
Email - Accepts one or more email addresses using type = "email"
Number - Accepts a numerical value with additional checks like min and max using type = "number"
Search - Allows searching queries by inputting text using type = "search"
Tel - Allows different phone numbers by using type = "tel"
Placeholder - To display a short hint in the input fields before entering a value using type = "placeholder"
Range - Accepts a numerical value within a specific range using type = "range"
Url - Accepts a web address using type = "url”


  Test
  
  
  
  
  
  
  
  
