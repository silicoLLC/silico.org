---
layout: home
title: About me
---

I am a biologist with 10 years of computational and bench research experience. Throughout my career, I have generated, analyzed, and integrated genomic and other biological information to understand processes driving genome regulation, disease, and phenotypic variation. I apply intensive exploratory data analysis, data visualization, and statistical approaches to address large-scale problems using genomic, epigenomic, transcriptomic, and proteomic data.

I am a Research Fellow at [Harvard Medical School](https://genetics.med.harvard.edu/sinclair/), and a freelance computational/molecular biologist for [hire](/hire). I blog about aging, genomics, and cutting-edge technologies.
### Interested in working with me?

If you are working in the areas of aging, age-associated diseases, cutting-edge genomics, or data science, [contact me](/contact/) if you are interested in collaborating. If there is sufficient mutual interests and benefit in working together, there may be the possibility of collaborating with me in my capacity at Harvard Medical School.

If your project does not qualify for a collaboration, you may be able to [hire](/hire) me. [Contact me](/contact) me for more information.

### Interested in working for me?

I am always seeking talented, motivated trainees and aspiring bioinformaticians to collaborate with, both at [Harvard](https://genetics.med.harvard.edu/sinclair/) and at [silico](/hire). Remote positions are available in some situations. [Contact me](/contact) for more information.

<main id="main" class="site-main">
<br>
<br>

<!-- Posts Index -->
<div class="post-feed inner">
    {% if page.url == "/" %}
    <div class="post-feed-title">Blog posts</div>
    {% endif %}
    <div class="post-feed inner-wide">
        {% for post in site.posts %}
            {% include postbox.html %}
        {% endfor %}
    </div>
</div>

</main>