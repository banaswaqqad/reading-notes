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
 
 **# Process & Design ** 
 
 **Who is the Site For?**
 every website should be build for targeted visitors
 thier are two types of visitors : 
 
 * individuals 
you should focus on : 
1. age range 
2. appeal to more women or men
3. country do visitors live in
4. average income of visitors
5. How often do they use the web?
6. the level of education do they have 


* Companies

 you should focus on : 

1. size of the company
2.  the position of people in the company who visit your site and how larg the budget they control


**# Why People Visit
YOUR Website** 

aftre you know who your visitors are, you
should consider why they are coming. While
some people will simply chance across your
website, most will visit for a specific reason

**the content and design should
be deal with the goals and intrests  of
your users** 

To help determine why people
are coming to your website,
there are two basic categories of
questions you can ask:
1.  The first attempts to discover
the underlying motivations for
why visitors come to the site.
2.  The second examines the
specific goals of the visitors.
These are the triggers making
them come to the site now.

**# What Your Visitors are
Trying to Achieve**

to know that you should 
create a list
of reasons why people would
be coming to your site. You can
then assign the list of tasks to
the fictional visitors you created
in the step described on the
previous page

**# What Information
Your Visitors Need**

**Key Information**

* Will visitors be familiar with
your subject area / brand
or do you need to introduce
yourself?
* Will they be familiar with
the product / service /
information you are covering
or do they need background
information on it?
* What are the most important
features of what you are
offering?
* What is special about what
you offer that differentiates
you from other sites that offer
something similar?
* Once people have achieved
the goal that sent them to
your site, are there common
questions people ask about
this subject area

**# Site Maps**

*starting to organize the
information into sections or pages that will be used
to structure the site..*

**card sorting technique:** can help you to decide what
information should go on each
page

This involves placing each
piece of information that a
visitor might need to know on
a separate piece of paper and
then organizing the related
information into groups.

Each group relates to a page and,
on larger sites the, pages can in
turn can be grouped together to
create different sections of the
website.

The groups of information are
then turned into the diagram
that is known as the site map.
Sometimes it can be helpful to
ask people who are the target
audience to help you group
related information together.

A site map will usually
begin with the homepage.
Additionally, if the site is **large
and is compartmentalized
into sections, each section
might require its own section
homepage to link to all of the
information within it.

**# WireFrames** 
sketch of the key
information that needs to go on each page of a
site. It shows the hierarchy of the information
and how much space it might require.

**the Importance of wireframes**

1. By creating a wireframe you can
ensure that all of the information
that needs to be on a page is
included.

2. The wireframes make design
easier because you know what
information needs to appear on
which page before considering
how the the page should look

**#Getting your message
across using design** 

With so much on the page, the
designer needs to **organize** and
**prioritize** the information to
communicate their message
and help users find what they're
looking for.

**1. organizing**



 Grouping together related
content into blocks or chunks
makes the page look simpler
(and easier to understand).
Users should be able to
identify the purpose of each
block without processing each
individual item.
By presenting certain types of
information in a similar visual
style (such as using the same
style for all buttons or all links),
users will learn to associate that
style with a particular type of
content

**#2. Prioritizing**

f everything on a page appeared
in the same style, it would be
much harder to understand. (Key
messages would not stand out.)
By making parts of the page
look distinct from surrounding
content, designers draw
attention to (or away from)
those items.
Designers create something
known as a visual hierarchy
to help users focus on the key
messages that will draw people's
attention, and then guide them
to subsequent messages.

**explain how
design can be used to effectively
communicate the services of a
company**

1. visual hierarchy

You can use contrast to create a visual hierarchy that gets
across your key message and helps users find what they are looking for :

* Size 
* Color
* Style

2. grouping and Similarity

 Grouping related pieces of information together can make a
design easier to comprehend. Here are some ways this can be achieved: 

* Proximity:
 several items are
placed close together, they are
perceived as more related than
items that are placed further
apart

* Closure : faced with a complicated
arrangement of items, we
will often look for a single or
recognisable pattern or form.
A real or imaginary box can be
formed around elements due to
their proximity and alignment.

* Continuance : elements are placed in
a line or a curve then they are
perceived to be more related
than those that are not following
the same direction. This can be
used to direct a reader from one
part of a page to the next.

* White Space :
Placing related items closer
together and leaving a bigger
gap between unrelated items.

* color :
A background color placed
behind related items to
emphasize their connection.

* Borders :

 A line can be drawn around the
border of the group or between it
and its neighbors.

!(grouping and Similarity)[https://1.bp.blogspot.com/-vi1__2L_J4M/XLdeGwtGAdI/AAAAAAAAAKA/WYp6FMi1KV06WTH-a7nWKnNO78p6L-6bwCEwYBhgL/s1600/Gestalt%2BTheory.jpg"]

**# Designing Navigation** 

Site navigation:  helps people: 

1. find where they want to go 
2. understand what your site is about and how it is organized

Good navigation tends to follow these principles...

* Concise: 

 the navigation should
be quick and easy to read. 

* Clear : 

Users should be able to predict
the kind of information that
they will find on the page
before clicking on the link

* Selective
The primary navigation should
only reflect the sections or
content of the site ,exapmle : login and search 
A large site may have primary,
secondary and even tertiary
navigation. Primary navigation
often appears across the top
of the site from left to right, or
down the left hand side of the
page. Secondary navigation
could be under the primary
navigation or down the side of
the page. Tertiary navigation
often sits in the footer of the
page. The menu will not be the
only way users navigate the site.
They will also use links within
each page. Some sites also offer
a search function

* Context : 

lets the user know
where they are in the website at
that moment. Using a different
color or some kind of visual
marker to indicate the current
page is a good way to do this.

* Interactive : 

Each link should be big enough
to click on and the appearance
of the link should change when
the user hovers over each item
or clicks on it. It should also
be visually distinct from other
content on the page.

* Consistent : 


The more pages a site contains,
the larger the number of
navigation items there will be.
Although secondary navigation
will change from page to page,
it is best to keep the primary
navigation exactly the same.





