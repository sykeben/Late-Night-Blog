# :sleepy: Late Night Blog
*A blog created at 11:30pm on a Sunday night by a tired college student.*

## Posts
<ul>
  {% for post in site.posts %}
    <li>
    	<a href="{{ post.url }}">{{ post.date }}: {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>