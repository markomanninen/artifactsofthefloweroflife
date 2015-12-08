# Credits

I need to credit all picture copyright holders and work made by numerous artists and authors. Without their willingness to share their work it would be impossible to present the continuity of the FOL symbol by its various appearances in any satisfactory way.

Most of the pictures have been published with Creative Commons license<!-- cite author="wikipedia.org" title="Creative Commons license" date="" location="" type="website" href="http://en.wikipedia.org/wiki/Creative_Commons_license" -->. It was straightforward to use those images in this book. I have published all my own photos and illustrations with the same license. I believe it is the way to keep creative work and research hassle free and enjoyable for everyone.


### Pictures

<ul class="pictures">
{% for picture in book.pictures %}<li>{{ picture }}</li>{% endfor %}
</ul>

{% include 'footnotes.md' %}
