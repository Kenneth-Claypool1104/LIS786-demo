---
title: Home
layout: default
---
Godzilla is an enormous, destructive, prehistoric sea monster awakened and empowered by nuclear radiation. With the nuclear bombings of Hiroshima and Nagasaki and the Lucky Dragon 5 incident still fresh in the Japanese
consciousness, Godzilla was conceived as a metaphor for nuclear weapons.

 Others have suggested that Godzilla is a metaphor for the United States, a giant beast woken from its slumber which then takes terrible vengeance on Japan.

 As the film series expanded, some stories took on less serious undertones, portraying Godzilla as an antihero, or a lesser threat who defends humanity. Later films address themes including Japan's forgetfulness over its imperial past, natural disasters and the human condition.

 Source: [Wikipedia](https://en.wikipedia.org/wiki/Godzilla)

 Movies and collections below:

 {% for movies in site.movies %}
  <h2>{{ movies.title }}</h2>
  <p>{{ movies.content }}</p>
  <a href="{{ movies.source }}" target="_blank">Source</a>
{% endfor %}
