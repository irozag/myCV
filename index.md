

## Iro Zagota 

[{{site.data.personal.page}}](http://{{ site.data.personal.page }}) -- {{site.data.personal.email }} <br/>
--  *for portfolio view request a private presentation*

{% for item in site.data.personal.urls %}[{{item.link}}](http://{{ item.link }})<br>{% endfor %}


### Digital (UX/UI) Product Deisgner
>{{site.data.personal.intro }}

_______________________

### Expirenece

{% for exp in site.data.experience.experience %}
   {{exp.years}}<br> 
   **{{exp.job}}**<br> 
   [{{exp.employer}}](http://{{ exp.link }})<br> 
    *{{exp.city}}*<br> 
{% endfor %}

_______________________

### Education

{% for edu in site.data.education.education %}
{{edu.years}}<br>
**{{edu.subject}}**<br>
{{edu.institute}}<br> 
*{{edu.city}}*<br> 
**Courses:** {{edu.courses}}
{% endfor %}

_______________________

### Seminars

{% for sem in site.data.seminars.seminars %}
   {{sem.years}}<br> 
   **{{sem.subject}}**<br> 
   {{sem.IssuingOrganization}}<br> 
{% endfor %}

_______________________

### Additional Freelance Projects

{% for p in site.data.projects.projects %}
   {{p.years}}<br> 
    **{{p.project}}** - {{p.client}}<br> 
   {{p.type}}<br> 
{% endfor %}


