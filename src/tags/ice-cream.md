---
layout: layouts/tag.njk
title: Ice cream
date: 2024-01-12
---

# Ice cream recipes

For ice cream to set properly when it's churned the mixture needs to be 10-15% fat and 10-15% sugar.

The higher the sugar content, the softer the resulting ice cream.
This is because the dissolved sugar lowers the freezing point of the mixture.

## Dairy free

It's harder to get the required fat content when making a dairy free ice cream.
Coconut milk is a popular option for a base but it's got a lot of flavour that can't always be hidden.

Instead you can use a combination of vegan butter (unsalted), cream and milk to get the correct volume and fat ratio.

## Recipes

<ul>
{%- for recipe in collections.ice_cream -%}
  <li><a href="{{ recipe.url }}">{{ recipe.data.title }}</a></li>
{%- endfor -%}
</ul>
