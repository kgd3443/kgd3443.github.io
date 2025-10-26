---
widget: blank
headless: true
active: true
weight: 15
title: ""
---

<div class="kgd-slider">
  <img src="https://images.unsplash.com/photo-1620662731530-c2b9d06b0fef?w=1200&q=80" alt="modern workspace">
  <img src="https://images.unsplash.com/photo-1618220408826-d1d0f8a7a4ab?w=1200&q=80" alt="notebook and coffee">
  <img src="https://images.unsplash.com/photo-1603791452906-b11dcf86a6a0?w=1200&q=80" alt="plants and desk lamp">
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


.kgd-slider img {
  width: 100%;
  max-width: 420px;
  height: auto;
  border-radius: 14px;
  flex-shrink: 0;
  scroll-snap-align: center;
  box-shadow: 0 10px 22px rgba(0, 0, 0, 0.25);
  transition: transform 0.25s ease, box-shadow 0.25s ease;
}


.kgd-slider img:hover {
  transform: scale(1.03);
  box-shadow: 0 12px 28px rgba(0, 0, 0, 0.3);
}


.dark .kgd-slider img {
  box-shadow: 0 8px 18px rgba(255, 255, 255, 0.08);
}
</style>


{{< slider_projects_vanilla id="projects-auto" limit="12" interval="3000" >}}
