# A travel blog of the Gerber family

We are bound for Berlin, Germany for a year.  We hope to keep in touch with friends and family while we're away.  Here you're see what we've been up to, through the eyes Moomin and Gingy!

# News

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
