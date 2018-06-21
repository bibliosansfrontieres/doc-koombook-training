#KoomBookteachingguide


![](../logo.png)

To navigate in the document, use the left and right arrows to turn the page and the up and down arrows to scroll. 

### Authors

{% for author in book.authors %}
  {{ author.name }} 
{% endfor %}

Dernière modification : {{file.mtime}}