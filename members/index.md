---
title: Members
nav:
  order: 3
  tooltip: Members
---

# <i class="fas fa-users"></i>Members



{% include section.html %}
# Professor
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{% include section.html %}

# MS Students
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: ms"
%}
{% include section.html %}
# Research Interns
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}

{:.center}

{% include section.html %}

## Alumni
