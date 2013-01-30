Mantle
======

Mantle is an easy rendering layer for [Axilent](http://www.axilent.com), the modern platform for ubiquitous publishing.  Mantle is designed to make it possible for someone with front-end web development skills (HTML/JS/CSS) build a website that pulls content from Axilent and otherwise interacts with the [Axilent API](https://www.axilent.net/api/docs/).

The Mantle implementation is written in Python as a WSGI application, however no knowledge of Python is required to use Mantle.  It just requires front-end development skills and the configuration of a few parameters.

Mantle uses [Mustache templates](http://http://mustache.github.com/), a simple "logicless" template system.  Mustache templates allow Mantle to integrate Axilent content with your website designs exactly as you specify.

Mantle provides:

* [Content Channel](http://docs.axilent.com/article/content-channels/) access.
* The ability to map URIs to [Triggers](http://docs.axilent.com/article/triggers/).
* Retrieve content items with specific Content Flavors defined.
* Proxy requests and responses to third party applications, allowing you to integrate your Mantle based site with any web application.
* Define blocks of markup as specific to a particular Content Flavor or User Profile Segment.

Early Warning
-------------

This project is just starting, so you shouldn't depend on it for a production website just yet.