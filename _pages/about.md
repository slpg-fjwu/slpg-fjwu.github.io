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
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem 0.5rem;">
      <i class="fa-solid fa-book" style="font-size: 1.4rem; color: #4338ca; margin-bottom: 8px; display: block;"></i>
      <h2 class="counter" data-target="{{ pub_count }}" style="margin: 0; font-size: 1.6rem;">0</h2>
      <p style="color: #888; font-size: 0.85rem; margin: 4px 0 0;">Publications</p>
    </div>
  </div>
  <div class="col">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem 0.5rem;">
      <i class="fa-solid fa-cube" style="font-size: 1.4rem; color: #4338ca; margin-bottom: 8px; display: block;"></i>
      <h2 class="counter" data-target="14" style="margin: 0; font-size: 1.6rem;">0</h2>
      <p style="color: #888; font-size: 0.85rem; margin: 4px 0 0;">Models</p>
    </div>
  </div>
  <div class="col">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem 0.5rem;">
      <i class="fa-solid fa-database" style="font-size: 1.4rem; color: #4338ca; margin-bottom: 8px; display: block;"></i>
      <h2 class="counter" data-target="6" style="margin: 0; font-size: 1.6rem;">0</h2>
      <p style="color: #888; font-size: 0.85rem; margin: 4px 0 0;">Datasets</p>
    </div>
  </div>
  <div class="col">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem 0.5rem;">
      <i class="fa-solid fa-trophy" style="font-size: 1.4rem; color: #4338ca; margin-bottom: 8px; display: block;"></i>
      <h2 class="counter" data-target="3" style="margin: 0; font-size: 1.6rem;">0</h2>
      <p style="color: #888; font-size: 0.85rem; margin: 4px 0 0;">Awards</p>
    </div>
  </div>
</div>

<h4 style="text-align: center; margin-bottom: 1.5rem;">Our Research Areas</h4>
<div class="row" style="margin: 1rem 0 2rem;">
  <div class="col-6 col-md-3" style="margin-bottom: 1rem;">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem; height: 100%; text-align: center;">
      <i class="fa-solid fa-brain" style="font-size: 1.8rem; color: #4338ca; margin-bottom: 10px; display: block;"></i>
      <strong style="font-size: 0.9rem;">Large Language Models</strong>
    </div>
  </div>
  <div class="col-6 col-md-3" style="margin-bottom: 1rem;">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem; height: 100%; text-align: center;">
      <i class="fa-solid fa-wave-square" style="font-size: 1.8rem; color: #4338ca; margin-bottom: 10px; display: block;"></i>
      <strong style="font-size: 0.9rem;">Speech Recognition</strong>
    </div>
  </div>
  <div class="col-6 col-md-3" style="margin-bottom: 1rem;">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem; height: 100%; text-align: center;">
      <i class="fa-solid fa-language" style="font-size: 1.8rem; color: #4338ca; margin-bottom: 10px; display: block;"></i>
      <strong style="font-size: 0.9rem;">Machine Translation</strong>
    </div>
  </div>
  <div class="col-6 col-md-3" style="margin-bottom: 1rem;">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem; height: 100%; text-align: center;">
      <i class="fa-solid fa-comments" style="font-size: 1.8rem; color: #4338ca; margin-bottom: 10px; display: block;"></i>
      <strong style="font-size: 0.9rem;">Natural Language Processing</strong>
    </div>
  </div>
  <div class="col-6 col-md-3" style="margin-bottom: 1rem;">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem; height: 100%; text-align: center;">
      <i class="fa-solid fa-microphone" style="font-size: 1.8rem; color: #4338ca; margin-bottom: 10px; display: block;"></i>
      <strong style="font-size: 0.9rem;">Speech Synthesis</strong>
    </div>
  </div>
  <div class="col-6 col-md-3" style="margin-bottom: 1rem;">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem; height: 100%; text-align: center;">
      <i class="fa-solid fa-sitemap" style="font-size: 1.8rem; color: #4338ca; margin-bottom: 10px; display: block;"></i>
      <strong style="font-size: 0.9rem;">Argument Mining</strong>
    </div>
  </div>
  <div class="col-6 col-md-3" style="margin-bottom: 1rem;">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem; height: 100%; text-align: center;">
      <i class="fa-solid fa-magnifying-glass" style="font-size: 1.8rem; color: #4338ca; margin-bottom: 10px; display: block;"></i>
      <strong style="font-size: 0.9rem;">RAG</strong>
    </div>
  </div>
  <div class="col-6 col-md-3" style="margin-bottom: 1rem;">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem; height: 100%; text-align: center;">
      <i class="fa-solid fa-robot" style="font-size: 1.8rem; color: #4338ca; margin-bottom: 10px; display: block;"></i>
      <strong style="font-size: 0.9rem;">Agentic AI</strong>
    </div>
  </div>
</div>

