---
title: Team
---

# <i class="fas fa-users"></i>Team
<!-- section break -->
{% capture contents %}
{% include team-list.html role="pi" %}
{% include team-list.html role="phd" group="" %}
{% include team-list.html role="programmer" group="" %}
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

## Alumni
{% capture alumni %}
{%include team-list.html role="phd" group="alumni" mini=true%}
{%include team-list.html role="master" group="alumni" mini=true%}
{%include team-list.html role="tech" group="alumni" mini=true%}
{%include team-list.html role="undergrad" group="alumni" mini=true %}
{% endcapture %}
{% include centerer.html contents=alumni %}

<!-- section break -->

## Funding
Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  fit="false"

  image1="images/funding/nsf.jpg"
  link1="https://www.nsf.gov/policies/logos.jsp"
  tooltip1="National Science Foundation"

%}
