# foundations_web_dev
Odin Path to development!

Hello Patrick!

__Working with text__

Most content on the web is text-based. Working with text entails creating paragraphs, headings, bold text, italicized text, relationship between nested elements and html comments.

_Paragraph_ 

When the browser encounters new lines your HTML, it will compress them down into one single space. The result of this compression is that all of the text is clumped together into one long line.

To create paragraphs in HTML, we need to use the paragraph element, which will add a newline after each of our paragraphs. 
A paragraph element is defined by wrapping text content with a  ```<p>```   tag.

_Headings_

Headings are displayed larger and bolder than other text to signify that they are headings.

There are 6 different levels of headings starting from ```<h1> to <h6>```. The number within a heading tag represents that heading’s level. The largest and most important heading is h1, while h6 is the tiniest heading at the lowest level.

Headings are defined much like paragraphs. For example, to create an h1 heading, we wrap our heading text in a ```<h1>``` tag.

Using the correct level of heading is important as levels provide a hierarchy to the content. An h1 heading should always be used for the heading of the overall page, and the lower level headings should be used as the headings for content in smaller sections of the page.

*Strong Element*

The ```<strong>``` tag is used when we want to indicate the importance, seriousness, or urgency of a word or section of content without changing the meaning of the content itself.
e.g 
```
<p>Before entering , Link read the warning at the entrance of the cave: <strong>Caution! Fire-breathing dragon ahead.</strong></p>
```
_Em Element_

The em element makes text italic. It also semantically places emphasis on the text, which again may affect things like screen readers. To define an emphasised element we wrap text content in a ```<em>``` tag.

```
<!-- We use <em> tags to emphasize markup and indicate verbal stress on a word or words -->
<p> Further and further Link went into the cave. With each step, it grew darker. This was a <em> very </em> deep cave indeed.</p>
```
_Nesting and Indentation_

When we nest elements within other elements, we create a parent and child relationship between them. The nested elements are the children and the element they are nested within is the parent.

We use indentation to make the level of nesting clear and readable for ourselves and other developers who will work with our HTML in the future. It is recommended to indent any child elements by two spaces.

_HTML Comments_

HTML comments are not visible to the browser; they allow us to comment on our code so that other developers or our future selves can read them and get some context about something that might not be clear in the code.

Writing an HTML comment is simple: We just enclose the comment with ```<!-- and --> ```tags.

**Links and Images**

Links point the user to a different HTML document, and images pull another resource into the page.