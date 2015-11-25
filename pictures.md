# Pictures

{% for picture in book.pictures %}
  1. [{{ picture.list_caption }}]({{ picture.backlink }})
{% endfor %}
