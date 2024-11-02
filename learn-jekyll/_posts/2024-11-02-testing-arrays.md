---
birds:
  - name: Tui
    description: Striking songbird
    image: https://dam-cdn.cloudcannon.com/community/images/tui.jpg
    image_alt: Striking songbird in a tree.
  - name: Kea
    description: Alpine parrot
    image: https://dam-cdn.cloudcannon.com/community/images/kea.jpg
    image_alt: Parrot sitting in an alpine tree.
  - name: Kaka
    description: Loud, social forest parrot
    image: https://dam-cdn.cloudcannon.com/community/images/kaka.jpg
    image_alt: Kaka parrot in a thick forest.
  - name: Pukeko
    description: Colourful swamp hen
    image: https://dam-cdn.cloudcannon.com/community/images/pukeko.jpg
    image_alt: Pukeko bird rustling in a swamp.
  - name: Piwakawaka
    description: Small and energetic
    image: https://dam-cdn.cloudcannon.com/community/images/piwakawaka.jpg
    image_alt: Piwakaka with its tail feathers fanned sitting in a tree.
  - name: Kereru
    description: Mute yet loud pigeon
    image_alt: Kereru sitting in a tree eating berries.
    image: https://dam-cdn.cloudcannon.com/community/images/kereru.jpg
---
<div class="image-grid">
{% for bird in page.birds %}
  <div class="item">
    <img src="{{ bird.image }}" alt="{{ bird.image_alt }}">
    <p>Bird name: {{ bird.name }}</p>
    <p>Description: {{ bird.description }}</p>
  </div>
{% endfor %}
</div>