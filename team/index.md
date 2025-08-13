---
title: Members
nav:
  order: 3
  # tooltip: About our lab
---

# {% include icon.html icon="fa-solid fa-users" %}Members

<!-- members -->

## Faculty

{% include list.html data="members" component="portrait" filters="role: professor" %}
{% include section.html %}

## Graduate Students

{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: ms" %}
{% include section.html %}

## Undergraduate Interns

{% include list.html data="members" component="portrait" filters="role: undergrad" %}

## Visiting Researchers

{% include list.html data="members" component="portrait" filters="role: visiting" %}

## Affiliated Members

{% include list.html data="members" component="portrait" filters="role: affiliated" %}

## Alumni

### Master's Student

{% include list.html data="members" component="portrait-list" filters="role: alumni, status: ms" %}

### Visiting Researcher

{% include list.html data="members" component="portrait-list" filters="role: alumni, status: visiting" %}

### Undergraduate Interns

{% include list.html data="members" component="portrait-list" filters="role: alumni, status: undergrad" %}

<!-- {% include list.html data="members" component="portrait" filters="role: ^(?!professor$)" %} -->

{% capture content %}

<!-- {% include figure.html image="images/photo.jpg" %} -->

{% endcapture %}

{% include grid.html style="square" content=content %}
