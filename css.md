**# Introducing CSS**

**What CSS does?**
CSS allows you to create rules that specify how the content of
an element should appear

**BLOCK & INLINE ELEMENTS :** 

* Block level elements look
like they start on a new line.
Examples include the <h1>-
<h6>, <p> and <div> elements.

* Inline elements flow within the
text and do not start on a new
line. Examples include <b>, <i>,
<img>, <em> and <span>.

*CSS allows you to create rules that control the
way that each individual box (and the contents
of that box) is presented *

**Example Styles**

 1. Boxes 

 Width and height
Borders (color, width, and style)
Background color and images
Position in the browser window

2. Text

Typeface
Size
Color
Italics, bold, uppercase,
lowercase, small-caps

**# CSS Associates Style rules with HTML elements**
CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.

This rule indicates that all <p>
elements should be shown in the
Arial typeface.
Selectors indicate which
element the rule applies to.
The same rule can apply to
more than one element if you
separate the element names
with commas.
Declarations indicate how
the elements referred to in
the selector should be styled.
Declarations are split into two
parts (a property and a value),
and are separated by a colon.

#**CSS Properties Affect How Elements Are Displayed**

CSS declarations sit inside curly brackets and each is made up of two
parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon

This rule indicates that all <h1>,
<h2> and <h3> elements
should be shown in the Arial
typeface, in a yellow color.
Properties indicate the aspects
of the element you want to
change. For example, color, font,
width, height and border.
Values specify the settings
you want to use for the chosen
properties. For example, if you
want to specify a color property
then the value is the color you
want the text in these elements
to be.

#**Using External CSS**

**<link>**
The <link> element can be used
in an HTML document to tell the
browser where to find the CSS
file used to style the page. It is an
empty element (meaning it does
not need a closing tag), and it
lives inside the <head> element.
It should use three attributes

**href**
This specifies the path to the
CSS file (which is often placed in
a folder called css or styles).
type
This attribute specifies the type
of document being linked to. The
value should be text/css.

**rel**
This specifies the relationship
between the HTML page and
the file it is linked to. The value
should be stylesheet when
linking to a CSS file.

#**Using Internal CsS**

<style>
You can also include CSS rules
within an HTML page by placing
them inside a <style> element,
which usually sits inside the
<head> element of the page.
The <style> element should use
the type attribute to indicate
that the styles are specified in
CSS. The value should be text/
css

**the best thing in using internal css** 
This:
*  Allows all pages to use the
same style rules (rather than
repeating them in each page).
*  Keeps the content separate
from how the page looks.
*  Means you can change the
styles used across all pages
by altering just one file
(rather than each individual
page).

**# the css Selectors**

!(css selector)[https://www.testim.io/wp-content/uploads/2020/05/xpath-vs-css-selector-syntax-table-1.png]

**How Css Rules Cascade**

If there are two or more rules
that apply to the same element,
it is important to understand
which will take precedence.
LAST RULE
If the two selectors are identical,
the latter of the two will take
precedence. Here you can see
the second i selector takes
precedence over the first.
SPECIFICITY
If one selector is more specific
than the others, the more
specific rule will take precedence
over more general ones. In this
example:
h1 is more specific than *
p b is more specific than p
p#intro is more specific than p
IMPORTANT
You can add !important after
any property value to indicate
that it should be considered
more important than other rules
that apply to the same element.

# **Inheritance**

If you specify the font-family
or color properties on the
<body> element, they will apply
to most child elements. This is
because the value of the
font-family property is
inherited by child elements. It
saves you from having to apply
these properties to as many
elements (and results in simpler
style sheets).
You can compare this with
the background-color or
border properties; they are not
inherited by child elements. If
these were inherited by all child
elements then the page could
look quite messy.