<h2>{{ site.data.cookbook_pages.docs_list_title }}</h2>
<ul>
   {% for item in site.data.cookbook_pages.docs %}
      <li><a href="{{ item.url }}">{{ item.title }}</a></li>
   {% endfor %}
</ul>
