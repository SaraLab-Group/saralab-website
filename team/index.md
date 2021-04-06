---
title: Team
---

# <i class="fas fa-users"></i>Team
<!-- section break -->
{% capture contents %}
{% include team-list.html role="pi" %}
{% include team-list.html role="phd" %}
{% include team-list.html role="programmer" %}
{% endcapture %}

{% include centerer.html contents=contents %}
<!-- section break -->
<!-- section dark -->
<!-- section background images/banner.jpg -->

We are insterested in developing new optical imaging techniquesand novel image analysis tools in collaboration. We are always in the lookout for new ideas.
{%
  include big-link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
  button=true
%}{:.center}

<!-- section break -->
# Alumni
<!-- section break -->
{% capture contents %}
{%include team-list.html role="phd group="alumni"%}
{% endcapture %}
<!-- section break -->


## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  fit="false"

  image1="images/photo.jpg"
  link1="https://nasa.gov/"
  tooltip1="Cool Foundation"

  image2="images/photo.jpg"
  link2="https://nasa.gov/"
  tooltip2="Cool Institute"
%}
