---
title: Staff
---
# *Hello* 👋 from our team!

These individuals worked behind the scenes to make SciTinyML a reality. Feel free to [**reach out**](mailto:edu@tinyml.org) to us with any questions!

{% if site.data.team.local_organizers.size > 0 %}
# Lead Organizer{% if site.data.team.local_organizers.size > 1 %}s{% endif %}

{% for person in site.data.team.local_organizers %}
{% include team_person person = person %}
{% endfor %}

{% endif %}

{% if site.data.team.regional_leads.size > 0 %}
# Regional Lead Organizer{% if site.data.team.regional_leads.size > 1 %}s{% endif %}

{% for person in site.data.team.regional_leads %}
{% include team_person person = person %}
{% endfor %}

{% endif %}

{% if site.data.team.other.size > 0 %}
# Supporting Organizer{% if site.data.team.other.size > 1 %}s{% endif %}

{% for person in site.data.team.other %}
{% include team_person person = person %}
{% endfor %}

{% endif %}