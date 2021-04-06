---
title: Team
---

# <i class="fas fa-users"></i>Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

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
