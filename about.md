---
layout: blue_page
permalink: /about/
title: About
---

RustFest is Europe’s Rust-dedicated conference. The one day event will take place in Kyiv.

We care about diversity and accessibility at this conference.

<section>
  <h2>Team</h2>
  <ul class="team">
    {% for entry in site.data.team %}
      {% assign member=entry[1] %}
      <li>
        {% include team-member.html member=member %}
      </li>
    {% endfor %}
  </ul>
</section>
