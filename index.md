---
title: Home
layout: default
---

{% capture text %}

<div class="row">
    <div class="col-sm-4">
        <img class="img-fluid" src="{{ '/images/lotfull.jpg' | relative_url }}">
    </div>
    <div class="col-sm-8">
        <p><strong>Corey Oglesby</strong> is a poet and artist originally from the Washington, DC, area, and he is also me. My poems and poem-comics have appeared recently or are forthcoming in <em>Beloit Poetry Journal</em>, <em>Barrow Street</em>, <em>Diagram</em>, <em>Hobart</em>, <em>Puerto del Sol</em>, <em>jubilat</em>, and elsewhere. Formerly the Editor-in-Chief of <em>Fugue</em>, I currently live and make things in Moscow, Idaho.</p>
        <p><u>Follow me on social media:</u><br>Twitter: <a href="https://twitter.com/Coreyoglesby">@Coreyoglesby</a><br>Instagram: <a href="https://www.instagram.com/corey.oglesby/?hl=en">@corey.oglesby</a></p>
    </div>

{% endcapture %}
{% include card.md text=text %}