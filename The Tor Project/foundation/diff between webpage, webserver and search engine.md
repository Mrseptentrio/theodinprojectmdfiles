## [Summary](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Pages_sites_servers_and_search_engines#summary "Permalink to Summary")

As with any area of knowledge, the web comes with a lot of jargon. Don't worry, we won't overwhelm you with all of it (we have a [glossary](https://developer.mozilla.org/en-US/docs/Glossary) if you're curious). However, there are a few basic terms you need to understand at the outset, since you'll hear these expressions all the time as you read on. It's easy to confuse these terms sometimes since they refer to related but different functionalities. In fact, you'll sometimes see these terms misused in news reports and elsewhere, so getting them mixed up is understandable!

We'll cover these terms and technologies in more detail as we explore further, but these quick definitions will be a great start for you:

# web page

A document which can be displayed in a web browser such as Firefox, Google Chrome, Opera, Microsoft Internet Explorer or Edge, or Apple's Safari. These are also often called just "pages."

# website

A collection of web pages which are grouped together and usually connected together in various ways. Often called a "web site" or a "site."

# [web server]

A computer that hosts a website on the Internet

# search engine

A web service that helps you find other web pages, such as Google, Bing, Yahoo, or DuckDuckGo. Search engines are normally accessed through a web browser (e.g. you can perform search engine searches directly in the address bar of Firefox, Chrome, etc.) or through a web page (e.g. [bing.com](https://www.bing.com/) or [duckduckgo.com](https://duckduckgo.com/)).

Let's look at a simple analogy — a public library. This is what you would generally do when visiting a library:

1.  Find a search index and look for the title of the book you want.
2.  Make a note of the catalog number of the book.
3.  Go to the particular section containing the book, find the right catalog number, and get the book.

Let's compare the library with a web server:

-   The library is like a web server. It has several sections, which is similar to a web server hosting multiple websites.
-   The different sections (science, math, history, etc.) in the library are like websites. Each section is like a unique website (two sections do not contain same books).
-   The books in each section are like webpages. One website may have several webpages, e.g., the Science section (the website) will have books on heat, sound, thermodynamics, statics, etc. (the webpages). Webpages can each be found at a unique location (URL).
-   The search index is like the search engine. Each book has its own unique location in the library (two books cannot be kept at the same place) which is specified by the catalog number.


## [Deeper dive](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Pages_sites_servers_and_search_engines#deeper_dive "Permalink to Deeper dive")

So, let's dig deeper into how those four terms are related and why they are sometimes confused with each other.

### [Web page](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Pages_sites_servers_and_search_engines#web_page "Permalink to Web page")

A **web page** is a simple document displayable by a [browser](https://developer.mozilla.org/en-US/docs/Glossary/Browser). Such documents are written in the [HTML](https://developer.mozilla.org/en-US/docs/Glossary/HTML) language (which we look into in more detail in [other articles](https://developer.mozilla.org/en-US/docs/Web/HTML)). A web page can embed a variety of different types of resources such as:

-   _style information_ — controlling a page's look-and-feel
-   _scripts_ — which add interactivity to the page
-   _media_ — images, sounds, and videos.

**Note:** Browsers can also display other documents such as [PDF](https://developer.mozilla.org/en-US/docs/Glossary/PDF) files or images, but the term **web page** specifically refers to HTML documents. Otherwise, we only use the term **document**.

All web pages available on the web are reachable through a unique address. To access a page, just type its address in your browser address bar:

![Example of a web page address in the browser address bar](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Pages_sites_servers_and_search_engines/web-page.jpg)

### [Web site](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Pages_sites_servers_and_search_engines#web_site "Permalink to Web site")

A _website_ is a collection of linked web pages (plus their associated resources) that share a unique domain name. Each web page of a given website provides explicit links—most of the time in the form of clickable portion of text—that allow the user to move from one page of the website to another.

To access a website, type its domain name in your browser address bar, and the browser will display the website's main web page, or _homepage_ (casually referred as "the home"):

![Example of a web site domain name in the browser address bar](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Pages_sites_servers_and_search_engines/web-site.jpg)

The ideas of a _web page_ and a _website_ are especially easy to confuse for a _website_ that contains only one _web page._ Such a website is sometimes called a _single-page website._

### [Web server](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Pages_sites_servers_and_search_engines#web_server "Permalink to Web server")

A _web server_ is a computer hosting one or more _websites_. "Hosting" means that all the _web pages_ and their supporting files are available on that computer. The _web server_ will send any _web page_ from the _website_ it is hosting to any user's browser, per user request.

Don't confuse _websites_ and _web servers_. For example, if you hear someone say, "My website is not responding", it actually means that the _web server_ is not responding and therefore the _website_ is not available. More importantly, since a web server can host multiple websites, the term _web server_ is never used to designate a website, as it could cause great confusion. In our previous example, if we said, "My web server is not responding", it means that multiple websites on that web server are not available.

### [Search engine](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Pages_sites_servers_and_search_engines#search_engine "Permalink to Search engine")

Search engines are a common source of confusion on the web. A search engine is a special kind of website that helps users find web pages from _other_ websites.

There are plenty out there: [Google](https://www.google.com/), [Bing](https://www.bing.com/), [Yandex](https://www.yandex.com/), [DuckDuckGo](https://duckduckgo.com/), and many more. Some are generic, some are specialized about certain topics. Use whichever you prefer.

Many beginners on the web confuse search engines and browsers. Let's make it clear: A _**browser**_ is a piece of software that retrieves and displays web pages; a **_search engine_** is a website that helps people find web pages from other websites. The confusion arises because, the first time someone launches a browser, the browser displays a search engine's homepage. This makes sense, because, obviously, the first thing you want to do with a browser is to find a web page to display. Don't confuse the infrastructure (e.g., the browser) with the service (e.g., the search engine). The distinction will help you quite a bit, but even some professionals speak loosely, so don't feel anxious about it.

[find this article](https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/how-does-the-web-work)