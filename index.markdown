---
layout: default
---
{% for election in site.data.simplified_election_data %}}

{% assign winner = site.data.parties | find: "pm"，election.pm %}

{% assign time = site.data.events | find："year"，election.year %}

{{ election.pm }}, who belonged to {{ winner.party }}, won the elections in {{ election.year }}, which is also the year in which {{ time.events }}


{% endfor %}

