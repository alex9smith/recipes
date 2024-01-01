---
layout: layouts/base.njk
eleventyImport:
  collections: ["recipe"]
---

# Alex's recipes

All recipes:

<ul>
{%- for recipe in collections.recipe -%}
  <li><a href="{{ recipe.url }}">{{ recipe.data.title }}</a></li>
{%- endfor -%}
</ul>
