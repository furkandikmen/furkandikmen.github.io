---
layout: page
title: Projects
permalink: /projects/
---

<style>
/* ====== Stable light projects page ====== */

.page-projects {
  color-scheme: light;
  --ink: #111827;
  --text: #1f2937;
  --sub: #4b5563;
  --ring: #dbe1e8;
  --ring-strong: #cfd8e3;
  --hover: #f8fafc;
  --link: #2563eb;
  --dot-ring: #ffffff;
  color: var(--text);
}

/* headline card */
.card {
  border: 1px solid var(--ring);
  border-radius: 0.75rem;
  padding: 1rem 1.1rem;
  margin: 0.5rem 0 1.25rem;
  background: #ffffff;
}

.card h2 {
  margin: 0 0 0.35rem;
  font-size: 1.2rem;
  line-height: 1.3;
  color: var(--ink);
}

.card p {
  margin: 0.25rem 0 0;
  color: var(--sub);
  line-height: 1.6;
}

.card .links a,
.links a {
  display: inline-block;
  margin: 0.5rem 0.5rem 0 0;
  padding: 0.18rem 0.5rem;
  font-size: 0.88rem;
  text-decoration: none;
  color: var(--link);
  background: #ffffff;
  border: 1px solid var(--ring-strong);
  border-radius: 0.45rem;
}

.card .links a:hover,
.links a:hover {
  background: var(--hover);
}

/* timeline */
.events {
  position: relative;
  margin: 1.5rem 0 3rem;
}

.events::before {
  content: "";
  position: absolute;
  left: 1rem;
  top: 0.25rem;
  bottom: 0.25rem;
  width: 2px;
  background: var(--ring);
}

/* year pill */
.year {
  position: relative;
  z-index: 1;
  display: inline-block;
  padding: 0.2rem 0.7rem;
  margin: 2rem 0 0.7rem;
  font-weight: 700;
  letter-spacing: 0.02em;
  line-height: 1;
  color: var(--ink);
  background: #ffffff;
  border: 1px solid var(--ring);
  border-radius: 999px;
}

/* event entries */
.event {
  position: relative;
  margin: 0 0 1rem;
  padding: 0.25rem 0 0.35rem 2rem;
  border-radius: 0.6rem;
}

.event:hover {
  background: rgba(15, 23, 42, 0.04);
}

.dot {
  position: absolute;
  left: 0.5rem;
  top: 0.85rem;
  width: 0.8rem;
  height: 0.8rem;
  border-radius: 50%;
  background: var(--ink);
  box-shadow: 0 0 0 4px var(--dot-ring);
}

.event h3 {
  margin: 0 0 0.2rem 0;
  font-size: 1.05rem;
  line-height: 1.35;
  color: var(--ink);
}

.meta {
  margin: 0 0 0.25rem 0;
  color: var(--sub);
  line-height: 1.6;
}

.links {
  margin: 0.25rem 0 0 0;
}

/* small screens */
@media (max-width: 640px) {
  .event {
    padding-left: 1.85rem;
  }

  .event h3 {
    font-size: 1rem;
  }
}
</style>

<div class="page-projects">
  <div class="card">
    <h2>IMMAGES — Hosting a clause: Implications for the Matrix and its Guests</h2>
    <p>Research project (ANR-DFG) on clause hosting and its implications for the matrix/embedded relation.</p>
    <p class="links">
      <a href="https://immages.hypotheses.org/" target="_blank" rel="noopener noreferrer">Project site</a>
    </p>
  </div>

  <section class="events">
    <div class="year">2025</div>

    <article class="event">
      <div class="dot" aria-hidden="true"></div>
      <h3>IMMAGES Workshop — Tours (16–17 Oct 2025)</h3>
      <p class="meta">
        <strong>Furkan Dikmen</strong> (16 Oct 2025).
        <em>Seemings, their content and as if clauses</em>. Talk presented at the IMMAGES workshop, Tours, France.
      </p>
      <p class="links">
        <a href="https://immages.hypotheses.org/1013" target="_blank" rel="noopener noreferrer">Workshop page</a>
        <a href="https://furkandikmen.com/assets/presentations/tours_workshop (13).pdf" target="_blank" rel="noopener noreferrer">Handout</a>
      </p>
    </article>

    <div class="year">2024</div>

    <article class="event">
      <div class="dot" aria-hidden="true"></div>
      <h3>IMMAGES Workshop — Tübingen (11–12 Oct 2024)</h3>
      <p class="meta">
        <strong>Furkan Dikmen</strong> (12 Oct 2024).
        <em>find verbs and discretionary predicates</em>. Talk presented at the IMMAGES workshop, Tübingen, Germany.
      </p>
      <p class="links">
        <a href="https://immages.hypotheses.org/1013" target="_blank" rel="noopener noreferrer">Workshop page</a>
        <a href="https://furkandikmen.com/assets/presentations/find_predicates%281%29.pdf" target="_blank" rel="noopener noreferrer">Handout</a>
      </p>
    </article>

    <div class="year">Online meetings</div>

    <article class="event">
      <div class="dot" aria-hidden="true"></div>
      <h3>IMMAGES seminar — Online</h3>
      <p class="meta">
        <strong>Furkan Dikmen</strong> (18 Dec 2024). <em>Marking belief shifts</em>. Talk presented in IMMAGES seminars.
      </p>
      <p class="links">
        <a href="https://furkandikmen.com/assets/presentations/immages_presentation_dec_18%20%282%29.pdf" target="_blank" rel="noopener noreferrer">Handout</a>
      </p>
    </article>
  </section>
</div>
