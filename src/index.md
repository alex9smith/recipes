---
layout: layouts/base.njk
eleventyImport:
  collections: ["recipe"]
---

# Alex's recipes

## Collections

<ul>
{%- for page in collections.tags -%}
  <li><a href="{{ page.url }}">{{ page.data.title }}</a></li>
{%- endfor -%}
</ul>

## All recipes

<ul>
{%- for recipe in collections.recipe -%}
  <li><a href="{{ recipe.url }}">{{ recipe.data.title }}</a></li>
{%- endfor -%}
</ul>