<h4>Datasets</h4>
<div class="row" style="margin: 1rem 0 2rem;">
  <div class="col-6 col-md-4" style="margin-bottom: 1rem;">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem; height: 100%;">
      <i class="fa-solid fa-database" style="font-size: 1.2rem; color: #4338ca; margin-bottom: 8px; display: block;"></i>
      <strong style="font-size: 0.9rem;">SLPG Humor Generation</strong>
      <p style="font-size: 0.85rem; color: #666; margin: 6px 0;">12.1k rows — dataset for humor and linguistic creativity tasks.</p>
      <a href="https://huggingface.co/datasets/SLPG/slpg_humor_generation" target="_blank" style="font-size: 0.85rem; color: #4338ca; font-weight: 600;">View on HuggingFace →</a>
    </div>
  </div>
  <div class="col-6 col-md-4" style="margin-bottom: 1rem;">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem; height: 100%;">
      <i class="fa-solid fa-database" style="font-size: 1.2rem; color: #4338ca; margin-bottom: 8px; display: block;"></i>
      <strong style="font-size: 0.9rem;">UNGA</strong>
      <p style="font-size: 0.85rem; color: #666; margin: 6px 0;">7.16k rows — UN General Assembly debate data.</p>
      <a href="https://huggingface.co/datasets/SLPG/UNGA" target="_blank" style="font-size: 0.85rem; color: #4338ca; font-weight: 600;">View on HuggingFace →</a>
    </div>
  </div>
  <div class="col-6 col-md-4" style="margin-bottom: 1rem;">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem; height: 100%;">
      <i class="fa-solid fa-database" style="font-size: 1.2rem; color: #4338ca; margin-bottom: 8px; display: block;"></i>
      <strong style="font-size: 0.9rem;">Biomedical EN-FR Corpus</strong>
      <p style="font-size: 0.85rem; color: #666; margin: 6px 0;">Parallel corpus for English-French biomedical translation.</p>
      <a href="https://huggingface.co/datasets/SLPG/Biomedical_EN_FR_Corpus" target="_blank" style="font-size: 0.85rem; color: #4338ca; font-weight: 600;">View on HuggingFace →</a>
    </div>
  </div>
  <div class="col-6 col-md-4" style="margin-bottom: 1rem;">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem; height: 100%;">
      <i class="fa-solid fa-folder-open" style="font-size: 1.2rem; color: #4338ca; margin-bottom: 8px; display: block;"></i>
      <strong style="font-size: 0.9rem;">All Datasets & Models</strong>
      <p style="font-size: 0.85rem; color: #666; margin: 6px 0;">Explore our complete collection on HuggingFace.</p>
      <a href="https://huggingface.co/SLPG" target="_blank" style="font-size: 0.85rem; color: #4338ca; font-weight: 600;">View HuggingFace profile →</a>
    </div>
  </div>
</div>

<h4 style="margin-bottom: 1.5rem;">Latest Publications</h4>
<div class="row">
  <div class="col-md-4" style="margin-bottom: 1rem;">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem; height: 100%;">
      <span style="display: inline-block; background: #e0e7ff; color: #4338ca; font-size: 0.75rem; font-weight: 600; padding: 3px 10px; border-radius: 20px; margin-bottom: 10px;">Information 2026</span>
      <p style="font-weight: 600; font-size: 0.95rem; margin: 0 0 8px;">Temporal Robustness of Large Language Models for Thematic Classification of UN General Assembly Debates</p>
      <p style="font-size: 0.8rem; color: #666; margin: 0 0 10px;">Fatima, M., Rauf, S. A., Saadia, I. N., Ghulam, A. M. M., Imran, M.</p>
      <a href="https://www.mdpi.com/2078-2489/17/6/589" target="_blank" style="font-size: 0.85rem; font-weight: 600; color: #4338ca;"><i class="fa-solid fa-arrow-up-right-from-square" style="font-size: 0.7rem;"></i> Read Paper</a>
    </div>
  </div>
  <div class="col-md-4" style="margin-bottom: 1rem;">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem; height: 100%;">
      <span style="display: inline-block; background: #e0e7ff; color: #4338ca; font-size: 0.75rem; font-weight: 600; padding: 3px 10px; border-radius: 20px; margin-bottom: 10px;">Information 2026</span>
      <p style="font-weight: 600; font-size: 0.95rem; margin: 0 0 8px;">A Comparative Framework for Political Violence Event Classification Using Machine Learning, Deep Learning, and Zero-Shot Language Models</p>
      <p style="font-size: 0.8rem; color: #666; margin: 0 0 10px;">Beenish, U., Ishtiaq Nauman, S., Rauf, S. A., Mumtaz, F., Abbas Malik, M. G., Imran, M., Iqbal, M.</p>
      <a href="https://www.mdpi.com/2078-2489/17/7/621" target="_blank" style="font-size: 0.85rem; font-weight: 600; color: #4338ca;"><i class="fa-solid fa-arrow-up-right-from-square" style="font-size: 0.7rem;"></i> Read Paper</a>
    </div>
  </div>
  <div class="col-md-4" style="margin-bottom: 1rem;">
    <div style="background: var(--global-card-bg-color, #fff); border: 1px solid #e5e7eb; border-radius: 12px; padding: 1.25rem; height: 100%;">
      <span style="display: inline-block; background: #e0e7ff; color: #4338ca; font-size: 0.75rem; font-weight: 600; padding: 3px 10px; border-radius: 20px; margin-bottom: 10px;">PLOS ONE 2026</span>
      <p style="font-weight: 600; font-size: 0.95rem; margin: 0 0 8px;">Automatic Sentence Simplification System for Arabic Script Punjabi</p>
      <p style="font-size: 0.8rem; color: #666; margin: 0 0 10px;">Shehzad, T., Rauf, S. A., Nazeer, S., Daud, A., Dawood, H.</p>
      <a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0344915" target="_blank" style="font-size: 0.85rem; font-weight: 600; color: #4338ca;"><i class="fa-solid fa-arrow-up-right-from-square" style="font-size: 0.7rem;"></i> Read Paper</a>
    </div>
  </div>
</div>
<p style="text-align: right; margin-top: 0.5rem;"><a href="/publications/" style="font-size: 0.9rem; font-weight: 600; color: #4338ca;">View All Publications →</a></p>

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
