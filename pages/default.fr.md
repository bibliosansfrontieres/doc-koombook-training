![THE ANTONOMUS ULTRA-PORTABLE DIGITAL LIBRARY](../logo.png)

Pour faciliter la navigation dans la documentation, n'hésitez pas à utiliser les touches  **gauche** et **droite** pour passer d'une page à une autre et **haut** et **bas** pour faire défiler les pages.

### Auteur

{% for author in book.authors %}
  {{ author.name }} 
{% endfor %}

Dernière modification : {{file.mtime}}