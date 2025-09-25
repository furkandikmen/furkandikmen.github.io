---
layout: page
title: Projects
permalink: /projects/
---

<style>
/* ——— minimal inline CSS to match your other pages ——— */
.card{
  border:1px solid #e5e7eb; border-radius:.75rem; padding:1rem 1.1rem; margin: .5rem 0 1.25rem;
}
.card h2{ margin:0 0 .35rem; font-size:1.2rem; }
.card p{ margin:.25rem 0 0; color:#374151; }
.card .links a{ display:inline-block; margin:.5rem .5rem 0 0; border:1px solid #e5e7eb; border-radius:.5rem; padding:.18rem .5rem; text-decoration:none; }

.events{ position:relative; margin:1.5rem 0 3rem; }
.events::before{ content:""; position:absolute; left:1rem; top:.25rem; bottom:.25rem; width:2px; background:#e5e7eb; }

/* YEAR pill above the timeline */
.year{
  position:relative; z-index:1; display:inline-block;
  padding:.15rem .6rem; margin:2rem 0 .6rem;
  font-weight:700; letter-spacing:.02em; line-height:1;
  color:#111827; background:#fff; border:1px solid #e5e7eb; border-radius:.75rem;
}

.event{ position:relative; margin:0 0 1rem; padding:.25rem 0 .25rem 2rem; border-radius:.6rem; }
.event:hover{ background:rgba(0,0,0,.03); }
.dot{ position:absolute; left:.5rem; top:.85rem; width:.8rem; height:.8rem; border-radius:50%; background:#111827; box-shadow:0 0 0 4px #fff; }

.event h3{ margin:0 0 .2rem 0; font-size:1.05rem; line-height:1.35; }
.meta{ margin:0 0 .25rem 0; color:#374151; }
.links{ margin:.25rem 0 0 0; }
.links a{ display:inline-block; margin-right:.5rem; font-size:.85rem; text-decoration:none; border:1px solid #e5e7eb; padding:.1rem .45rem; border-radius:.375rem; }

@media (prefers-color-scheme: dark){
  .card, .links a{ border-color:#374151; }
  .card p, .meta{ color:#cbd5e1; }
  .events::before{ background:#374151; }
  .year{ background:#0b0f14; color:#e5e7eb; border-color:#374151; }
  .dot{ background:#e5e7eb; }
  .event:hover{ background:rgba(255,255,255,.04); }
}
</style>

<!-- Project headline card -->
<div class="card">
  <h2>IMMAGES — Hosting a clause: Implications for the Matrix and its Guests</h2>
  <p>Research project (CNRS–BCL) on clause hosting and its implications for the matrix/embedded relation.</p>
  <p class="links">
    <a href="https://immages.hypotheses.org/" target="_blank" rel="noopener noreferrer">Project site</a>
  </p>
</div>

<section class="events">
  <div class="year">2024</div>

  <!-- Tübingen workshop -->
  <article class="event">
    <div class="dot" aria-hidden="true"></div>
    <h3>IMMAGES Workshop — Tübingen (11–12 Oct 2024)</h3>
    <p class="meta">
      <strong>Furkan Dikmen</strong> (12 Oct 2024).
      <em>find verbs and discretionary predicates</em>. Talk presented at the IMMAGES workshop, Tübingen, Germany.
    </p>
    <p class="links">
      <a href="https://immages.hypotheses.org/1013" target="_blank" rel="noopener noreferrer">Workshop page</a>
      <a href="https://furkandikmen.com/assets/presentations/find_predicates%281%29.pdf" target="_blank" rel="noopener noreferrer">Handout / slides (PDF)</a>
    </p>
  </article>

  <!-- Online meetings -->
  <div class="year">Online meetings</div>

  <article class="event">
    <div class="dot" aria-hidden="true"></div>
    <h3>IMMAGES seminar — Online</h3>
    <p class="meta">
      <strong>Furkan Dikmen</strong> (18 Dec 2024). <em>Marking belief shifts</em>. Talk presented in IMMAGES seminars.
    </p>
    <p class="links">
      <a href="https://furkandikmen.com/assets/presentations/immages_presentation_dec_18%20%282%29.pdf" target="_blank" rel="noopener noreferrer">Slides (PDF)</a>
    </p>
  </article>
</section>
