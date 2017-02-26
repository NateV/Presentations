---
layout: page
title: Decks
permalink: /decks/
---

<h1> Decks </h1>
<div class="decks-container">
    {% for deck in site.decks %}
    <div>
        {% include deck_blurb.html deck=deck %}
    </div>
    {% endfor %}
</div>
