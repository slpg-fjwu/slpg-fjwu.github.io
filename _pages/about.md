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
selected_papers: false
social: true
---

<div style="background: linear-gradient(135deg, #eef2ff, #f5f0ff); border-radius: 16px; padding: 2rem; margin-bottom: 2rem;">
  <p style="display: inline-block; background: #e0e7ff; color: #4338ca; font-size: 0.8rem; font-weight: 600; padding: 4px 12px; border-radius: 20px; margin-bottom: 12px;">WELCOME TO SLPG</p>
  <h1 style="font-size: 2.2rem; font-weight: 700; margin: 0 0 12px; line-height: 1.2;">
    Advancing AI Research in Speech, Language and <span style="color: #4338ca;">Beyond</span>
  </h1>
  <p style="font-size: 1rem; color: #555; max-width: 600px; margin-bottom: 20px;">
    We conduct cutting-edge research in Natural Language Processing, Speech Technologies, and Large Language Models to solve real-world challenges and empower society.
  </p>
  <a href="/publications/" style="display: inline-block; background: #4338ca; color: white; padding: 10px 20px; border-radius: 8px; font-weight: 600; font-size: 0.9rem; margin-right: 10px; text-decoration: none;">Explore Research →</a>
  <a href="/publications/" style="display: inline-block; background: white; color: #4338ca; border: 1px solid #4338ca; padding: 10px 20px; border-radius: 8px; font-weight: 600; font-size: 0.9rem; text-decoration: none;">View Publications</a>
</div>

Rawalpindi, Pakistan.

Welcome to the Speech and Language Processing Group, Islamabad. SLPG was founded at FJWU and now is a joint collaboration with International Islamic University, islamabad. We develop computational models for the understanding or generation of natural language.

