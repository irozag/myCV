

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


Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
