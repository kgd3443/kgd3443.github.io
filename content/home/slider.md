---
widget: blank
headless: true
active: true
weight: 15
title: ""
---

<div class="kgd-slider">
  <img src="https://images.unsplash.com/photo-1620662731530-c2b9d06b0fef?auto=format&fit=crop&w=1600&q=80" alt="Mountain landscape">
  <img src="https://images.unsplash.com/photo-1618220408826-d1d0f8a7a4ab?auto=format&fit=crop&w=1600&q=80" alt="Ocean view">
  <img src="https://images.unsplash.com/photo-1603791452906-b11dcf86a6a0?auto=format&fit=crop&w=1600&q=80" alt="City lights">
</div>

<style>
.kgd-slider {
  display: flex;
  justify-content: center;
  align-items: flex-start;
  flex-wrap: nowrap;
  gap: 1.5rem;
  padding: 1rem 0 3rem 0;
  overflow-x: auto;
  scroll-snap-type: x mandatory;
  scroll-behavior: smooth;
}
</style>
