---
widget: blank
headless: true
active: true
weight: 95
title: ""
---

<!-- 아래 FAB 블록 그대로 붙여넣기 -->
<div class="kgd-fab-wrap" aria-label="Quick actions">
  <button class="kgd-fab" aria-label="Go to top" title="맨 위로" data-action="top">
    <i class="fas fa-arrow-up"></i>
  </button>
  <a class="kgd-fab" aria-label="Projects" title="Projects" href="https://kgd3443.github.io/ko/project/">
    <i class="fas fa-th-large"></i>
  </a>
  <a class="kgd-fab" aria-label="Map" title="Map" href="https://kgd3443.github.io/ko/location/jbnu/">
    <i class="fas fa-map-marker-alt"></i>
  </a>
  <a class="kgd-fab" aria-label="Email" title="Email" href="https://mail.google.com/mail/u/0/?fs=1&to=shyshy7665@naver.com&tf=cm">
    <i class="fas fa-envelope"></i>
  </a>
  <a class="kgd-fab" aria-label="GitHub" title="GitHub" href="https://github.com/kgd3443" target="_blank" rel="noopener">
    <i class="fab fa-github"></i>
  </a>
  <a class="kgd-fab" aria-label="Resume" title="Resume" href="/uploads/resume.pdf" target="_blank" rel="noopener">
    <i class="fas fa-file-alt"></i>
  </a>
</div>

<script>
(function () {
  const wrap = document.querySelector('.kgd-fab-wrap');
  if (!wrap) return;
  const btnTop = wrap.querySelector('[data-action="top"]');
  if (btnTop) btnTop.addEventListener('click', () => window.scrollTo({top:0, behavior:'smooth'}));
  const toggle = () => { if (window.scrollY > 200) wrap.classList.add('show'); else wrap.classList.remove('show'); };
  toggle(); window.addEventListener('scroll', toggle, {passive:true});
})();
</script>
