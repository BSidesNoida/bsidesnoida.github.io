---
title: Sponsors
layout: default
year: 2025
permalink: /sponsors/
---
# Up your karma: sponsor hacker knowledge aquisition
Getting a community event going (possibly for free) is not easy. We're looking for sponsoring to provide for a nice and central location, multiple tracks, tech (beamers, PA, recording equipment), and ideally food and drinks for attendees. If you are interested to help an event by the security community - please fill-in the [form](#) or send us an e-mail to [info@bsidesnoida.in](mailto:info@bsidesnoida.in). 

Do check the [Sponsorship Deck](https://bsidesnoida.in/sponsor_us/).

PS: BSides is not a vendor marketing event, but you're more
than welcome to participate in any way you feel appropriate.


# Our sponsors

{%- for sponsor in site.data.bs_2024.sponsors %}
[{{ sponsor.name }}]({{ sponsor.url }})

{% if sponsor.image %}
[![{{ sponsor.name }}]({{ sponsor.image }}){:.sponsor}]({{ sponsor.url }})
{% endif %}

{%- endfor %}