More details about our project can be found [here](https://slpg-fjwu.github.io/graduate_research/). Also check out the our latest publications and participation in [WMT](http://www2.statmt.org/wmt23/) workshops. Our models are found [here](https://github.com/slpg-fjwu).

<h4>Collaborating Institutions</h4>
<div class="marquee-wrap" style="overflow: hidden; position: relative; margin: 1rem 0 2rem; -webkit-mask-image: linear-gradient(90deg, transparent, #000 10%, #000 90%, transparent); mask-image: linear-gradient(90deg, transparent, #000 10%, #000 90%, transparent);">
  <div class="marquee-track" style="display: flex; width: max-content; animation: scrollLeft 45s linear infinite;">
    <div class="marquee-group" style="display: flex; gap: 1rem; padding-right: 1rem;">
      <span class="inst-pill" style="background:#e1f5ee;">International Islamic University, Islamabad</span>
      <span class="inst-pill" style="background:#faece7;">Fatima Jinnah Women University</span>
      <span class="inst-pill" style="background:#eaf3de;">NUST</span>
      <span class="inst-pill" style="background:#fbeaf0;">FAST-NUCES, Lahore</span>
      <span class="inst-pill" style="background:#eeedfe;">LISN-CNRS, Group TLP, Université Paris-Saclay, France</span>
      <span class="inst-pill" style="background:#e6f1fb;">LISN-CNRS, Group ILES, Université Paris-Saclay, France</span>
      <span class="inst-pill" style="background:#faeeda;">LIUM, Université du Maine, France</span>
      <span class="inst-pill" style="background:#f1eee4;">Université Paris Diderot (Paris 7), France</span>
      <span class="inst-pill" style="background:#e1f5ee;">Prince Sultan University, Saudi Arabia</span>
    </div>
    <div class="marquee-group" style="display: flex; gap: 1rem; padding-right: 1rem;" aria-hidden="true">
      <span class="inst-pill" style="background:#e1f5ee;">International Islamic University, Islamabad</span>
      <span class="inst-pill" style="background:#faece7;">Fatima Jinnah Women University</span>
      <span class="inst-pill" style="background:#eaf3de;">NUST</span>
      <span class="inst-pill" style="background:#fbeaf0;">FAST-NUCES, Lahore</span>
      <span class="inst-pill" style="background:#eeedfe;">LISN-CNRS, Group TLP, Université Paris-Saclay, France</span>
      <span class="inst-pill" style="background:#e6f1fb;">LISN-CNRS, Group ILES, Université Paris-Saclay, France</span>
      <span class="inst-pill" style="background:#faeeda;">LIUM, Université du Maine, France</span>
      <span class="inst-pill" style="background:#f1eee4;">Université Paris Diderot (Paris 7), France</span>
      <span class="inst-pill" style="background:#e1f5ee;">Prince Sultan University, Saudi Arabia</span>
    </div>
  </div>
</div>

<style>
.inst-pill {
  display: inline-block;
  white-space: nowrap;
  padding: 0.5rem 1rem;
  border-radius: 12px;
  font-size: 0.85rem;
  font-weight: 600;
}
@keyframes scrollLeft {
  from { transform: translateX(0); }
  to { transform: translateX(-50%); }
}
</style>

{% capture pubs_html %}{% bibliography --file papers %}{% endcapture %}
{% assign pub_count = pubs_html | split: '<li' | size | minus: 1 %}

<div class="row text-center" style="margin: 2rem 0;">
  <div class="col">
    <h2 class="counter" data-target="{{ pub_count }}">0</h2>
    <p style="color: #888; font-size: 0.9rem;">Publications</p>
  </div>
  <div class="col">
    <h2 class="counter" data-target="14">0</h2>
    <p style="color: #888; font-size: 0.9rem;">Models</p>
  </div>
  <div class="col">
    <h2 class="counter" data-target="6">0</h2>
    <p style="color: #888; font-size: 0.9rem;">Datasets</p>
  </div>
  <div class="col">
    <h2 class="counter" data-target="3">0</h2>
    <p style="color: #888; font-size: 0.9rem;">Awards</p>
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
      <strong>Natural Language Processing for Educational Applications</strong>
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
    <div class="col-6 col-md-3" style="margin-bottom: 1rem;">
    <div style="background: #eeedfe; border-radius: 12px; padding: 1rem; height: 100%;">
      <strong>Argument Mining</strong>
    </div>
  </div>
  <div class="col-6 col-md-3" style="margin-bottom: 1rem;">
    <div style="background: #e6f1fb; border-radius: 12px; padding: 1rem; height: 100%;">
      <strong>RAG(Retrieval-Augmented Generation)</strong>
    </div>
  </div>
  <div class="col-6 col-md-3" style="margin-bottom: 1rem;">
    <div style="background: #faeeda; border-radius: 12px; padding: 1rem; height: 100%;">
      <strong>Large Language Models (LLMs)</strong>
    </div>
  </div>
  <div class="col-6 col-md-3" style="margin-bottom: 1rem;">
    <div style="background: #eaf3de; border-radius: 12px; padding: 1rem; height: 100%;">
      <strong>Agentic AI</strong>
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
<h4>Datasets</h4>
<div class="row" style="margin: 1rem 0 2rem;">
  <div class="col-6 col-md-4" style="margin-bottom: 1rem;">
    <div style="background: #e1f5ee; border-radius: 12px; padding: 1rem; height: 100%;">
      <strong>SLPG Humor Generation</strong>
      <p style="font-size: 0.85rem; color: #666; margin: 6px 0;">12.1k rows — dataset for humor and linguistic creativity tasks.</p>
      <a href="https://huggingface.co/datasets/SLPG/slpg_humor_generation" target="_blank" style="font-size: 0.85rem;">View on HuggingFace →</a>
    </div>
  </div>
  <div class="col-6 col-md-4" style="margin-bottom: 1rem;">
    <div style="background: #faece7; border-radius: 12px; padding: 1rem; height: 100%;">
      <strong>UNGA</strong>
      <p style="font-size: 0.85rem; color: #666; margin: 6px 0;">7.16k rows — UN General Assembly debate data.</p>
      <a href="https://huggingface.co/datasets/SLPG/UNGA" target="_blank" style="font-size: 0.85rem;">View on HuggingFace →</a>
    </div>
  </div>
  <div class="col-6 col-md-4" style="margin-bottom: 1rem;">
    <div style="background: #eaf3de; border-radius: 12px; padding: 1rem; height: 100%;">
      <strong>Biomedical EN-FR Corpus</strong>
      <p style="font-size: 0.85rem; color: #666; margin: 6px 0;">Parallel corpus for English-French biomedical translation.</p>
      <a href="https://huggingface.co/datasets/SLPG/Biomedical_EN_FR_Corpus" target="_blank" style="font-size: 0.85rem;">View on HuggingFace →</a>
    </div>
  </div>
  <div class="col-6 col-md-4" style="margin-bottom: 1rem;">
    <div style="background: #faeeda; border-radius: 12px; padding: 1rem; height: 100%;">
      <strong>All Datasets & Models</strong>
      <p style="font-size: 0.85rem; color: #666; margin: 6px 0;">Explore our complete collection on HuggingFace.</p>
      <a href="https://huggingface.co/SLPG" target="_blank" style="font-size: 0.85rem;">View HuggingFace profile →</a>
    </div>
  </div>
</div>
<div id="recent-pubs-source" style="display: none;">
  {% bibliography --file papers %}
</div>

<div id="recent-publications" style="margin: 1.5rem 0;">
  <p style="font-size: 0.85rem; color: #666; font-weight: 600; margin-bottom: 10px;">📄 RECENT PUBLICATIONS</p>
</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const source = document.querySelectorAll("#recent-pubs-source li");
  const container = document.getElementById("recent-publications");

  const topThree = Array.from(source).slice(0, 3);

  topThree.forEach(function (item) {
    const card = document.createElement("div");
    card.style.cssText = "background: #f1eee4; border-radius: 12px; padding: 1rem 1.25rem; margin-bottom: 10px; border-left: 4px solid #7F77DD;";
    card.innerHTML = item.innerHTML;
    container.appendChild(card);
  });
});
</script>

