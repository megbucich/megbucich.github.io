---
title: Education
icon: fas fa-graduation-cap
order: 2
---

<style>
/* ===== Shared look & feel (matches your Leadership tab) ===== */
.band{
  border-radius: 16px;
  padding: 1.25rem 1.25rem;
  margin: 1.5rem 0;
  border: 1px solid rgba(0,0,0,0.06);
}

.band-warm{
  background: linear-gradient(135deg, rgba(244,114,182,0.16), rgba(250,204,21,0.14));
}

.band-cool{
  background: linear-gradient(135deg, rgba(59,130,246,0.12), rgba(34,197,94,0.10));
}

.section-header{
  background: linear-gradient(135deg, #f472b6, #fb7185, #facc15);
  padding: 1.1rem 1rem;
  border-radius: 12px;
  margin-bottom: 1.25rem;
}
.section-header h2{
  color: #1f2937;
  margin: 0 0 0.25rem 0;
}
.section-header p{
  color: #374151;
  font-size: 0.95rem;
  margin: 0;
}

/* Two-column layout */
.role-grid{
  display: grid;
  grid-template-columns: 1.25fr 0.9fr;
  gap: 1.25rem;
  align-items: start;
}

@media (max-width: 900px){
  .role-grid{ grid-template-columns: 1fr; }
}

/* Media + cards */
.media-card{
  background: rgba(255,255,255,0.65);
  border: 1px solid rgba(0,0,0,0.08);
  border-radius: 14px;
  padding: 0.75rem;
  box-shadow: 0 10px 25px rgba(0,0,0,0.05);
  margin-bottom: 1rem;
}

.media-card img{
  width: 100%;
  height: auto;
  border-radius: 10px;
  display: block;
}

.impact-card{
  background: rgba(255,255,255,0.75);
  border: 1px solid rgba(0,0,0,0.08);
  border-radius: 14px;
  padding: 1rem;
  margin-top: 1rem;
  box-shadow: 0 10px 25px rgba(0,0,0,0.05);
}

.impact-card h4{
  margin-top: 0;
  margin-bottom: 0.6rem;
}

.impact-card ul{
  list-style: none;
  padding-left: 0;
  margin: 0;
}

.impact-card li{
  margin-bottom: 0.45rem;
}

/* Bullet polish */
.role-grid ul{
  margin-top: 0.5rem;
}
.role-grid li{
  margin-bottom: 0.45rem;
}

.small-note{
  font-size: 0.95rem;
  opacity: 0.9;
}
</style>

<section class="band band-warm">
  <div class="section-header">
    <h2>M.S. Applied Mathematics</h2>
    <p>San Diego State University — <em>Expected May 2026</em></p>
  </div>

  <div class="role-grid">

    <!-- LEFT COLUMN -->
    <div>
      <strong>Quantitative & Analytical Skill Set</strong>
      <ul>
        <li>Statistical modeling & applied regression analysis</li>
        <li>Optimization methods for decision making</li>
        <li>Control systems</li>
        <li>Numerical linear algebra</li>
        <li>Fourier and signal analysis</li>
        <li>Monte Carlo simulation & probabilistic modeling</li>
        <li>Quantitative problem solving</li>
      </ul>

    </div>

    <!-- RIGHT COLUMN -->
    <div>
      <div class="media-card">
        <img src="/assets/images/education_masters.jpg" alt="Graduate study / applied mathematics">
      </div>
    </div>

  </div>
</section>

<section class="band band-cool">
  <div class="section-header">
    <h2>B.S. Mathematics</h2>
    <p>Olivet Nazarene University — <em>May 2024</em></p>
  </div>

  <div class="role-grid">

    <!-- LEFT COLUMN -->
    <div>
      <strong>Foundational Analytical Training</strong>
      <ul>
        <li>Multivariable calculus & differential equations</li>
        <li>Linear and abstract algebra</li>
        <li>Probability theory & mathematical statistics</li>
        <li>Time series analysis</li>
        <li>Regression modeling</li>
        <li>Discrete mathematics</li>
        <li>Mathematical physics foundations</li>
      </ul>

    </div>

    <!-- RIGHT COLUMN -->
    <div>
      <div class="media-card">
        <img src="/assets/images/education_bachelors.jpg" alt="Undergraduate mathematics">
      </div>

    </div>

  </div>
</section>
