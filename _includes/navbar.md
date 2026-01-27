<div style="width: 100%; text-align: center; background-color: #1e1e1e; border: 5px solid #9ccf4c; padding: 10px; box-sizing: border-box;">

  {% if page.lang == "fr" %}
    <a href="{{ site.baseurl }}/fr/index" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Accueil</a>
    <a href="{{ site.baseurl }}/fr/dimensions" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Dimensions</a>
    <a href="{{ site.baseurl }}/fr/resources" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Ressources</a>
    <a href="{{ site.baseurl }}/fr/crafting" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Craft</a>
    <a href="{{ site.baseurl }}/fr/mobs" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Mobs</a>
    <a href="{{ site.baseurl }}/fr/end-dragon" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Ender Dragon</a>
  {% else %}
    <a href="{{ site.baseurl }}/en/index" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Homepage</a>
    <a href="{{ site.baseurl }}/en/dimensions" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Dimensions</a>
    <a href="{{ site.baseurl }}/en/resources" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Resources</a>
    <a href="{{ site.baseurl }}/en/crafting" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Crafting</a>
    <a href="{{ site.baseurl }}/en/mobs" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Mobs</a>
    <a href="{{ site.baseurl }}/en/end-dragon" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Ender Dragon</a>
  {% endif %}

  <span style="margin: 0 20px; color: #9ccf4c;">|</span>

  {% if page.lang == "fr" %}
    <a href="{{ site.baseurl }}{{ page.url | replace_first: '/fr', '/en' }}" style="color:#9ccf4c; font-size:18px; text-decoration:none;">
      🇬🇧 English
    </a>
  {% else %}
    <a href="{{ site.baseurl }}{{ page.url | replace_first: '/en', '/fr' }}" style="color:#9ccf4c; font-size:18px; text-decoration:none;">
      🇫🇷 Français
    </a>
  {% endif %}

</div>
