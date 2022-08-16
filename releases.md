---
layout: page
title: "Releases"
permalink: /releases/
share-description: "Thank you for taking an interest in what I do!"
---

Thank you for taking an interest in what I do! I am currently celebrating my first release on the DMs Guild, a pay what you want supplement for Curse of Strahd called the [Leader of the Pack](https://www.dmsguild.com/product/406741/Leader-of-the-Pack){:target="_blank"}. In the future you can use [this link](https://www.dmsguild.com/browse.php?author=YetAnotherTyler){:target="_blank"} to find all my releases on the DM's Guild.

<ul style="list-style-type:none">
{% for tag in site.tags %}
  {% if tag[0] == "DMs Guild" %}
    {% for post in tag[1] %}
        {{ post.excerpt }}
    {% endfor %}
  {% endif %}
{% endfor %}
</ul>

<center><script type='text/javascript' src='https://storage.ko-fi.com/cdn/widget/Widget_2.js'></script><script type='text/javascript'>kofiwidget2.init('Support Me on Ko-fi', '#29abe0', 'X8X2241SV');kofiwidget2.draw();</script></center>