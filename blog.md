---
layout: page
title: Blog
#featured_image: /assets/images/pages/about.jpg
---



<main id="main" class="site-main">

<!-- Posts Index -->
<div class="post-feed inner">
    <!-- {% if page.url == "/" %} -->
    <!-- <div class="post-feed-title">Blog posts</div> -->
    <!-- {% endif %} -->
    <div class="post-feed inner-wide">
        {% for post in site.posts %}
            {% include postbox.html %}
        {% endfor %}
    </div>
</div>

</main>
