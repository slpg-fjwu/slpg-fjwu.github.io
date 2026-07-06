---
layout: about
title: About 
permalink: /
subtitle: <a href='#'></a>

profile:
  align: right
  image: 
  image_circular: false
  address: Welcome to our Speech and Language Processing Group!

news: true
latest_posts: true
selected_papers: true
social: true
---
Rawalpindi, Pakistan.

Welcome to the Speech and Language Processing Group, Islamabad. SLPG was founded at FJWU and now is a joint collaboration with International Islamic University, islamabad. We develop computational models for the understanding or generation of natural language. Some of our current areas of interest are:

* Universal natural language processing and transfer learning
* Natural language processing for educational applications
* Context-aware machine translation
* Low-resource machine translation

More details about our project can be found [here](https://slpg-fjwu.github.io/graduate_research/). Also check out the our latest publications and participation in [WMT](http://www2.statmt.org/wmt23/) workshops. Our models are found [here](https://github.com/slpg-fjwu).

{% capture pubs_html %}{% bibliography --file papers %}{% endcapture %}
{% assign pub_count = pubs_html | split: '<li' | size | minus: 1 %}

<div class="row text-center" style="margin: 2rem 0;">
  <div class="col">
    <h2 class="counter" data-target="{{ pub_count }}">0</h2>
    <p style="color: #888; font-size: 0.9rem;">Publications</p>
  </div>
  <div class="col">
    <h2 class="counter" data-target="3">0</h2>
    <p style="color: #888; font-size: 0.9rem;">Awards</p>
  </div>
  <div class="col">
    <h2 class="counter" data-target="10">0</h2>
    <p style="color: #888; font-size: 0.9rem;">Projects</p>
  </div>
  <div class="col">
    <h2 class="counter" data-target="2">0</h2>
    <p style="color: #888; font-size: 0.9rem;">Institutions</p>
  </div>
</div>

<h4>Research Areas</h4>
<div class="row" style="margin: 1rem 0 2rem;">
  <div class="col-6 col-md-3" style="margin-bottom: 1rem;">
    <div style="background: #f1eee4; border-radius: 12px; padding: 1rem; height: 100%;">
      <strong>Universal NLP & Transfer Learning</strong>
    </div>
  </div>
  <div class="col-6 col-md-3" style="margin-bottom: 1rem;">
    <div style="background: #e1f5ee; border-radius: 12px; padding: 1rem; height: 100%;">
      <strong>NLP for Education</strong>
    </div>
  </div>
  <div class="col-6 col-md-3" style="margin-bottom: 1rem;">
    <div style="background: #faece7; border-radius: 12px; padding: 1rem; height: 100%;">
      <strong>Context-aware Machine Translation</strong>
    </div>
  </div>
  <div class="col-6 col-md-3" style="margin-bottom: 1rem;">
    <div style="background: #fbeaf0; border-radius: 12px; padding: 1rem; height: 100%;">
      <strong>Low-resource Machine Translation</strong>
    </div>
  </div>
</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const counters = document.querySelectorAll(".counter");
  const speed = 100;

  const animateCounter = (counter) => {
    const target = +counter.getAttribute("data-target");
    const increment = target / speed;
    let current = 0;

    const updateCount = () => {
      current += increment;
      if (current < target) {
        counter.innerText = Math.ceil(current);
        requestAnimationFrame(updateCount);
      } else {
        counter.innerText = target;
      }
    };
    updateCount();
  };

  const observer = new IntersectionObserver((entries) => {
    entries.forEach((entry) => {
      if (entry.isIntersecting) {
        animateCounter(entry.target);
        observer.unobserve(entry.target);
      }
    });
  }, { threshold: 0.5 });

  counters.forEach((counter) => observer.observe(counter));
});
</script>
