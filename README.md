# Backbone at Disqus: A Postmortem

This is a talk I gave at [BackboneConf 2013](http://backboneconf.com) in Boston.

Here's the synopsis:

<blockquote><p>Disqus is the web's largest discussion community. We process millions of comments every day, across hundreds of thousands of websites, including CNN, IGN, Rolling Stone, MLB.com, and NPR – to name a few.</p>

<p>Early last year we re-wrote our embedded commenting application from the ground up using Backbone. Being a non-standard application (embedded in other people's websites), working with a not-quite-RESTful API, built on a set of terribly unpopular microlibraries (Ender), we've had to bend Backbone to do terrible – and sometimes neat – things.</p>

<p>In this talk, I'll walk through the architecture of the "new Disqus application and our relationship with Backbone. I'll explain why and how we use iframes, and how it affects Backbone's development model. I'll also talk about some unique hacks we do with models, and how we communicate with our legacy-ish API.</p></blockquote>

## Building the slides

These slides are built on [reveal.js](https://github.com/hakimel/reveal.js/). Check out their README for instructions.

## License

http://creativecommons.org/licenses/by/2.0/

(Basically, just say you got it here and we're cool.)
