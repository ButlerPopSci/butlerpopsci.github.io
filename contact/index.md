---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact
<div style="text-align: center;">
Interested our work and collaborating with our group? Reach out to us at:
</div>
{%
  include button.html
  type="email"
  text="ebonee@unc.edu"
  link="ebonee@unc.edu"
%}
<!-- {%
  include button.html
  type="phone"
  text="(555) 867-5309"
  link="+1-555-867-5309"
%} -->
{%
  include button.html
  type="address"
  tooltip="Visit us at the Gillings School of Global Public Health"
  link="http://goo.gl/maps/9JNrx"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/contact/MCG_building.jpg"
  caption="McGavern-Greenberg Hall, Gillings School of Global Public Health"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/contact/MCG_cherryblossoms.jpg"
  caption="McGavern-Greenberg Hall, Epidemiology Department"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Department of Epidemiology <br>
McGavran-Greenberg Hall, Suite 2102-B
University of North Carolina at Chapel Hill
Chapel Hill, NC 27599-7435
{% endcapture %}

{% capture col2 %}

{% endcapture %}

{% capture col3 %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
