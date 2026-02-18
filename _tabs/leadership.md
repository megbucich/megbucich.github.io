---
title: Leadership
icon: fas fa-chalkboard-teacher
order: 4
---

<style>
/* ===== Layout helpers ===== */
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

/* Header pill */
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
  color: #1f2937;
  font-size: 0.95rem;
  margin: 0;
}

/* Two-column role layout */
.role-grid{
  display: grid;
  grid-template-columns: 1.25fr 0.9fr;
  gap: 1.25rem;
  align-items: start;
}

@media (max-width: 900px){
  .role-grid{ grid-template-columns: 1fr; }
}

/* Quote grid */
.quote-grid{
  display:grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 0.9rem;
  margin-top: 0.75rem;
}

.quote-card{
  background: rgba(255,255,255,0.85);
  border: 1px solid rgba(0,0,0,0.08);
  border-radius: 14px;
  padding: 0.9rem 0.95rem;
  box-shadow: 0 10px 25px rgba(0,0,0,0.06);
  line-height: 1.35;
  position: relative;
}

.quote-card:before{
  content: "“";
  position: absolute;
  top: -12px;
  left: 10px;
  font-size: 40px;
  opacity: 0.18;
}

.quote-tag{
  display: inline-block;
  font-size: 0.78rem;
  font-weight: 600;
  opacity: 0.75;
  margin-bottom: 0.35rem;
}

/* Media card */
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

.small-note{
  font-size: 0.95rem;
  opacity: 0.9;
}

