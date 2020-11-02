

## Iro Zagota

{{site.data.personal.email }}

{% for item in site.data.personal.urls %}[{{item.link}}](http://{{ item.link }})<br>{% endfor %}


### Intro
>{{site.data.personal.intro }}

### Expirenece

{% for exp in site.data.experience.experience %}
   {{exp.years}}<br> 
   **{{exp.job}}**<br> 
   {{exp.employer}}<br> 
    *{{exp.city}}*<br> 
{% endfor %}

________________________

### Education

{% for edu in site.data.education.education %}
{{edu.years}}<br>
**{{edu.subject}}**<br>
{{edu.institution}}<br> 
*{{edu.city}}*<br> 
{% endfor %}


### Seminars

{% for sem in site.data.seminars.seminars %}
   {{sem.years}}<br> 
   **{{sem.subject}}**<br> 
   {{sem.IssuingOrganization}}<br> 
{% endfor %}


