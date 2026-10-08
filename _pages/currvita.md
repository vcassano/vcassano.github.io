---
layout: page
permalink: /currvita/
title: currvita
nav: true
order: 4
eng_pdf: english.pdf
eng_date: 2022-06-01
spa_pdf: spanish.pdf
spa_date: 2023-05-08
---

<p class="post-title">
  {% if page.eng_pdf %}
    in English
    {% if page.eng_date %}
      (last updated {{page.eng_date}})
    {% endif %}
    <a
      href="{{ page.eng_pdf | prepend: 'assets/currvita/' | relative_url}}"
      target="_blank"
      rel="noopener noreferrer"
      class="float-right"
    >
      <i class="fas fa-file-pdf"></i>
    </a>
  {% endif %}
</p>

<p class="post-title">
  {% if page.spa_pdf %}
    en Castellano
    {% if page.spa_date %}
      (last updated {{page.spa_date}})
    {% endif %}
    <a
      href="{{ page.spa_pdf | prepend: 'assets/currvita/' | relative_url}}"
      target="_blank"
      rel="noopener noreferrer"
      class="float-right"
    >
      <i class="fas fa-file-pdf"></i>
    </a>
  {% endif %}
</p>