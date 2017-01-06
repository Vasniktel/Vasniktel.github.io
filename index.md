{% for link in site.links %}
      
        <h2>{{ link.name }}</h2>
        <iframe src="{{ link.url_info }}" frameborder="0" allowfullscreen>hello</iframe>
        <br />
        <a href="{{ link.url_downloads }}" class="btn btn-success">
          <span class="glyphicon glyphicon-floppy-save"></span> Download
        </a> 
        <a href="{{ link.url_repo }}" class="btn btn-default btn-github">View on GitHub</a>
        
{% endfor %}
