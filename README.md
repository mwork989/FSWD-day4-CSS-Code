
Cascading Style Sheets (CSS) is a fundamental technology in web development for several important reasons:

1.Separation of Content and Presentation : CSS allows you to separate the structure and content (HTML) of a web page from its visual design. This separation enhances maintainability and reusability of web pages.

2.Consistent Styling:CSS enables you to apply consistent styling to multiple web pages or elements throughout a website.

3.Ease of Maintenance:With CSS, making global design changes becomes more straightforward. You can update a single CSS file to change the look and feel of an entire website.

4.Scalability:CSS scales well for both small websites and large web applications, providing the tools needed to handle complex layout and styling requirements.
---------------------------
Latest version - CSS3 

Most important feature in css3 is Flexbox (Flexible Box Layout):

-----------------------

Importance in CSS is decided by how closer the style proeprties are
attached to HTML elements

1. Inline styling 
2. embedded styles - internal styles
3. external styles
    we can create link or style imports to multiple css files


Selectors
----------------

CSS selectors are patterns used to select and style HTML elements on a web page

They define which elements in the HTML document should have specific styles applied to them.

CSS selectors target elements based on various criteria, such as
element,type,attibute,relationships to other elemtents

1.Element Selector:

Selects elements by their HTML tag name.
e.g.
p{
    color:gree;
}

selects all p tags


2. Class Selector:

Selects elements with a specific class attribute.
Example: .highlight selects all elements with class="highlight".

3. ID Selector:

Selects a single element with a specific ID attribute.
Example: #header selects the element with id="header".

4. Universal Selector:

* Selects all elements on the page.


5. Attribute Selector:

Selects elements based on their attributes and attribute values.
    5.1  Existence Selector [attribute] : Selects elements that have the specified attribute, regardless of its value

    5.2  Equality Selector [attribute=value] : Selects elements with the specified attribute that has a specific value

    5.3  Substring Value Selector [attribute*=value] : Selects elements with the specified attribute that contains the specified substring anywhere within its value.

    5.4  Prefix Value Selector [attribute^=value] : Selects elements with the specified attribute that begins with the specified prefix.

    5.5  Suffix Value Selector [attribute$=value] : Selects elements with the specified attribute that ends with the specified suffix.

    5.6  Hyphen-Match Value Selector [attribute|=value] : Selects elements with the specified attribute that matches a specific language code or begins with that code followed by a hyphen.



6. Descendant Selector:

Selects an element that is a descendant of another element.
Example: ul li selects all <li> elements that are descendants of a <ul>.

7. Child Selector:

Selects an element that is a direct child of another element.
Example: ul > li selects all <li> elements that are immediate children of a <ul>.


8. Adjacent Sibling Selector:

Selects an element that is an immediate sibling of another element.
Example: h2 + p selects a <p> that comes immediately after an <h2>.


9. General Sibling Selector:

Selects elements that are siblings of another element.
Example: h2 ~ p selects all <p> elements that are siblings of an <h2>.

10. Pseudo-Classes:

Select elements based on their state or position in the document.
Example: a:hover selects links when they are hovered over.

11. Pseudo-Elements:

Selects parts of elements, such as the first line of text or the first letter.
Example: p::first-line selects the first line of text within a <p>.

12. based on above selection process we can combinators 
13. multselectors 


