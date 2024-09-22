---
layout: default
title: Home
---

# Welcome

The Quran is the main holy book of Islam, which Muslims believe to be a direct revelation from God.

Muslims assert that the Quran is:
- The eternal, uncreated word of God
- Perfect and free from error
- A guidance for all aspects of life
- Containing prophecies and scientific knowledge beyond human capacity

Quran.sh was created to explore these claims and others made about the Quran and to see if they hold up to scrutiny.

[Why do issues in the Quran matter?]({{ site.baseurl }}/issues)
## Issues in the Quran

<ul>
  {% for post in site.categories.quran-issues %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
