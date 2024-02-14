---
permalink: /ABOUT/
---

# About

This is a Github Page made for SP241. I can add whatever I want in it and nobody can stop me! (unless if I sound too condescending).
Everything is written using Neovim and terminal, no fancy GUI needed.

<br>
# More Information

<ul><li>
{% for ii in site.navbarlinks %}
  {% if ii.navbar == "GitHub Page" %}
    <a href="{{ ii.link | relative_url }}">{{ ii.navbar }}</a>
  {% endif %}
{% endfor %}
</li><li>
{% for ii in site.navbarlinks %}
  {% if ii.navbar == "GitHub" %}
    <a href="{{ ii.link | relative_url }}">{{ ii.navbar }}</a>
  {% endif %}
{% endfor %}
</li></ul><br>

# This is the Way!



