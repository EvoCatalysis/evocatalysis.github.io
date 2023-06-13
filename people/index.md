---
title: People
nav:
  order: 2
---

# <i class="fas fa-users"></i>People

{% include section.html %}

## Current Members

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: manager"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: technician"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: grad-student"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}

{% include section.html %}

{% comment %}

## Alumni

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: alum"
%}
{% endcomment %}

{:.center}
