---
_schema: default
title: Astro Recipe Book
description: Alysha's favourite recipes, all in one place.
pageSections:
  - _component: page-sections/layouts/recipe-carousel
    heading: Recipes
    slides:
      - _component: page-sections/layouts/recipe-carousel/recipe-carousel-item
        recipes:
          - recipe: /src/content/recipes/biscoff-gelato.md
            cardStyle: large
          - recipe: /src/content/recipes/biscoff-gelato.md
            cardStyle: small
    colorScheme: inherit
    backgroundColor: base
---
