{% for link in site.links %}
      
## {{ link.name }}

{{ link.info }}

[Download]({{ link.url_downloads }}) | [View on GitHub]({{ link.url_repo }})
        
{% endfor %}
