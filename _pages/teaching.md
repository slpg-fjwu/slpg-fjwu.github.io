---
layout: page
permalink: /teaching/
title: Teaching
description: List of courses and research areas we explore at SLPG.
nav: true
nav_order: 5
---

<div class="container text-justify">

    <p>Welcome to our Speech & Language Processing Group (SLPG), where the fascinating world of language meets the cutting-edge advancements in Artificial Intelligence. In this dynamic learning environment, we delve into the intricacies of human language and its interaction with technology. Our lab is dedicated to imparting knowledge and skills in a range of NLP subjects, empowering students to decode language patterns, develop language models, and create AI-driven applications that understand, generate, and manipulate text in meaningful ways.</p>

    <h4 style="margin-top: 2rem;">Courses</h4>
    <div class="row" style="margin: 1rem 0 2rem;">
      {% assign courses = site.courses | sort: 'title' %}
      {% for c in courses %}
      <div class="col-12 col-md-4" style="margin-bottom: 1rem;">
        <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem; height: 100%;">
          <i class="fa-solid fa-book-open" style="font-size: 1.4rem; color: #b916b0; margin-bottom: 8px; display: block;"></i>
          <strong style="font-size: 0.95rem;">{{ c.title }}</strong>
          {% if c.description %}<p style="font-size: 0.85rem; color: #666; margin: 6px 0;">{{ c.description }}</p>{% endif %}
          <a href="{{ c.url | relative_url }}" style="color: #b916b0; font-size: 0.85rem; font-weight: 600;">Open course &rarr;</a>
        </div>
      </div>
      {% endfor %}
    </div>

    <h4>List of Research Areas</h4>
    <ul>
        <li>Computational Linguistics</li>
        <li>Data Science</li>
        <li>NLP with Python</li>
        <li>Deep Learning</li>
        <li>Speech and Language Processing</li>
        <li>Machine Translation</li>
        <li>Computer Speech Processing</li>
        <li>Automatic Speech Recognition</li>
        <li>Text to Speech Synthesis</li>
        <li>Operating Systems</li>
        <li>Object Oriented Programming</li>
        <li>Data Structures and Algorithms</li>
        <li>Professional Practices in Computer Science</li>
        <li>Computer Architecture and Assembly Language</li>
        <li>Software Quality Assurance</li>
        <li>Software Design and Architecture</li>
        <li>Introduction to Natural Language Processing</li>
        <li>Text Preprocessing and Tokenization</li>
        <li>Language Modeling and Grammatical Analysis</li>
        <li>Sentiment Analysis and Opinion Mining</li>
        <li>Named Entity Recognition and Information Extraction</li>
        <li>Text Classification and Topic Modeling</li>
        <li>Machine Translation and Language Generation</li>
        <li>Question Answering Systems</li>
    </ul>

    <p>Join us on a journey of exploration, innovation, and collaboration as we delve into the realm of Natural Language Processing. Our lab equips you with the skills to unlock the potential of language-driven AI and contribute to the advancement of this transformative field.</p>

</div>
