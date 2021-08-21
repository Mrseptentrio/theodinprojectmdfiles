# HTML

[HTML](http://en.wikipedia.org/wiki/HTML), meaning “HyperText Markup Language”, is a document format used for defining the semantic structure of a single web page. One could say that HTML is what the internet is made of: All the websites that we are looking at every day are all defined (described) as HTML.

HTML was first proposed by [Tim Berners-Lee](http://en.wikipedia.org/wiki/Tim_Berners-Lee) in 1989, and layed grounds for the World Wide Web’s huge breakthrough during the 1990s. It is defined by the [W3C](http://en.wikipedia.org/wiki/World_Wide_Web_Consortium) and it’s latest version is [HTML 5](http://en.wikipedia.org/wiki/HTML5) which added a bunch of exciting, and useful features.

The fundamental, primary feature of any web browser, such as Firefox, Chrome, Safari, is to render (display) HTML documents:

Whenever you type a URL into the browser’s address bar (or click a link, such as [](http://rubymonstas.org)[http://rubymonstas.org](http://rubymonstas.org)) then the browser will send a request to this address (i.e. to some application running on some computer that responds to this address), and it will (in most cases) get an HTML document back as a response, which it will display to you.

What is meant by “semantic structure” though?

Maybe it is best to look at an example first. This is a fairly simple, but valid HTML document:

```
<html>
  <head>
    <title>Ruby Monstas HTML Example</title>
  </head>
  <body>
    <h1>Ruby Monstas HTML Example</h1>
    <p>One paragraph of text.</p>
    <p>Another paragraph of text, containing an emphasized <em>word</em>.</p>
    <h2>A list of items</h2>
    <ul>
      <li>First item</li>
      <li>Second item</li>
      <li>Third item</li>
    </ul>
  </body>
</html>
```

If you look at this document you’ll notice the recurring pattern of “tags” that start with `<something>` and then are closed with `</something>`. E.g. the entire document starts with an opening `<html>` tag, and ends with a closing `</html>` tag.

HTML entirely consists of these tags that have a certain meaning, can be nested, and contain content.

Here’s what the HTML tags used in this example mean:

-   `<html>...</html>` - the HTML document as a whole
-   `<head>...</head>` - the header of the document, containing meta information (i.e. information _about_ the document, not _part of_ the document itself)
-   `<title>...</title>` - an example of one bit of meta information, the title of the page as displayed in your browser history, and the browser window title (or tab)
-   `<body>...</body>` - the body of the document itself, i.e. the whole of its content
-   `<h1>...</h1>`, `<h2>...</h2>` - a headline level 1, and level 2, containing the headline’s text. HTML defines heading levels 1-6, which should be enough to define the structure even of large documents.
-   `<p>...</p>` - a single paragraph, containing the paragraph’s text.
-   `<ul>...</ul>` - an unordered list (i.e. a list that uses bullet points, as opposed to, e.g., a numbered list)
-   `<li>...</li>` - a single list item, must be contained in either a `<ul>` or `<ol>` tag

You can read `<html>` as _“Ok, let’s start an HTML document!”_. Then `<head>` says: _“Oh, btw, here’s some extra meta information about the document …”_ and `<title>` says: _“The title of this document is: […]”_. `</title>` meaning _“Ok, we’re done with the title”_, just like `</head>` meaning _“Ok, we’re done with the meta information part.”_

When the browser sees `<body>` it reads that as _“Ok, now here comes the real content part of the document.”_

Inside that content section it first finds an `<h1>` tag, and reads _“Aha, the main headline is […]”_, so it will display this as a headline to you. It then finds two `<p>` tags containing a few bits of plain text, so it displays two paragraphs. The last paragraph has an emphasized word, so it makes that one cursive (or something else, depending on style definitions defined elsewhere). Next it finds a 2nd level headline `<h2>`, and then an “unordered list” `<ul>`, i.e. a list with bullet points.

It is important to understand that HTML only defines the **semantic structure** of a document. It does, as such, say nothing about the visual representation of, for example, a headline, the spacing between paragraphs, the font family and size used, any colors, borders, or even element placement: The visual representation is defined in a different language called [CSS](http://en.wikipedia.org/wiki/Cascading_Style_Sheets) (or by the browser’s defaults, should there not be any custom style definition for this web page, as in our example above).

Why is the semantic structure of a document useful at all, even disregarding its visual styling when presented in the browser window?

Maybe the simplest example is a link. In order to describe a link in text (HTML is stored as plain text) we’ll need to tell three pieces of information to the browser:

-   That we’d like to define a link,
-   what text to display for the link, and
-   what other web address to link to.

This is a valid example of a link in HTML, using the tag `a` (which means “anchor”):

```
<a href="http://rubymonstas.org">Ruby Monstas Homepage</a>
```

This HTML, when rendered in a web browser, looks like this: [Ruby Monstas Homepage](http://rubymonstas.org), i.e. there’s a link with the text “Ruby Montas Homepage” and it links to the target URL (“href”) [http://rubymonstas.org](http://rubymonstas.org).

Does this make sense?

This is why HTML is called a “markup language”. It is a language that “marks up” certain each part of the content with its structural meaning, such as _“This is a link, with this target URL”_, or _“This is a heading with this level”_, _“This is a simple paragraph”_, and so on.

If you think about it, there are lots of useful applications, that leverage the information that is provided by defining the **semantic structure** of a document (as opposed to its visual representation).

For example, one could apply different “themes”, as in styles, to the same HTML page depending on people’s preferences, or depending on the device this website is displayed on (e.g. desktop browser windows versus mobile devices).

But also, the entire success of Google as a search engine relied on the fact that the semantic structure of a document provides clues about the relevance of certain search terms in this document: If a word is contained in the URL, the document title, the toplevel headlines, then it’s probably important. Even more so, if other pages link to this document using link texts that also contain that word, then this adds social proof to the mix, and search results should probably list this page higher up in the results.

Another example is that, by inspecting the headline tags in an HTML document, we can auto-generate a table of contents for this document quite easily, without having authors maintain this manually. Many content management systems (CMS) do this, including Wikipedia.