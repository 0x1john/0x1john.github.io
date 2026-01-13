---

layout: default

title: All Tags

permalink: /categories/all-tags/

---



<h2>All Categories</h2>



<ul>

{% for category in site.categories %}

&nbsp; <li>

&nbsp;   <a href="/categories/{{ category\[0] }}/">

&nbsp;     {{ category\[0] }} ({{ category\[1].size }})

&nbsp;   </a>

&nbsp; </li>

{% endfor %}

</ul>



