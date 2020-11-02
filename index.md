

## Iro Zagota

{{site.data.personal.email }}

{{site.data.personal.url }}


{% for item in site.data.personal.urls %}
 [{{item.link}}](http://{{ item.link }})
{% endfor %}


### Intro
>{{site.data.personal.intro }}


### Education

{% for item in site.data.education.education %}
        {{item.year}}  
        __{{item.subject}}__
        {{item.city}} 
{% endfor %}





For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/irozg/cv-iro-zagota/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
