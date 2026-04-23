---
layout: page
title: Publications
permalink: /publications/
---

<style>
/* ====== Stable light publications page ====== */

.page-pubs {
  color-scheme: light;
  --bg: #ffffff;
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

/* toolbar / search */
.toolbar {
  display: flex;
  justify-content: flex-end;
  margin: 0.5rem 0 1.25rem;
}

#pub-filter {
  width: min(420px, 100%);
  padding: 0.55rem 0.7rem;
  border: 1px solid var(--ring-strong);
  border-radius: 0.5rem;
  background: #ffffff;
  color: var(--ink);
  font-size: 1rem;
  outline: none;
  box-sizing: border-box;
  -webkit-appearance: none;
  appearance: none;
  color-scheme: light;
}

#pub-filter::placeholder {
  color: #6b7280;
}

#pub-filter:focus {
  border-color: #94a3b8;
  box-shadow: 0 0 0 3px rgba(148, 163, 184, 0.18);
}

/* timeline */
.pubs {
  position: relative;
  margin: 1rem 0 3rem;
}

.pubs::before {
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

/* entry */
.pub {
  position: relative;
  margin: 0 0 1rem;
  padding: 0.25rem 0 0.35rem 2rem;
  border-radius: 0.5rem;
}

.pub:hover {
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

.pub h3 {
  margin: 0 0 0.2rem 0;
  font-size: 1.05rem;
  line-height: 1.4;
  text-align: left;
  color: var(--ink);
}

.meta {
  margin: 0 0 0.25rem 0;
  color: var(--sub);
  line-height: 1.6;
}

.links {
  margin: 0.35rem 0 0 0;
}

.links a {
  display: inline-block;
  margin: 0 0.45rem 0.35rem 0;
  padding: 0.18rem 0.5rem;
  font-size: 0.88rem;
  text-decoration: none;
  color: var(--link);
  background: #ffffff;
  border: 1px solid var(--ring-strong);
  border-radius: 0.45rem;
}

.links a:hover {
  background: var(--hover);
}

.badge {
  display: inline-block;
  margin-left: 0.45rem;
  padding: 0.08rem 0.38rem;
  font-size: 0.72rem;
  line-height: 1.2;
  color: var(--ink);
  border: 1px solid var(--ring-strong);
  border-radius: 0.4rem;
  vertical-align: middle;
}

.plain-email {
  display: inline-block;
  margin-left: 0.5rem;
  font-size: 0.85em;
  color: var(--sub);
  user-select: all;
}

/* small screens */
@media (max-width: 640px) {
  .toolbar {
    justify-content: stretch;
  }

  #pub-filter {
    width: 100%;
  }

  .pub {
    padding-left: 1.85rem;
  }

  .pub h3 {
    font-size: 1rem;
  }
}
</style>

<div class="page-pubs">
  <div class="toolbar">
    <input id="pub-filter" type="search" placeholder="Filter by title, author, venue…" aria-label="Filter publications">
  </div>

  <section class="pubs">

    <div class="year">2026</div>

    <article class="pub">
      <div class="dot" aria-hidden="true"></div>
      <h3>Finding objects of experiences <span class="badge">Proceedings</span></h3>
      <p class="meta"><strong>Furkan Dikmen</strong>. <em>to appear in the Proceedings of Sinn und Bedeutung30 (2026)</em>.</p>
      <p class="links">
        <a href="https://ling.auf.net/lingbuzz/009737" target="_blank" rel="noopener noreferrer">Preprint</a>
      </p>
    </article>

    <div class="year">2025</div>

    <article class="pub">
      <div class="dot" aria-hidden="true"></div>
      <h3>Derivational Affixes as Heads and Phrases: Evidence from Turkish Diminutives <span class="badge">Journal</span></h3>
      <p class="meta"><strong>Ümit Atlamaz, and Furkan Dikmen</strong>. <em>Morphology (2025)</em>.</p>
      <p class="links">
        <a href="https://rdcu.be/eQufz" target="_blank" rel="noopener noreferrer">DOI</a>
      </p>
    </article>

    <article class="pub">
      <div class="dot" aria-hidden="true"></div>
      <h3>Believing p, discovering ¬p: <em>meğer</em> and epistemic shifts <span class="badge">Proceedings</span></h3>
      <p class="meta"><strong>Furkan Dikmen</strong>. <em>Proceedings of Sinn und Bedeutung 29</em>.</p>
      <p class="links">
        <a href="https://ojs.ub.uni-konstanz.de/sub/index.php/sub/article/view/1220" target="_blank" rel="noopener noreferrer">DOI</a>
      </p>
    </article>

    <article class="pub">
      <div class="dot" aria-hidden="true"></div>
      <h3>Decomposing habituals <span class="badge">Book chapter</span></h3>
      <p class="meta"><strong>Furkan Dikmen</strong>, Ömer Demirok. <em>Nanosyntax and the Lexicalisation Algorithm</em>, ed. Pavel Caha, Karen De Clercq, Guido Vanden Wyngaerd. Oxford University Press.</p>
      <p class="links">
        <a href="https://doi.org/10.1093/9780198947158.003.0004" target="_blank" rel="noopener noreferrer">DOI</a>
      </p>
    </article>

    <article class="pub">
      <div class="dot" aria-hidden="true"></div>
      <h3>The role of plans for qua-events and their effects on part-structure <span class="badge">Proceedings</span></h3>
      <p class="meta">Pierre Ardisson, <strong>Furkan Dikmen</strong>, Friederike Moltmann, Kalle Müller. <em>Proceedings of the 15th International Conference on Formal Ontology in Information Systems (FOIS)</em>. IOS Press.</p>
      <p class="links">
        <a href="https://ebooks.iospress.nl/doi/10.3233/FAIA250485" target="_blank" rel="noopener noreferrer">DOI</a>
      </p>
    </article>

    <div class="year">2024</div>

    <article class="pub">
      <div class="dot" aria-hidden="true"></div>
      <h3>
        Türkçede orta ve nedensiz yapılar üzerine bir inceleme
        [An investigation of middle and anticausative constructions in Turkish]
        <span class="badge">Book chapter</span>
      </h3>
      <p class="meta">
        <strong>Furkan Dikmen</strong>, Sercan Karakaş, Sumru Özsoy (2024).
        <em>Dilbilimde Güncel Tartışmalar-4</em>. Dilbilim Derneği Yayınları.
      </p>
      <p class="links">
        <a href="mailto:furkan.dikmen@etu.univ-cotedazur.fr">Email me</a>
        <span class="plain-email">furkan.dikmen@etu.univ-cotedazur.fr</span>
      </p>
    </article>

    <article class="pub">
      <div class="dot" aria-hidden="true"></div>
      <h3>When tense shifts presuppositions: <em>hani</em> and monstrous semantics <span class="badge">Journal</span></h3>
      <p class="meta"><strong>Furkan Dikmen</strong>, Elena Guerzoni, Ömer Demirok. <em>Natural Language Semantics</em>.</p>
      <p class="links">
        <a href="https://doi.org/10.1007/s11050-023-09215-y" target="_blank" rel="noopener noreferrer">DOI</a>
      </p>
    </article>

    <div class="year">2023</div>

    <article class="pub">
      <div class="dot" aria-hidden="true"></div>
      <h3>Revisiting Agent Pseudo-Incorporation in Turkish: A Dependent Case Theoretic Perspective <span class="badge">Journal</span></h3>
      <p class="meta"><strong>Furkan Dikmen</strong>, Ömer Demirok, Ümit Atlamaz. <em>The Linguistic Review</em>.</p>
      <p class="links">
        <a href="https://doi.org/10.1515/tlr-2023-2011" target="_blank" rel="noopener noreferrer">DOI</a>
      </p>
    </article>

    <article class="pub">
      <div class="dot" aria-hidden="true"></div>
      <h3>Compounding with a polymorphic deverbaliser in Turkish <span class="badge">Journal</span></h3>
      <p class="meta"><strong>Furkan Dikmen</strong>, Ömer Demirok. <em>Roczniki Humanistyczne</em>, 71(11).</p>
      <p class="links">
        <a href="https://doi.org/10.18290/rh237111-4s" target="_blank" rel="noopener noreferrer">DOI</a>
      </p>
    </article>

    <div class="year">2022</div>

    <article class="pub">
      <div class="dot" aria-hidden="true"></div>
      <h3>How can a language have double passives but lack antipassives? <span class="badge">Journal</span></h3>
      <p class="meta"><strong>Furkan Dikmen</strong>, Ömer Demirok, Balkız Öztürk. <em>Glossa: a journal of general linguistics</em>, 7(1).</p>
      <p class="links">
        <a href="https://www.glossa-journal.org/article/id/6553/" target="_blank" rel="noopener noreferrer">DOI</a>
      </p>
    </article>

    <div class="year">2021</div>

    <article class="pub">
      <div class="dot" aria-hidden="true"></div>
      <h3>Modifying result states in Turkish <span class="badge">Proceedings</span></h3>
      <p class="meta"><strong>Furkan Dikmen</strong>, Ömer Demirok. <em>Semantics and Linguistic Theory 31</em>, pp. 42–60.</p>
      <p class="links">
        <a href="https://journals.linguisticsociety.org/proceedings/index.php/SALT/article/view/31.003" target="_blank" rel="noopener noreferrer">DOI</a>
      </p>
    </article>

    <article class="pub">
      <div class="dot" aria-hidden="true"></div>
      <h3>Turkish palatalized consonants <span class="badge">Proceedings</span></h3>
      <p class="meta">Stefano Canalis, <strong>Furkan Dikmen</strong>. <em>Proceedings of the Workshop on Turkic and Languages in Contact with Turkic (Tu+5)</em>, pp. 41–55.</p>
      <p class="links">
        <a href="https://journals.linguisticsociety.org/proceedings/index.php/tu/article/view/4781" target="_blank" rel="noopener noreferrer">DOI</a>
      </p>
    </article>

    <article class="pub">
      <div class="dot" aria-hidden="true"></div>
      <h3>Associative plurality in Turkish <span class="badge">Proceedings</span></h3>
      <p class="meta"><strong>Furkan Dikmen</strong>. <em>Proceedings of the 15th Workshop on Altaic Formal Linguistics (WAFL15)</em>, pp. 15–27.</p>
      <p class="links">
        <a href="https://furkandikmen.com/assets/publications/Associative_plurality_in_Turkish.pdf" target="_blank" rel="noopener noreferrer">Preprint</a>
        <a href="http://mitwpl.mit.edu/catalog/mwpl93/" target="_blank" rel="noopener noreferrer">Series</a>
      </p>
    </article>

    <div class="year">Work in progress</div>

    <article class="pub">
      <div class="dot" aria-hidden="true"></div>
      <h3>Attitudes of fear and expletive negation in French</h3>
      <p class="meta"><strong>Furkan Dikmen</strong> and Lena Baunaz, to be submitted to the volume Aspect and Mood in Studia Linguistica</p>
    </article>

  </section>
</div>

<script>
document.addEventListener('DOMContentLoaded', () => {
  const input = document.querySelector('#pub-filter');
  const pubs = Array.from(document.querySelectorAll('.pub'));
  if (!input) return;

  input.addEventListener('input', e => {
    const q = e.target.value.toLowerCase().trim();

    pubs.forEach(pub => {
      pub.style.display = pub.textContent.toLowerCase().includes(q) ? '' : 'none';
    });
  });
});
</script>
