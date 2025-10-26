---
widget: blank
headless: true
active: true
weight: 15
title: ""
---

<div class="kgd-slider">
  <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1600&q=80" alt="Mountain landscape">
  <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=1600&q=80" alt="Ocean view">
  <img src="https://images.unsplash.com/photo-1522199710521-72d69614c702?auto=format&fit=crop&w=1600&q=80" alt="City lights">
</div>

<style>
/* 슬라이더 전체 영역 */
.kgd-slider {
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  justify-content: flex-start;
  align-items: center;
  gap: 1.5rem;
  overflow-x: auto;
  overflow-y: hidden;
  scroll-snap-type: x mandatory;
  scroll-behavior: smooth;
  -webkit-overflow-scrolling: touch;
  padding: 1rem 1rem 3rem 1rem;
}

/* 각 이미지 설정 */
.kgd-slider img {
  width: 100%;
  max-width: 480px;
  height: auto;
  border-radius: 12px;
  flex-shrink: 0;
  scroll-snap-align: center;
  object-fit: cover;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.25);
  transition: transform 0.3s ease;
}

/* hover 효과 */
.kgd-slider img:hover {
  transform: scale(1.05);
}

/* 다크 모드 대응 */
.dark .kgd-slider img {
  box-shadow: 0 8px 18px rgba(255, 255, 255, 0.15);
}
</style>
