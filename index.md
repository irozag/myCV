

## Iro Zagota

{{site.data.personal.email }}

{{site.data.personal.url }}


{% for item in site.data.personal.urls %}
 [{{item.link}}](http://{{ item.link }})
{% endfor %}


### Intro
>{{site.data.personal.intro }}

### Education 
```
{% for edu in site.data.education.education %}
        {{edu.year}}  
        <b>{{edu.subject}}</b>
        {{edu.city}} 
{% endfor %}
```

### Expirenece

{% for exp in site.data.experience.experience %}
        {{exp.year}}  
        *{{exp.employer}}*
        **{{exp.job}}**
        {{exp.city}} 
{% endfor %}

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
