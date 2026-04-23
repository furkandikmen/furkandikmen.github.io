---
layout: page
title: Presentations
permalink: /presentations/
---

<style>
/* ====== Stable light presentations page ====== */

.page-talks {
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

/* toolbar / search */
.toolbar {
  display: flex;
  justify-content: flex-end;
  margin: 0.5rem 0 1.25rem;
}

#talk-filter {
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

#talk-filter::placeholder {
  color: #6b7280;
}

#talk-filter:focus {
  border-color: #94a3b8;
  box-shadow: 0 0 0 3px rgba(148, 163, 184, 0.18);
}

/* timeline */
.talks {
  position: relative;
  margin: 1rem 0 3rem;
}

.talks::before {
  content: "";
  position: absolute;
  left: 1rem;
  top: 0.25rem;
  bottom: 0.25rem;
  width: 2px;
  background: var(--ring);
}

.year-group {
  position: relative;
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
.talk {
  position: relative;
  margin: 0 0 1rem;
  padding: 0.25rem 0 0.35rem 2rem;
  border-radius: 0.5rem;
}

.talk:hover {
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

.talk h3 {
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

/* small screens */
@media (max-width: 640px) {
  .toolbar {
    justify-content: stretch;
  }

  #talk-filter {
    width: 100%;
  }

  .talk {
    padding-left: 1.85rem;
  }

  .talk h3 {
    font-size: 1rem;
  }
}
</style>

<div class="page-talks">
  <div class="toolbar">
    <input id="talk-filter" type="search" placeholder="Filter by title, author, venue…" aria-label="Filter presentations">
  </div>

  <section class="talks">

    <div class="year-group">
      <div class="year">2026</div>

      <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
        <div class="dot" aria-hidden="true"></div>
        <h3 itemprop="name">Reporting experiences: (gibi) gel in Turkish. <span class="badge">Talk</span></h3>
        <p class="meta">
          <strong>Furkan Dikmen</strong>. TU+11 (Workshop on Turkic and Languages in Contact with Turkic (TU+)), MIT, Cambridge, USA.
        </p>
        <p class="links">
          <a href="https://turkicworkshop.github.io/tu11/program.html" target="_blank" rel="noopener noreferrer">Program</a>
          <a href="https://furkandikmen.com/assets/presentations/TU_11_conference (3).pdf" target="_blank" rel="noopener noreferrer">PDF</a>
        </p>
      </article>

      <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
        <div class="dot" aria-hidden="true"></div>
        <h3 itemprop="name">Greek and Turkish passives: A comparative approach <span class="badge">Talk</span></h3>
        <p class="meta">
          Nikos Angelopoulos, Ömer Demirok and <strong>Furkan Dikmen</strong>.
          ALF 1 (Atelier de linguistique formelle / Atelier for formal linguistics),
          Université Paris 8/CNRS, Structures Formelles du Langage, Paris, France.
        </p>
        <p class="links">
          <a href="https://www.sfl.cnrs.fr/en/alf-1" target="_blank" rel="noopener noreferrer">Program</a>
          <a href="https://furkandikmen.com/assets/presentations/ALF_workshop_Paris.pdf" target="_blank" rel="noopener noreferrer">Handout</a>
        </p>
      </article>

      <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
        <div class="dot" aria-hidden="true"></div>
        <h3 itemprop="name">Seemings and beliefs <span class="badge">Talk</span></h3>
        <p class="meta">
          <strong>Furkan Dikmen</strong>. Conference of the Student Organization of Linguistics in Europe (ConSOLE34), Pavia, Italy.
        </p>
        <p class="links">
          <a href="https://console34.github.io/program/" target="_blank" rel="noopener noreferrer">Program</a>
        </p>
      </article>
    </div>

    <div class="year-group">
      <div class="year">2025</div>

      <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
        <div class="dot" aria-hidden="true"></div>
        <h3 itemprop="name">French perception verbs are not equal <span class="badge">Talk</span></h3>
        <p class="meta">
          <strong>Furkan Dikmen</strong>, Lena Baunaz, Katerina Palasis.
          Going Romance 2025, Venice, Italy.
        </p>
        <p class="links">
          <a href="https://furkandikmen.com/assets/presentations/GoingRomance%20(6).pdf" target="_blank" rel="noopener noreferrer">PDF</a>
        </p>
      </article>

      <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
        <div class="dot" aria-hidden="true"></div>
        <h3 itemprop="name">Finding objects of experiences <span class="badge">Poster</span></h3>
        <p class="meta">
          <strong>Furkan Dikmen</strong>. Sinn und Bedeutung 30 (SuB30), Frankfurt, Germany.
        </p>
        <p class="links">
          <a href="https://vicom.info/sub30-program-2/" target="_blank" rel="noopener noreferrer">Program</a>
        </p>
      </article>

      <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
        <div class="dot" aria-hidden="true"></div>
        <h3 itemprop="name">Syllabic harmony in Turkish</h3>
        <p class="meta">
          Mehmet Can Dadan, Alper Canberk Balcı, <strong>Furkan Dikmen</strong>, Stefano Canalis.
          Presented in the OCP Workshop on Vowel Harmony (OCP22).
        </p>
        <p class="links">
          <a href="https://www.universiteitleiden.nl/en/events/2025/02/vowel-harmony" target="_blank" rel="noopener noreferrer">Event page</a>
        </p>
      </article>
    </div>

    <div class="year-group">
      <div class="year">2024</div>

      <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
        <div class="dot" aria-hidden="true"></div>
        <h3 itemprop="name">A novel account of Turkish singular and plural marking</h3>
        <p class="meta">
          Elena Guerzoni, <strong>Furkan Dikmen</strong>, Penka Stateva.
          17th conference on Syntax, Phonology and Language Analysis (SinFonIJA 17).
        </p>
        <p class="links">
          <a href="https://sites.google.com/view/sinfonija-17/home?authuser=0" target="_blank" rel="noopener noreferrer">Event page</a>
        </p>
      </article>

      <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
        <div class="dot" aria-hidden="true"></div>
        <h3 itemprop="name">Believing p, discovering ¬p: <em>meğer</em> and epistemic shifts <span class="badge">Poster</span></h3>
        <p class="meta">
          <strong>Furkan Dikmen</strong>. Sinn und Bedeutung 29.
        </p>
        <p class="links">
          <a href="https://furkandikmen.com/assets/presentations/DIKMEN%20.pdf" target="_blank" rel="noopener noreferrer">PDF</a>
          <a href="https://drive.google.com/file/d/1iVKxHEO0l1wIaTzoIHKD2u2d6qM9RGf5/view" target="_blank" rel="noopener noreferrer">Conference page</a>
        </p>
      </article>

      <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
        <div class="dot" aria-hidden="true"></div>
        <h3 itemprop="name">What was believed, what was true: The case of <em>meğer</em></h3>
        <p class="meta">
          <strong>Furkan Dikmen</strong>. Student Conference on Linguistics 2024.
        </p>
        <p class="links">
          <a href="https://furkandikmen.com/assets/presentations/SCOL24.pdf" target="_blank" rel="noopener noreferrer">PDF</a>
        </p>
      </article>
    </div>

    <div class="year-group">
      <div class="year">2023</div>

      <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
        <div class="dot" aria-hidden="true"></div>
        <h3 itemprop="name">When tense shifts expressive presuppositions: <em>hani</em> and monstrous semantics</h3>
        <p class="meta">
          <strong>Furkan Dikmen</strong>, Elena Guerzoni, Ömer Demirok. Tu+8.
        </p>
        <p class="links">
          <a href="https://furkandikmen.com/assets/presentations/TU+8%20(3).pdf" target="_blank" rel="noopener noreferrer">Handout</a>
          <a href="https://furkandikmen.com/assets/presentations/Tu+8-Dikmen,%20Guerzoni%20&%20Demirok%20(1).pdf" target="_blank" rel="noopener noreferrer">Abstract</a>
        </p>
      </article>
    </div>

    <div class="year-group">
      <div class="year">2022</div>

      <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
        <div class="dot" aria-hidden="true"></div>
        <h3 itemprop="name">Adjectival Diminutives in Turkish</h3>
        <p class="meta">
          Ümit Atlamaz, <strong>Furkan Dikmen</strong>. DMTD Workshop series &amp; WAFL16.
        </p>
        <p class="links">
          <a href="https://furkandikmen.com/assets/presentations/Adjectival_Dimunitives.pdf" target="_blank" rel="noopener noreferrer">PDF</a>
        </p>
      </article>
    </div>

    <div class="year-group">
      <div class="year">2021</div>

      <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
        <div class="dot" aria-hidden="true"></div>
        <h3 itemprop="name">Compounding with a polymorphic deverbalizer in Turkish</h3>
        <p class="meta">
          <strong>Furkan Dikmen</strong>, Ömer Demirok, Balkız Öztürk. 9th Workshop on Nominalizations (JeNOM 9).
        </p>
        <p class="links">
          <a href="https://sites.google.com/view/nominalizations-jenom9/program" target="_blank" rel="noopener noreferrer">Program</a>
        </p>
      </article>

      <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
        <div class="dot" aria-hidden="true"></div>
        <h3 itemprop="name">Modifying result states in Turkish <span class="badge">Poster</span></h3>
        <p class="meta">
          <strong>Furkan Dikmen</strong>, Ömer Demirok. Semantics and Linguistic Theory (SALT 31).
        </p>
        <p class="links">
          <a href="https://osf.io/g8da5/" target="_blank" rel="noopener noreferrer">OSF</a>
        </p>
      </article>
    </div>

    <div class="year-group">
      <div class="year">2020</div>

      <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
        <div class="dot" aria-hidden="true"></div>
        <h3 itemprop="name">Palatalized Turkish consonants and vowel harmony</h3>
        <p class="meta">
          Stefano Canalis, <strong>Furkan Dikmen</strong>. The 5th workshop on Turkic and languages in contact with Turkic (Tu+5).
        </p>
        <p class="links">
          <a href="https://bpb-us-w2.wpmucdn.com/sites.udel.edu/dist/1/9450/files/2019/12/tunamed.pdf" target="_blank" rel="noopener noreferrer">PDF</a>
        </p>
      </article>
    </div>

    <div class="year-group">
      <div class="year">2019</div>

      <article class="talk" itemscope itemtype="https://schema.org/CreativeWork">
        <div class="dot" aria-hidden="true"></div>
        <h3 itemprop="name">The semantics of the associative -lAr in Turkish <span class="badge">Poster</span></h3>
        <p class="meta">
          <strong>Furkan Dikmen</strong>. Workshop on Altaic Formal Linguistics 15 (WAFL 2019).
        </p>
        <p class="links">
          <a href="https://furkandikmen.com/assets/presentations/WAFL%2015-Furkan%20Dikmen.pdf" target="_blank" rel="noopener noreferrer">PDF</a>
        </p>
      </article>
    </div>

  </section>
</div>

<script>
document.addEventListener('DOMContentLoaded', () => {
  const input = document.querySelector('#talk-filter');

  document.querySelectorAll('.talk h3').forEach(h3 => {
    if (!h3.querySelector('.badge')) {
      const span = document.createElement('span');
      span.className = 'badge';
      span.textContent = 'Talk';
      h3.appendChild(document.createTextNode(' '));
      h3.appendChild(span);
    }
  });

  function applyFilter() {
    const q = (input?.value || '').toLowerCase().trim();

    document.querySelectorAll('.year-group').forEach(group => {
      const talks = group.querySelectorAll('.talk');
      let visibleCount = 0;

      talks.forEach(talk => {
        const match = talk.textContent.toLowerCase().includes(q);
        talk.style.display = match ? '' : 'none';
        if (match) visibleCount++;
      });

      group.style.display = visibleCount > 0 ? '' : 'none';
    });
  }

  if (input) input.addEventListener('input', applyFilter);
  applyFilter();
});
</script>
