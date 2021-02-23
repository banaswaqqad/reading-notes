  **#The Evolution of HTML**
1. HTML4


Each new version was designed
to be an improvement on the
last (with new elements and
attributes added and older code
removed).

*some browsers not supporting certain features*


Although HTML 4 had some
presentational elements to
control the appearance of pages
Examples
* include the <center>element
for centering content on a
page
 
* <font> for controlling
the appearance of text

 * <strike> "to put a line through
the text" 

2. XHTML1.0

XML
was published. Its purpose
was to allow people to write
new markup languages. Since
HTML was the most widely used
markup language around, it was
decided that HTML 4 should be
reformulated to follow the rules
of XML and it was renamed
XHTMl 


This meant that
there is some new,
more strict rules about writing
markup. For example:
* Every element needed a
closing tag (except for empty
elements such as <img />).

*  Attribute names had to be in
lowercase.

* All attributes required a value,
and all values were to be
placed in double quotes.
*  Deprecated elements should
no longer be used.
*  Every element that was
opened inside another
element should be closed
inside that same element.


3. HTML5 

In HTML5, web page authors do
not need to close all tags, and
new elements and attributes will
be introduced. At the time of
writing, the HTML5 specification
had not been completed, but
the major browser makers had
started to implement many of
the new features, and web page
authors were rapidly adopting
the new markup.
Despite the fact that HTML5
is not yet completed, you can
safely take advantage of the
new features of the language as
long as you endeavour to ensure
that users with older browsers
will be able to view your pages
(even though some of the extra
features will not be visible to
them).


**#Doctypes :**
Because there have been
several versions of HTML, each
web page should begin with a
DOCTYPE declaration to tell a
browser which version of HTML
the page is using (although
browsers usually display the
page even if it is not included)

**#Comments in Html**

<!-- -->

it's help you when you go back to your code and help other if they want to use your code 

**#ID Attribute**
giving an element a
unique identity, it's allows you to
style it differently than any other
instance of the same element
on the page

**#class attribute**
a way to identify several elements
as being different from the
other elements on the page.

**#Block Elements**
Some elements will always
appear to start on a new line in
the browser window

**#Inline Elements**
Some elements will always
appear to continue on the
same line as their neighbouring
elements. These are known as
inline elements

**#Grouping Text &
Elements In a Block**

<div>
allow the user group a set of elements together
in one block

**#Grouping Text &
Elements Inline**
<span>

the main aim for it is : 


* To explain the purpose of this
<span> element

*  So that CSS styles can be
applied to elements that
have specific values for these
attribute

**#IFrames**

<iframe> 

small window
that has been appear into your
page — and in that window you
can see another page

An iframe is created using the
<iframe> element.

 There are a
few attributes that you will need
to know to use it:


1. src.
The src attribute specifies the
URL of the page to show in the
frame.

2. height
The height attribute specifies
the height of the iframe in pixels.

3. width
The width attribute specifies
the width of the iframe in pixels.


**# HTML5 Layout**


**HTML5** introduces a new set of elements that allow you to divide up the
parts of a page

1. Headers  <header> & Footers  <footer>
 
*it can be used for*

* The main header or footer
that appears at the top or
bottom of every page on the
site.
*  A header or footer for an
individual <article> or
<section> within the page

2. Navigation < nav> 

it's used to
contain the major navigational
blocks on the site such as the
primary site navigation.

3. Articles <article> 

it's acts as
a *container* for any section of a
page that could stand alone and
potentially be syndicated.
This could be an individual
article or blog entry, a comment
or forum post, or any other
independent piece of content.
If a page contains several articles
(or even summaries of several
articles), then each individual
article would live inside its own
<article> element.
The <article> elements can
even be nested inside each
other. For example, a blog post
might live inside one <article>
element and each comment on
the article could live inside its
own child <article> element

3. Asides <aside>
this element has two
purposes, depending on whether
it is inside an <article>
element or not.
 
* When the <aside> element
is used *inside* an <article>
element, it should contain
information that is related to the
article but not essential to its
overall meaning. .
 
* When the <aside> element is
used *outside* of an <article>
element, it acts as a container
for content that is related to
the entire page. 
 
4. Sections  <section>
this element groups
related content together, and
 each section would
have its own heading.
 
*Because the <section> element
groups related items together,
it may contain several distinct
<article> elements that have a
common theme or purpose* 
 
5. Heading  groups  <hgroup> 

The purpose of this element is to group together a
set of one or more <h1> through
<h6> elements so that they are
act as one single heading

6. Figures  <figure> <figcaption>
 
 it should only be
used when the content simply
references the element (and not
for something that is absolutely
integral to the flow of a page).

The <figure> element should
also contain a <figcaption>
element which provides a text
decription for the content of
the <figure> element. In
this example, you can see a
<figure> has been added inside
the <article> element.

7. Sectioning ELEMENTS <div> 

the <div> element
A way to
group together related elements

*Where there is no suitable
element to group a set of
elements, the <div> element will
still be used*
 
 Linking Around
Block-Level Elements <a> 
 This element  allows the user to turn an entire block
into a link.

