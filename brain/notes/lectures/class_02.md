Subject: #HTML
Date: {{date}}
Course: 100devs

## Main Points
- The internet connects *servers* and *clients* to one another for communication
- Remember the golden rule: *Separation of Concerns*. Essentially, keep projects broken down into units.
- Project standards and stakeholder needs will make every project different (headings, tag selection, etc.)

## Notes
- [[HTML]], [[CSS]], [[JavaScript]] is all code that runs on the client-side
- Since HTML5, new containing elements have been introduced
	- ``<div> </div>`` : basic division
	- ``<section> </section>`` : for grouping like content together
	- ``<article> </article>`` : for content meant to be shared
	- ``<aside> </aside>`` : for extra content
	- ``<header> </header>`` : for content at the beginning of the doc
	- ``<footer> </footer>`` : for content at the end of the doc

## Questions/Cues
- What is the primary function of a server on the internet?
	- Listens for requests and has code running on it that is capable of responding to them
- Why are HTML and CSS not considered programming languages? What are they called?
	- They are *markdown* languages.
	- The Adam Turing Principle requires a programming language to respond to an operation with a response
- What is the ``<span>`` tag for and how does it differ from ``<p>``?
	- ``<span>`` tag is for a short line of text, whereas ``<p>`` can be used for multi-line paragraphs, blocks of text, etc.
- What is the ``<pre>`` tag and should you ever use it?
	- It preserves whitespace in text, but apparently everyone hates it
- What would be good content for an ``<aside>`` tag?
	- Advertisements, sidebars, call-out boxes
- What is the only reason for using ``<h1>`` or any other heading tags?
	- Displaying the *most important* information. Size/position/etc does not matter
- Why are some tags such as ``<blink>`` and ``<marquee>`` considered deprecated elements?
	- They provide function similarly to what CSS, which violates separation of concerns
- What is the smallest heading tag available?
	- The ``<h6>`` tag is used for the least important headings (usually smallest)
- How would you link another page for navigation on a site?
	- With the ``<a>`` tag linking to the other .html file for the different webpage