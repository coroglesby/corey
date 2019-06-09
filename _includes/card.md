<div class="card mb-3">
{% if include.img %}<img class="card-img-top" src="{{ include.img | prepend: '/images/' | absolute_url }}" alt="{{ include.alt | default: 'Card image' }}">{% endif %}
{% if include.header %}<h5 class="card-header" style="text-shadow: 2px 2px rgb(0, 0, 0); background-color: #40e0d0;">{{ include.header }}</h5>{% endif %}
<div class="card-body" style="background-color: rgb(154, 226, 190);">
{% if include.title %}<h5 class="card-title">{{ include.title }}</h5>{% endif %}
<div class="card-text" markdown="1">

{{ include.text }}

</div>
</div>
</div>