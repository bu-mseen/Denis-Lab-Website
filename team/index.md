---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi, group:"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc, group:"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd, group:"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: programmer, group:"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: mds, group:"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: masters, group:"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad, group:"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: RA, group:"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: Lab Technician, group:"
%}{:.center}


{% include section.html background="images/site_wide/Site Banner.png" dark=true%}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

## Join

### Lab Alumni

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc, group: alum"
  style="small"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd, group: alum"
  style="small"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: mds, group: alum"
  style="small"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: masters, group: alum"
  style="small"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad, group: alum"
  style="small"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: RA, group: alum"
  style="small"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: Lab Technician, group: alum"
  style="small"
%}{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/photo.jpg"
  link1="https://nasa.gov/"
  tooltip1="Cool Foundation"

  image2="images/photo.jpg"
  link2="https://nasa.gov/"
  tooltip2="Cool Institute"

  image3="images/photo.jpg"
  link3="https://nasa.gov/"
  tooltip3="Cool Initiative"

  image4="images/photo.jpg"
  link4="https://nasa.gov/"
  tooltip4="Cool Foundation"

  image5="images/photo.jpg"
  link5="https://nasa.gov/"
  tooltip5="Cool Institute"

  image6="images/photo.jpg"
  link6="https://nasa.gov/"
  tooltip6="Cool Initiative"
%}
