---
layout: post
title: "A Site Aside"
date: 2020-06-21
---

I thought I would play around with the website before I begin my
[learning journey]({% post_url 2020-06-18-first-post %}).
I spent some time over the weekend looking at [Jekyll](https://jekyllrb.com/) and
[Liquid](https://shopify.github.io/liquid/), the static-site generator and template language, respectively, that are
provided by default for [GitHub Pages](https://pages.github.com/) projects.

I added a couple more sections to the site in order to use the functionality that these provide:
[Albums](/albums) and [Films](/films).

The Albums page is a list of music albums that I have listened to and rated. These albums are selected from
[Acclaimed Music](http://acclaimedmusic.net/) as I work my way through the _All Time Top 3,000_ in descending order.

Similarly, the Films page is a list of films I have watched and rated. For films, I use
[TSPDT]()'s _1,000 Greatest Films_ which, again, I am working through from bottom to top.

Both the Albums and Films pages use Jekyll and Liquid to read YAML data files and generate HTML lists of artists,
directors and their respective works. When I have watched a film, or listened to an album, I just
update the YAML files and Jekyll will do the rest.

The homepage has also been updated and now shows the three latest diary entries, album ratings and film ratings.

I have tried to use
[semantic HTML elements](https://developer.mozilla.org/en-US/docs/Glossary/semantics#Semantics_in_HTML) throughout the
website, while also styling the elements in a simple, accessible way. I was inspired by the designs of
[Inclusive Components](https://inclusive-components.design/), [Every Layout](https://every-layout.dev/) and
[Andy Bell](https://hankchizljaw.com/).

It's not perfect, and will be tweaked continuously, but it does its job.
