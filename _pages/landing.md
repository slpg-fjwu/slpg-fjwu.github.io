---
layout: page
title: Welcome
permalink: /
---

<div style="min-height: 80vh; display: flex; flex-direction: column; align-items: center; justify-content: center; text-align: center; padding: 2rem 1rem;">

  <div class="slpg-hero" style="position: relative; width: 320px; height: 260px; display: flex; align-items: center; justify-content: center;">
    <div style="width: 110px; height: 110px; border-radius: 50%; background: #4338ca; display: flex; align-items: center; justify-content: center; animation: slpgSpin 18s linear infinite; z-index: 2;">
      <i class="fa-solid fa-earth-asia" style="font-size: 2.6rem; color: #fff;"></i>
    </div>

    <div class="slpg-bubble" style="position: absolute; top: 2%; left: 0%; background: #4338ca; color: #fff; padding: 7px 14px; border-radius: 20px; font-weight: 600; font-size: 0.85rem; animation: slpgFloat 4.5s ease-in-out infinite;">اردو</div>
    <div class="slpg-bubble" style="position: absolute; top: 0%; right: 0%; background: #1D9E75; color: #fff; padding: 7px 14px; border-radius: 20px; font-weight: 600; font-size: 0.85rem; animation: slpgFloat 5s ease-in-out infinite 0.4s;">English</div>
    <div class="slpg-bubble" style="position: absolute; top: 44%; left: -6%; background: #D85A30; color: #fff; padding: 7px 14px; border-radius: 20px; font-weight: 600; font-size: 0.85rem; animation: slpgFloat 4.2s ease-in-out infinite 0.8s;">پنجابی</div>
    <div class="slpg-bubble" style="position: absolute; top: 42%; right: -6%; background: #D4537E; color: #fff; padding: 7px 14px; border-radius: 20px; font-weight: 600; font-size: 0.85rem; animation: slpgFloat 4.8s ease-in-out infinite 1.2s;">سنڌي</div>
    <div class="slpg-bubble" style="position: absolute; bottom: 4%; left: 8%; background: #BA7517; color: #fff; padding: 7px 14px; border-radius: 20px; font-weight: 600; font-size: 0.85rem; animation: slpgFloat 5.2s ease-in-out infinite 0.6s;">پښتو</div>
    <div class="slpg-bubble" style="position: absolute; bottom: 2%; right: 6%; background: #185FA5; color: #fff; padding: 7px 14px; border-radius: 20px; font-weight: 600; font-size: 0.85rem; animation: slpgFloat 4.6s ease-in-out infinite 1s;">بلوچی</div>
    <div class="slpg-bubble" style="position: absolute; bottom: -6%; left: 38%; background: #712B13; color: #fff; padding: 7px 14px; border-radius: 20px; font-weight: 600; font-size: 0.85rem; animation: slpgFloat 5s ease-in-out infinite 1.4s;">سرائیکی</div>
  </div>

  <h1 style="font-size: 2.2rem; font-weight: 700; margin: 1.5rem 0 0.5rem;">Speech and Language Processing Group</h1>
  <p style="color: #666; font-size: 1rem; max-width: 480px; margin: 0 0 2rem;">Building computational models for the understanding and generation of natural language.</p>

  <a href="/about/" class="slpg-enter-btn" style="background: #4338ca; color: #fff; padding: 0.85rem 2.2rem; border-radius: 30px; font-weight: 600; font-size: 1rem; text-decoration: none; transition: background 0.2s ease;">Welcome to the Speech and Language Processing Group</a>

</div>

<style>
@keyframes slpgFloat {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-10px); }
}
@keyframes slpgSpin {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}
.slpg-enter-btn:hover {
  background: #2563eb;
}
</style>
