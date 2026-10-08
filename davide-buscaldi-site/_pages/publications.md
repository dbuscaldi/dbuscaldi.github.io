---
layout: page
permalink: /publications/
title: publications
description: Publications by category, in reverse chronological order.
nav: false
---

{% include bib_search.liquid %}

<div class="publications">

<h2 class="bibliography">International conferences</h2>
{% bibliography --query @*[keywords=intconf] %}

<h2 class="bibliography">International journals with SJR ranking</h2>
{% bibliography --query @*[keywords=journal] %}

<h2 class="bibliography">Other journals</h2>
{% bibliography --query @*[keywords=otherjournal] %}

<h2 class="bibliography">International workshops</h2>
{% bibliography --query @*[keywords=workshop] %}

<h2 class="bibliography">National conferences and workshops</h2>
{% bibliography --query @*[keywords=national] %}

<h2 class="bibliography">As editor</h2>
{% bibliography --query @*[keywords=editor] %}

</div>
