
**Images**

Controlling the size and alignment of
your images using CSS keeps rules that
affect the presentation of your page in
the CSS and out of the HTML markup.

![photo](https://i.ytimg.com/vi/kMT54MPz9oE/maxresdefault.jpg)

* **Controlling sizes of images in CSS**

* You can control the size of an
image using the width and
height properties in CSS, just
like you can for any other box.

* Specifying image sizes helps
pages to load more smoothly
because the HTML and CSS
code will often load before the
images, and telling the browser
how much space to leave for an
image allows it to render the rest
of the page without waiting for
the image to download.

* **Aligning images using CSS**

* Rather than using the img
element's align attribute, web
page authors are increasingly
using the float property to align
images. There are two ways that
this is commonly achieved:

1. The float property is added
to the class that was created to
represent the size of the image

2. New classes are created with
names such as align-left or
align-right to align the images
to the left or right of the page.
These class names are used in
addition to classes that indicate
the size of the image.

* **Centering images using CSS**

* By default, images are inline
elements. This means that they
flow within the surrounding text.
In order to center an image, it
should be turned into a blocklevel
element using the display
property with a value of block.

* Once it has been made into a
block-level element, there are
two common ways in which you
can horizontally center an image:

1. On the containing element,
you can use the text-align
property with a value of center.

2. On the image itself, you can
use the use the margin property
and set the values of the left and
right margins to auto.

* **Background Images**

* The background-image
property allows you to place
an image behind any HTML
element. This could be the entire
page or just part of the page. By
default, a background image will
repeat to fill the entire box.

* The path to the image follows
the letters url, and it is put
inside parentheses and quotes.

* Background images are often
the last thing on the page to
load (which can make a website
seem slow to load). As with any
images you use online, if the
size of the file is large it will take
longer to download.

* **Repeating Images**

* The background-repeat
property can have four values:

1. repeat

The background image is
repeated both horizontally and
vertically (the default way it
is shown if the backgroundrepeat
property isn't used).

2. repeat-x

The image is repeated
horizontally only.

3. repeat-y

The image is repeated vertically
only.

4. no-repeat

The image is only shown once.


* **Background Position**

* When an image is not being
repeated, you can use the
background-position
property to specify where in the
browser window the background
image should be placed.

* This property usually has a pair
of values. The first represents
the horizontal position and the
second represents the vertical.

* If you only specify one value,
the second value will default to
center.

* **Image Rollovers and Sprites**

* Using CSS, it is possible to create
a link or button that changes to a
second style when a user moves
their mouse over it (known as a
**rollover**) and a third style when
they click on it.

* This is achieved by setting a
background image for the link or
button that has three different
styles of the same button (but
only allows enough space to
show one of them at a time).

* When the user moves their
mouse over the element, or
clicks on it, the position of the
background image is moved to
show the relevant image.

* When a single image is used
for several different parts of an
interface, it is known as a sprite.
You can add the logo and other
interface elements, as well as
buttons to the image.

* The advantage of using sprites is
that the web browser only needs
to request one image rather than
many images, which can make
the web page load faster.


* **CSS3: Gradients**

* CSS3 is going to introduce the
ability to specify a gradient for
the background of a box. The
gradient is created using the
background-image property
and, at the time of writing,
different browsers required a
different syntax.


* **Contrast of background images**

If you want to overlay text on a background image, the image must be low contrast in order for the text to be legible.

* High Contrast

A high contrast background image makes the text difficult to read.

* Low Contrast

A low contrast background image makes the text easier to read.

* Screen

A screen added to a high contrast image makes the texteasier to read.


* You can specify the dimensions of images using CSS.
This is very helpful when you use the same sized
images on several pages of your site.

* Images can be aligned both horizontally and vertically
using CSS.

* You can use a background image behind the box
created by any element on a page.

* Background images can appear just once or be
repeated across the background of the box.

* You can create image rollover effects by moving the
background position of an image.

* To reduce the number of images your browser has to
load, you can create image sprites.



**Practical Information**

* **Search Engine Optimization(SEO)**

* The Basics

* Search engine optimization (or
SEO) is the practice of trying
to help your site appear nearer
the top of search engine results
when people look for the topics
that your website covers.

* At the heart of SEO is the idea of
working out which terms people
are likely to enter into a search
engine to find your site and then
using these terms in the right
places on your site to increase
the chances that search engines
will show a link to your site in
their results.

* In order to determine who comes
first in the search results, search
engines do not only look at what
appears on your site. They also
consider how many sites link
to you (and how relevant those
links are). For this reason, SEO
is often split into two areas:
on-page techniques and off-page
techniques.

* On-Page Techniques

* On-page techniques are the
methods you can use on your
web pages to improve their
rating in search engines.

* The main component of this is
looking at keywords that people
are likely to enter into a search
engine if they wanted to find
your site, and then including
these in the text and HTML code
for your site in order to help the
search engines know that your
site covers these topics.

* Search engines rely very heavily
on the text that is in your pages
so it is important that the terms
people are going to search for
are in text. There are seven
essential places where you want
your keywords to appear.

* Ensuring that any images have
appropriate text in the value of
their alt attribute also helps
search engines understand the
content of images.

* Off-Page Techniques

* Getting other sites to link to you
is just as important as on-page
techniques. Search engines help
determine how to rank your
site by looking at the number of
other sites that link to yours.

* They are particularly interested
in sites whose content is related
to yours. For example, if you
were running a website that
sold fish bait, then a link from
a hairdresser is not likely to be
considered as relevant as one
from an angling community.

* Search engines also look at the
words between the opening
<a> tag and closing </a> tag
in the link. If the text in the link
contains keywords (rather than
just click here or your website
address) it may be considered
more relevant.

* The words that appear in links to
your site should also appear in
the text of the page that the site
links to.

**On-Page SEO**

In every page of your website there are seven key places where keywords (the words people might search on to find your site) can appear in order to improve its findability.

1. Page Title

The page title appears at the top
of the browser window or on the
tab of a browser. It is specified in
the <title> element which lives
inside the <head> element.

2. URL / Web Address

The name of the file is part of
the URL. Where possible, use
keywords in the file name.

3. Headings

If the keywords are in a heading
<hn> element then a search
engine will know that this page is
all about that subject and give it
greater weight than other text.

4. Text

Where possible, it helps to
repeat the keywords in the main
body of the text at least 2-3
times. Do not, however, over-use
these terms, because the text
must be easy for a human to
read.

5. Link Text

Use keywords in the text that
create links between pages
(rather than using generic
expressions such as "click here").

6. Image Alt Text

Search engines rely on you
providing accurate descriptions
of images in the alt text. This
will also help your images show
up in the results of image-based
searches.

7. Page Descriptions

The description also lives inside
the <head> element and is
specified using a <meta> tag.
It should be a sentence that
describes the content of the
page. (These are not shown in
the browser window but they
may be displayed in the results
pages of search engines.)

**How to Identify Keywords and Phrases**

Determining which keywords to use on your site can be one of the
hardest tasks when you start to think about SEO. Here are six steps that will help you identify the right keywords and phrases for your site.

1. Brainstorm

List down the words that
someone might type into
Google to find your site. Be sure
to include the various topics,
products or services your site is
about.

2. Organize

Group the keywords into
separate lists for the different
sections or categories of your
website.

3. Research

There are several tools that let
you enter your keywords and
then they will suggest additional
keywords you might like to
consider.

4. Compare

It is very unlikely that your
site will appear at the top of
the search results for every
keyword. This is especially true
for topics where there is a lot
of competition. The more sites
out there that have already been
optimized for a given keyword,
the harder it will be for you to
rise up the search results when
people search on that term.

5. Refine

Now you need to pick which
keywords you will focus on.
These should always be the ones
that are most relevant to each
section of your site.

6. MAP

Now that you have a refined list
of keywords, you know which
have the most competition, and
which ones are most relevant,
it is time to start picking which
keywords you will use for each
page.


**Analytics: Learning about your Visitors**

As soon as people start coming to your site, you can start analyzing how they found it, what they were looking at and at what point they are leaving. One of the best tools for doing this is a free service offered by Google called Google Analytics.

* Signing Up

The Google Analytics service
relies on you signing up for an
account at:
www.google.com/analytics
The site will give you a piece of
tracking code which you need to
put on every page of your site.

* How it Works

Every time someone loads a
page of your site, the tracking
code sends data to the Google
servers where it is stored.
Google then provides a webbased
interface that allows you
to see how visitors use your site.

* The Tracking Code

A tracking code is provided
by Google Analytics for each
website you are tracking. It
should appear just before the
closing </head> tag. The code
does not alter the appearance of
your web pages.

**How Many People Are Coming to Your Site?**

The overview page gives you a snapshot of the key information you are likely to want to know. In particular, it tells you how many people are coming to your site.

* Visits

This is the number of times
people have come to your site. If
someone is inactive on your site
for 30 minutes and then looks at
another page on your site, it will
be counted as a new visit.

* Unique Visits

This is the total number of
people who have visited your site
over the specified period. The
number of unique visits will be
lower than the number of visits
if people have been returning to
your site more than once in the
defined period.

* Page Views

The total number of pages all
visitors have viewed on your site.

* Pages per Visit

The average number of pages
each visitor has looked at on
your site per visit.

* Average Time on Site

The average amount of time
each user has spent on the site
per visit.

* Date Selector

Using the date selector in the top
right hand corner of the site, you
can change the period of time
the reports display. When you
log in, this is usually set to the
last month, but you can change
it to report on a specific time
period.

* Export

The export link just above the
title that says "visitors overview"
allows you to export the
statistics on this page for other
applications such as Excel.


**What Are Your Visitors Looking At?**

The content link on the left-hand side allows
you to learn more about what the visitors are
looking at when they come to your site.

**Where Are Your Visitors Coming From?**

The traffic sources link on the left hand side
allows you to learn where your visitors are
coming from.

**Domain Names & Hosting**

In order to put your site on the web you will
need a domain name and web hosting.

* **Domain Names**

Your domain name is your web
address (e.g. google.com or bbc.
co.uk). There are many websites
that allow you to register domain
names. Usually you will have to
pay an annual fee to keep that
domain name.

* **Web Hosting**

So that other people can see
your site, you will need to upload
it to a web server. Web servers
are special computers that are
constantly connected to the
Internet. They are specially set
up to serve web pages when
they are requested.

* **Hosted Services**

There are a number of online
services that allow you to point
your domain name to their
servers. Blogging platforms such
as WordPress.com, Tumblr,
and Posterous, or e-commerce
platforms such as Big Cartel and
Shopify provide the servers that
your site is hosted on. If you are
using a platform like this you
will not need your own hosting
for the website, although you
often still need hosting for your
email. If this is the case, some
web hosting companies offer
packages that will just offer
email services.

**FTP & Third Party Tools**

To transfer your code and images from your
computer to your hosting company, you use
something known as File Transfer Protocol.

* As the name suggests, File
Transfer Protocol (or FTP) allows
you to transfer files across the
Internet from your computer to
the web server hosting your site.

* There are many FTP programs
that offer a simple interface
that shows you the files on your
computer alongside the files that
are on your web server. These
allow you to drag and drop
files from your computer to the
server or vice versa.

* Search engine optimization helps visitors find your
sites when using search engines.

* Analytics tools such as Google Analytics allow you to
see how many people visit your site, how they find it,
and what they do when they get there.

* To put your site on the web, you will need to obtain a
domain name and web hosting.

* FTP programs allow you to transfer files from your
local computer to your web server.

* Many companies provide platforms for blogging, email
newsletters, e-commerce and other popular website
tools (to save you writing them from scratch).

**Flash**

Flash is a very popular technology used
to add animations, video, and audio to
websites.

* **How Flash Works**

Since the late 1990s, Flash has been a very
popular tool for creating animations, and later
for playing audio and video in websites.

* **Use of Flash**

Since 2005, a number of factors have meant
that fewer websites are written in Flash or even
use elements of Flash in their pages.

