---
layout: default
title: Match Results
banner_text: Match Results
---

## Match Results
<br /><br />


{% for match in site.data.match_results %}
<div>
    <h4>
        <a target="_blank" style="text-decoration: underline;" class="text" href="{{ match.results_url }}">{{ match.month }} {{ match.day }} {{ match.year }}</a>
    </h4>
    <p><b>Set up raffle winner:</b> {{ match.set_up_winner }}</p>
</div>
{% endfor %}