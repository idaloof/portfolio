---
Title: About
Desription: Page about the page
---

About this web page
=======================

The content of this page is a collaboration between talented people at Blekinge Institute of Technology and me, Martin Fooladi (1st year student).

Down below you can read about this web page and the technologies we have used to create it.

Pico
-----------------------
Pico is a simple, flat file CMS. Basically it means that there is no backend administration or database to deal with. One of many advantages is that you are safe from SQL-injections, which can be a security issue when working with databases.

Contents are created in Markdown files, which become your pages.

MarkDown
-----------------------
The use of Markdown is simple. It is a plain text language whose purpose is to make writing for the internet easier. 

In contrast to HTML (Hyper Text Markup Language) it is more readable in the sence that no tags are used (although it is possible to use HTML in a Markdown file).

The links in the above menu and their contents are available in Markdown files.

Twig
-----------------------
Twig is a modern template engine for PHP, which is roughly a way to output variables inside HTML. With help of delimiters you are able to :

* {{ ... }} --> print content of variables
* {# ... #} --> add comments in templates
* {% ... %} --> execute statements

SASS
-----------------------
SASS is a preprocessor to CSS. The advantage with using SASS for your projects is that is has features that don't exist in CSS (yet).

For example you are able to nest CSS rules for a more compact code. Say you have a nav-element in which you have several tags. By nesting them inside the nav-element, you are able to write less code and at the same time maintain legibility.


    nav {
        ul {
            background-color: #eee;
        }
        li {
            list-type: none;
        }
        a {
            text-decoration: none;
        }
    }


You can use mixins to apply often recurring CSS rules to several elements/tags/classes/IDs without having to write the rules over and over again. Code yor mixin and apply it wherever you want using `@mixin`.

Summary
-----------------------
So, in summary. This web page contains a lot of technologies. I'm still trying to comprehend all of it, but 

I want to send a thanks to all of the people who have contributed to this page. I'm very grateful that I have the opportunity to learn all of this!

I hope you've enjoyed reading this. 

Take care!

/Martin