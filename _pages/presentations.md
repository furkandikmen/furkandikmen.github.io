---
layout: page
title: Presentations
permalink: /presentations/
---

<style>
/* ==== minimal inline CSS (titles aligned left) ==== */
.toolbar{display:flex;justify-content:flex-end;margin:.5rem 0 1.25rem}
#talk-filter{width:min(420px,100%);padding:.55rem .7rem;border:1px solid #d1d5db;border-radius:.5rem}

.talks{position:relative;margin:1rem 0 3rem}
.talks::before{content:"";position:absolute;left:1.1rem;top:.25rem;bottom:.25rem;width:2px;background:#e5e7eb}
.year{font-weight:700;margin:2rem 0 .6rem;color:#111827;letter-spacing:.02em}

.talk{position:relative;margin:0 0 1.2rem;padding:.25rem 0 .35rem 2rem;border-radius:.75rem}
.talk:hover{background:rgba(0,0,0,.03)}
.dot{position:absolute;left:.5rem;top:.85rem;width:.8rem;height:.8rem;border-radius:50%;background:#111827;box-shadow:0 0 0 4px #fff}

.talk h3{margin:0 0 .25rem 0;font-size:1.06rem;line-height:1.35;text-align:left}
.meta{margin:.15rem 0 .2rem 0;color:#374151}
.badge{font-size:.7rem;border:1px solid #d1d5db;padding:.05rem .35rem;border-radius:.375rem;margin-left:.4rem}

.links{margin:.25rem 0 0 0;padding:0;font-size:.9em;line-height:1}
.links a{display:inline-block;margin:0 .45rem .35rem 0;padding:.18rem .5rem;border:1px solid #d1d5db;border-radius:.5rem;text-decoration:none}
.links a:hover{background:#f3f4f6}

@media (prefers-color-scheme: dark){
  #talk-filter{border-color:#4b5563;background:#0b0f14;color:#e5e7eb}
  .talks::before{background:#374151}
  .year{color:#e5e7eb}
  .dot{background:#e5e7eb}
  .talk:hover{background:rgba(255,255,255,.04)}
  .meta{color:#cbd5e1}
  .links a,.badge{border-color:#4b5563}
}
</style>

<div class="toolbar">
  <input id="talk-filter" type="search" placeholder="Filter by title, author, venue…" aria-label="Filter presentations">
</div>

<section class="talks">
  <div class="year">2025</div>

  <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
    <div class="dot" aria-hidden="true"></div>
    <h3 itemprop="name">French perception verbs are not equal <span class="badge">Talk</span></h3>
    <p class="meta"><strong>Furkan Dikmen</strong>, Lena Baunaz, Katerina Palasis (2025). Going Romance 2025, Venice, Italy.</p>
  </article>

  <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
    <div class="dot" aria-hidden="true"></div>
    <h3 itemprop="name">The role of plans for qua-events and their effects on part-structure <span class="badge">Paper</span></h3>
    <p class="meta">Pierre Ardisson, <strong>Furkan Dikmen</strong>, Friederike Moltmann, Kalle Müller (2025). 15th International Conference on Formal Ontology in Information Systems (FOIS), Catania, Sicily.</p>
  </article>

  <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
    <div class="dot" aria-hidden="true"></div>
    <h3 itemprop="name">Finding objects of experiences <span class="badge">Poster</span></h3>
    <p class="meta"><strong>Furkan Dikmen</strong> (2025). Sinn und Bedeutung 30 (SuB30), Frankfurt, Germany.</p>
    <p class="links">
      <a href="https://vicom.info/sub30-program-2/" target="_blank" rel="noopener noreferrer">Program</a>
      <a href="https://www.dropbox.com/scl/fi/u9qhvgh99m8mkt57sq881/Dikmen.pdf?dl=0&rlkey=jca4va70dirvzobcji8rnchne" target="_blank" rel="noopener noreferrer">Poster PDF</a>
    </p>
  </article>

  <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
    <div class="dot" aria-hidden="true"></div>
    <h3 itemprop="name">Syllabic harmony in Turkish</h3>
    <p class="meta">Mehmet Can Dadan, Alper Canberk Balcı, <strong>Furkan Dikmen</strong>, Stefano Canalis (2025). Presented in the OCP Workshop on Vowel Harmony (OCP22).</p>
    <p class="links">
      <a href="https://www.universiteitleiden.nl/en/events/2025/02/vowel-harmony" target="_blank" rel="noopener noreferrer">Event page</a>
    </p>
  </article>

  <!-- keep your 2024, 2023, 2022, 2021, 2020, 2019 entries in the same structure -->
</section>

<script>
/* tiny client-side filter (optional) */
document.addEventListener('DOMContentLoaded', () => {
  const input = document.querySelector('#talk-filter');
  input?.addEventListener('input', e => {
    const q = e.target.value.toLowerCase();
    document.querySelectorAll('.talk').forEach(t => {
      t.style.display = t.textContent.toLowerCase().includes(q) ? '' : 'none';
    });
  });
});
</script>
