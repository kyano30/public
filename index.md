# TEC-BA420T

最新のリリースはこちら：

{% for file in site.static_files %}
  {% if file.path contains 'TEC-BA420T/' %}
- [{{ file.name }}]({{ file.path }})
  {% endif %}
{% endfor %}
