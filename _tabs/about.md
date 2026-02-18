---
title: ""
icon: fas fa-user
order: 1
---

<style>
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

.band-sunset{
  background: linear-gradient(135deg, rgba(251,113,133,0.14), rgba(250,204,21,0.12), rgba(244,114,182,0.12));
}

.section-header{
  background: linear-gradient(135deg, #f472b6, #fb7185, #facc15);
  padding: 1.1rem 1rem;
  border-radius: 12px;
  margin-bottom: 1.25rem;
}
.section-header h2{
  color: #1f2937;
  margin: 0;
}

.two-col{
  display: grid;
  grid-template-columns: 1.2fr 0.9fr;
  gap: 1.25rem;
  align-items: start;
}

@media (max-width: 900px){
  .two-col{ grid-template-columns: 1fr; }
}

.media-card{
  background: rgba(255,255,255,0.75);
  border: 1px solid rgba(0,0,0,0.08);
  border-radius: 14px;
  padding: 0.75rem;
  box-shadow: 0 10px 25px rgba(0,0,0,0.05);
}

.media-card img{
  width: 100%;
  height: auto;
  border-radius: 12px;
  display: block;
}

.info-card{
  background: rgba(255,255,255,0.78);
  border: 1px solid rgba(0,0,0,0.08);
  border-radius: 14px;
  padding: 1rem;
  margin-top: 1rem;
  box-shadow: 0 10px 25px rgba(0,0,0,0.05);
}

.info-card ul{
  list-style: none;
  padding-left: 0;
  margin: 0;
}

.info-card li{
  margin-bottom: 0.5rem;
}

.small-note{
  opacity: 0.9;
  line-height: 1.45;
}
</style>

<div class="section-header">
  <h2>About Me</h2>
</div>

<section class="band band-warm">
  <div class="two-col">

    <!-- LEFT -->
    <div>
      <p>
        I am currently in my second year of an M.S. in Applied Mathematics at
        <a href="https://math.sdsu.edu/graduate/applied-mathematics/">San Diego State University</a>,
        graduating in May 2026.
      </p>

      <p>
        I am interested in industry roles where I can combine mathematics and data analysis
        to work on real-world problems. Through my
        <a href="/education/">academic training</a> and
        <a href="/research/">research experience</a>, I have developed experience in
        mathematical modeling, statistics, numerical methods, and data visualization.
      </p>

      <p class="small-note">
        I am comfortable working with computational tools, collaborating with others,
        and approaching unfamiliar problems with structure and persistence.
      </p>

      <div class="info-card">
        <h4 style="margin-top:0;">Overview</h4>
        <ul>
          <li><strong>Degree:</strong> M.S. Applied Mathematics (2026)</li>
          <li><strong>Focus:</strong> Modeling, statistics, applied computation</li>
          <li><strong>Current Role:</strong> Teaching Assistant (Calculus I & Life Sciences)</li>
          <li><strong>Location:</strong> San Diego, CA</li>
        </ul>
      </div>
    </div>

    <!-- RIGHT -->
    <div>
      <div class="media-card">
        <img src="/assets/images/about_me.jpeg" alt="Portrait">
      </div>
    </div>

  </div>
</section>

<section class="band band-cool">
  <div class="section-header">
    <h2>Academic Journey</h2>
  </div>

  <div class="two-col">

    <!-- LEFT -->
    <div>
      <p>
        I began my undergraduate studies at
        <a href="https://www.olivet.edu/academics/areas-study/mathematics">Olivet Nazarene University</a>
        in 2020, initially planning to pursue a career in education.
        During my early coursework, I rediscovered how much I enjoyed problem solving.
      </p>

      <p>
        As I progressed through calculus, statistics, and abstract mathematics between
        2020 and 2024, my interests shifted toward understanding how mathematical tools
        could be applied beyond the classroom.
      </p>

      <p>
        I explored several possible directions, including education and actuarial science,
        before realizing that applied mathematics provided the balance of theory and application
        that I found most meaningful.
      </p>
    </div>

    <!-- RIGHT -->
    <div>
      <div class="media-card">
        <img src="/assets/images/grad_photo.jpg" alt="Undergraduate graduation">
      </div>
    </div>

  </div>
</section>

<section class="band band-sunset">
  <div class="two-col">

    <!-- LEFT IMAGE -->
    <div>
      <div class="media-card">
        <img src="/assets/images/GMCS.jpeg" alt="Graduate experience">
      </div>
    </div>

    <!-- RIGHT TEXT -->
    <div>
      <h2 style="margin-top:0;">Graduate Growth</h2>

      <p>
        When applying to graduate programs, I was motivated by a desire to challenge myself
        academically and personally. In Fall 2024, I chose SDSU for its applied focus and
        opportunity to teach.
      </p>

      <p>
        The transition into graduate school required adapting to a stronger emphasis on
        computation and independent problem solving. Over time, I gained confidence in
        navigating unfamiliar material, collaborating with peers, and approaching complex
        problems with resilience.
      </p>

      <p class="small-note">
        I view my academic path as shaped by exploration, adaptability, and persistence,
        qualities that now define how I approach both mathematics and new challenges.
      </p>
    </div>

  </div>
</section>