/* Bullet polish */
.role-grid ul{
  margin-top: 0.5rem;
}
.role-grid li{
  margin-bottom: 0.45rem;
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

.quote-board{
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 0.85rem;
  margin-top: 0.75rem;
}

@media (max-width: 950px){
  .quote-board{
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }
}

@media (max-width: 600px){
  .quote-board{
    grid-template-columns: 1fr;
  }
}

.quote-tile{
  background: rgba(255,255,255,0.78);
  border: 1px solid rgba(0,0,0,0.08);
  border-radius: 14px;
  padding: 0.95rem 1rem;
  box-shadow: 0 10px 25px rgba(0,0,0,0.05);
  line-height: 1.35;
  font-size: 0.98rem;
  opacity: 0.95;
}


</style>




<!-- ===== Student Impact Band (clean 3x3 board) ===== -->
<section class="band band-sunset">
  <div class="section-header">
    <h2>Student Impact & Evaluation Feedback</h2>
  </div>

  <div class="quote-board">
    <div class="quote-tile">“Explains complex problems and makes them feel easy.”</div>
    <div class="quote-tile">“Encouraged us to talk and ask as many questions as possible.”</div>
    <div class="quote-tile">“Guided us in the right direction without giving away the answer.”</div>

    <div class="quote-tile">“Kept everyone involved. Super inclusive; I never left class feeling any less than”</div>
    <div class="quote-tile">“A safe space to ask questions. She never made me feel bad for asking questions”</div>
    <div class="quote-tile">“She knew everyone's name by the second week.”</div>

    <div class="quote-tile">“Extremely smart and able to answer genuinely any question we had.”</div>
    <div class="quote-tile">“Ensured no student was left behind regardless of how little initial understanding they had.”</div>
    <div class="quote-tile">“Helped in a way that made me actually do the work”</div>
  </div>
</section>



<section class="band band-cool">
  <div class="section-header">
    <h2>Graduate Instructional Leadership</h2>
    <p>San Diego State University • 2024–Present</p>
  </div>

  <div class="role-grid">

    <!-- LEFT COLUMN -->
    <div>
      <p>
        Served as a Teaching Assistant in coordinated calculus programs 
        supporting high-enrollment foundational mathematics courses.
      </p>

      <strong>Key Responsibilities</strong>
      <ul>
        <li>Led structured discussion sections twice weekly for Calculus I and Calculus for the Life Sciences</li>
        <li>Facilitated collaborative, whiteboard-centered problem solving environments designed to increase student engagement</li>
        <li>Managed course communication channels including email and class Discord platforms</li>
        <li>Maintained grading systems and assessment databases for assigned student cohorts</li>
        <li>Delivered targeted academic intervention during office hours through individualized performance coaching</li>
        <li>Collaborated with course coordinators and fellow TAs to ensure consistency across multi-section courses</li>
      </ul>

      <!-- IMPACT SNAPSHOT (NOW CORRECTLY IN LEFT COLUMN) -->
      <div class="impact-card">
        <h4>Overview</h4>
        <ul>
          <li><strong>200+</strong> Students Supported</li>
          <li><strong>2 Years</strong> Instructional Experience</li>
          <li>Coordinated Multi-Section Courses</li>
          <li>High-Enrollment STEM Programs</li>
        </ul>
      </div>
    </div>

    <!-- RIGHT COLUMN -->
    <div>
      <div class="media-card">
        <img src="/assets/images/teaching_whiteboard.png" 
             alt="Whiteboard facilitation">
      </div>

      <strong>Feedback Highlights</strong>
      <div class="quote-grid">
        <div class="quote-card">
          <div class="quote-tag">Clarity</div>
          Super good at explaining the material.
        </div>

        <div class="quote-card">
          <div class="quote-tag">Respect</div>
          Makes me feel respected as a student.
        </div>

        <div class="quote-card">
          <div class="quote-tag">Structure</div>
          Very well structured and expectations were clear.
        </div>

        <div class="quote-card">
          <div class="quote-tag">Confidence</div>
          Helped me feel prepared for exams.
        </div>
      </div>
    </div>

  </div>
</section>



<!-- ===== Undergraduate Role Band ===== -->
<section class="band band-warm">
  <div class="section-header">
    <h2>Undergraduate Instructional Leadership</h2>
    <p>Olivet Nazarene University • 2021–2024</p>
  </div>

  <div class="role-grid">
    <!-- Left: narrative + bullets -->
    <div>
      <p>
        Over three years, I served in progressively advanced instructional support roles across coordinated mathematics and science courses,
        contributing to student performance initiatives in both entry-level and upper-division classes.
      </p>

      <strong>Key Responsibilities</strong>
      <ul>
        <li>Delivered structured academic support across diverse student populations, including liberal arts, business, and STEM majors in the <a href="https://www.olivet.edu/academics/colleges/college-professional-studies/center-academic-excellence/">Math Lab</a></li>
        <li>Facilitated large-group review sessions for calculus, differential equations, and linear algebra</li>
        <li>Provided individualized 1-on-1 academic coaching through scheduled hours as a <a href="https://www.olivet.edu/academics/academic-support/">peer educator</a></li>
        <li>Managed weekly grading workflows and maintained digital grade databases</li>
        <li>Supported laboratory instruction in physical science courses, reinforcing technical concepts during experiments</li>
      </ul>

      <div class="impact-card">
  <h4>Overview</h4>
  <ul>
    <li><strong>3 Years</strong> Instructional Support Experience</li>
    <li>Progressed from Math Lab Tutor to Peer Educator</li>
    <li>Supported Entry-Level & Upper-Division Mathematics</li>
    <li>Delivered Large-Group Review Sessions</li>
    <li>Maintained Weekly Grading & Academic Databases</li>
  </ul>
</div>

    </div>

    <!-- Right: image + mini quote highlights -->
    <div>
      <div class="media-card">
        <img src="/assets/images/peer_educator.png" alt="Peer educator flyer/photo">
      </div>

      <strong>Feedback Highlights</strong>
      <div class="quote-grid">
        <div class="quote-card"><div class="quote-tag">Approachable</div> Very fun to be in her class and extremely approachable.</div>
        <div class="quote-card"><div class="quote-tag">Coaching</div> Gave hints that pointed groups in the right direction without giving away the answer.</div>
        <div class="quote-card"><div class="quote-tag">Support</div> Went out of her way many times to provide as much help as possible.</div>
        <div class="quote-card"><div class="quote-tag">Inclusivity</div> One of the most inclusive, supporting, and positive environments I’ve been in as a student.</div>
      </div>
    </div>
  </div>
</section>
