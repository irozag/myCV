

## Iro Zagota

{{site.data.personal.email }}

{% for item in site.data.personal.urls %}[{{item.link}}](http://{{ item.link }})<br>{% endfor %}


### Intro
>{{site.data.personal.intro }}

_______________________

### Expirenece

{% for exp in site.data.experience.experience %}
   {{exp.years}}<br> 
   **{{exp.job}}**<br> 
   {{exp.employer}}<br> 
    *{{exp.city}}*<br> 
{% endfor %}

_______________________

### Education

{% for edu in site.data.education.education %}
{{edu.years}}<br>
**{{edu.subject}}**<br>
{{edu.institute}}<br> 
*{{edu.city}}*<br> 
{% endfor %}

_______________________

### Seminars

{% for sem in site.data.seminars.seminars %}
   {{sem.years}}<br> 
   **{{sem.subject}}**<br> 
   {{sem.IssuingOrganization}}<br> 
{% endfor %}

_______________________

### Projects

{% for p in site.data.projects.projects %}
   {{p.years}}<br> 
   {{p.type}}<br> 
   **{{p.client}}**<br> 
   {{p.description}}<br> 
{% endfor %}


