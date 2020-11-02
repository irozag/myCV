

## Iro Zagota

{{site.data.personal.email }}

{% for item in site.data.personal.urls %}
 [{{item.link}}](http://{{ item.link }})
{% endfor %}


### Intro
{{site.data.personal.intro }}

### Education 

{% for edu in site.data.education.education %}
        {{edu.year}}  
        {{edu.subject}}
        {{edu.city}} 
{% endfor %}

### Expirenece

{% for exp in site.data.experience.experience %}
   {{exp.year}}<br> 
   *{{exp.employer}}*<br> 
   **{{exp.job}}**<br> 
    {{exp.city}}<br> 
{% endfor %}


Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
