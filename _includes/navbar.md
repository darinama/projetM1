<div style="width: 100%; text-align: center; background-color: #1e1e1e; border: 5px solid #9ccf4c; padding: 10px; box-sizing: border-box;">

  <!-- Navigation principale -->
  {% if page.lang == "fr" %}
    <a href="/fr/index" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Accueil</a>
    <a href="/fr/dimensions" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Dimensions</a>
    <a href="/fr/resources" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Ressources</a>
    <a href="/fr/crafting" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Craft</a>
    <a href="/fr/mobs" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Mobs</a>
    <a href="/fr/end-dragon" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Ender Dragon</a>
  {% else %}
    <a href="/en/index" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Homepage</a>
    <a href="/en/dimensions" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Dimensions</a>
    <a href="/en/resources" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Resources</a>
    <a href="/en/crafting" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Crafting</a>
    <a href="/en/mobs" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Mobs</a>
    <a href="/en/end-dragon" style="color:#9ccf4c; margin:0 15px; font-size:22px; text-decoration:none;">Ender Dragon</a>
  {% endif %}

  <!-- Séparateur -->
  <span style="margin: 0 20px; color: #9ccf4c;">|</span>

  <!-- Switch de langue (page courante) -->
  {% if page.lang == "fr" %}
    <a href="{{ page.url | replace_first: '/fr', '/en' }}" style="color:#ffffff; font-size:18px; text-decoration:none;">
      🇬🇧 English
    </a>
  {% else %}
    <a href="{{ page.url | replace_first: '/en', '/fr' }}" style="color:#ffffff; font-size:18px; text-decoration:none;">
      🇫🇷 Français
    </a>
  {% endif %}

</div>
