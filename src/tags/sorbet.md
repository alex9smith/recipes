---
layout: layouts/tag.njk
title: Sorbet
date: 2024-01-13
---

# Sorbet

Sorbet needs to be 20-30% sugar to set when churned.
When working with fresh fruit that's usually 4 parts fruit puree to 1 part sugar by weight.

If you're using a flavoured sugar syrup instead of fruit (eg. lavender or juniper) then consider making the syrup with jam sugar.
The added pectin will help make a smoother sorbet.

## Recipes

<ul>
{%- for recipe in collections.sorbet -%}
  <li><a href="{{ recipe.url }}">{{ recipe.data.title }}</a></li>
{%- endfor -%}
</ul>
