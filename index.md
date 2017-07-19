---
layout: default
---


<header>
    <div class="header-content" id="start">
        <div class="header-content-inner">
            {% capture start %}{% include start.md %}{% endcapture %}
            {{ start | markdownify }}
        </div>
    </div>
</header>

<section class="bg-primary" id="about">
    <div class="container">
        <div class="row">
            <div class="col-lg-8 col-lg-offset-2 text-center">
                {% capture about %}{% include about.md %}{% endcapture %}
                {{ about | markdownify }}
            </div>
        </div>
    </div>
</section>

<section id="menu">
    <div class="container">
        <div class="row">
            <div class="col-lg-8 col-lg-offset-2 text-center">
                {% capture menu %}{% include menu.md %}{% endcapture %}
                {{ menu | markdownify }}
            </div>
        </div>
    </div>
</section>

<section class="bg-primary" id="contact">
    <div class="container">
        <div class="row">
            <div class="col-lg-8 col-lg-offset-2 text-center">
                {% capture contact %}{% include contact.md %}{% endcapture %}
                {{ contact | markdownify }}
            </div>
        </div>
    </div>
</section>

