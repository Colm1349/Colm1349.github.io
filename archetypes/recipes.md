---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
description: "Короткое описание блюда в одно предложение."
date: {{ .Date }}
emoji: "🍽️"
categories: ["Основные блюда"]
tags: []
servings: 4
time: "30 мин"
difficulty: "Легко"
# image: "/images/имя-файла.jpg"   # фото положите в папку static/images
ingredients:
  - items:
      - "ингредиент 1"
      - "ингредиент 2"
  # - group: "Соус"
  #   items:
  #     - "ингредиент"
---

1. **Первый шаг.** Описание.

2. **Второй шаг.** Описание.
