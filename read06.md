# What is CSS?
### CSS (Cascading Style Sheets) allows you to create great-looking web pages, but how does it work under the hood? This article explains what CSS is, with a simple syntax example, and also covers some key terms about the language.
 As mentioned before, CSS is a language for defining how documents are presented to users - how they are designed, laid out, etc.

The document is usually a text file structured using a markup language - HTML is the most popular markup language, but you may also come across other markup languages such as SVG or XML.

Presenting a document to a user means turning it into a form that can be used by your audience. Browsers, such as Firefox, Chrome or Edge, are designed to present documents visually, for example, on a computer screen, monitor, or printer.

# there are type of css.
+ CSS syntax
CSS is a rule-based language — you define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page. For example "I want the main heading on my page to be shown as large red text

 h1 {
    color: red;
    font-size: 5em;
}

+ CSS Modules
As there are so many things that you could style using CSS, the language is broken down into modules. You'll see reference to these modules as you explore MDN and many of the documentation pages are organized around a particular module. For example, you could take a look at the MDN reference to the Backgrounds and Borders module to find out what its purpose is, and what different properties and other features it contains. You will also find links to the CSS Specification that defines the technology (see below).

For more details please join link :)
[What is CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

# the second thing is how to add CSS?
Three Ways to Insert CSS
There are three ways of inserting a style sheet:

1. External CSS
2. Internal CSS
3. Inline CSS

## external CSS
You can only recognize one model!
Each HTML page must contain a reference to the external stylesheet file inside the <link> element, inside the header section.
+ example:

link rel="stylesheet" href="mystyle.css">

## Internal CSS
An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the <style> element, inside the head section.

 background-color: linen;

 ## Inline CSS

An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

for more details please join link :)

[ who to add CSS](https://www.w3schools.com/css/css_howto.asp)

# CSS Tools: Reset CSS

## The goal of a reset stylesheet is to reduce browser inconsistencies in things like:
 default line heights, margins and font sizes of headings, and so on. The general reasoning behind this was discussed in a May 2007 post, if you're interested. Reset styles quite often appear in CSS frameworks, and the original "meyerweb reset" found its way into Blueprint, among others.

The reset styles given here are intentionally very generic. There isn't any default color or background set for the body element, for example. I don't particularly recommend that you just use this in its unaltered state in your own projects. It should be tweaked, edited, extended, and otherwise tuned to match your specific reset baseline. Fill in your preferred colors for the page, links, and so on.

In other words, this is a starting point, not a self-contained black box of no-touchiness.

If you want to use my reset styles, then feel free! It's all explicitly in the public domain (I have to formally say that or else people ask me about licensing). You can grab a copy of the file to use and tweak as fits you best. If you're more of the copy-and-paste type, or just want an in-page preview of what you'll be getting, here it is.

the link [CSS Tools: Reset CSS
]

(https://meyerweb.com/eric/tools/css/reset/)

 
 



