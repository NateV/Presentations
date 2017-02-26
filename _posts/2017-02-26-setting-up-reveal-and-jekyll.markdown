---
layout: post
title:  "Setting up Reveal and Jekyll"
date:   2017-02-24 16:46:33 -0500
---

1. Create a new Jekyll site.

Github pages does not appear to work with all versions of Jekyll. See this site: https://pages.github.com/versions/ to see what versions of Jekyll are compatible.

2. Initialize git repository for the new site

3. Add revealjs as a submodule

`git add submodule https://github.com/hakimel/reveal.js/`

4. Add a "deck" layout

`mkdir \_layouts` if necessary.
`touch deck.html`

5. Add a decks page

6. Create a "decks" collection

7. Other kinds of customization will probably be useful.

Now to create a new presentation, simply create your presentation as a series of <section> elements in a markdown file in the "\_decks" directory.

_Useful Resources_
* [Github's how-to](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/#keeping-your-site-up-to-date-with-the-github-pages-gem)
