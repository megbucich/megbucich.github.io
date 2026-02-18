---
title: Projects
icon: fas fa-chart-area
order: 3
---

<style>
/* ===== Match the vibe of your other tabs ===== */
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

.ind-project-grid{
  display: grid;
  grid-template-columns: repeat(1, minmax(0, 1fr));
  gap: 1rem;
}

.group-project-grid{
  display: grid;
  grid-template-columns: repeat(1, minmax(0, 1fr));
  gap: 1rem;
}

.project-card{
  background: rgba(255,255,255,0.78);
  border: 1px solid rgba(0,0,0,0.08);
  border-radius: 14px;
  padding: 1rem;
  box-shadow: 0 10px 25px rgba(0,0,0,0.05);
}

.project-title{
  margin: 0 0 0.35rem 0;
}

.meta{
  font-size: 0.92rem;
  opacity: 0.85;
  margin: 0 0 0.6rem 0;
}

.tag-row{
  display: flex;
  gap: 0.5rem;
  flex-wrap: wrap;
  margin-bottom: 0.75rem;
}

.tag{
  display: inline-block;
  font-size: 0.78rem;
  padding: 0.2rem 0.55rem;
  border-radius: 999px;
  border: 1px solid rgba(0,0,0,0.10);
  background: rgba(255,255,255,0.6);
}

.small-note{
  margin: 0;
  line-height: 1.35;
}

.featured-grid{
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1rem;
  margin-top: 0.75rem;
}

@media (max-width: 900px){
  .featured-grid{
    grid-template-columns: 1fr;
  }
}

.figure-card{
  background: rgba(255,255,255,0.78);
  border: 1px solid rgba(0,0,0,0.08);
  border-radius: 14px;
  padding: 0.75rem;
  box-shadow: 0 10px 25px rgba(0,0,0,0.05);
}

.figure-card img{
  width: 100%;
  height: 220px;
  object-fit: contain
  border-radius: 10px;
  display: block;
}

.figure-caption{
  margin-top: 0.65rem;
  font-size: 0.95rem;
  opacity: 0.9;
  line-height: 1.35;
}

.figure-link{
  display: inline-block;
  margin-top: 0.5rem;
  font-weight: 700;
  text-decoration: none;
}


.card-figure-grid{
  display: grid;
  grid-template-columns: repeat(1, minmax(0, 1fr));
  gap: 0.75rem;
  margin-top: 0.75rem;
}

@media (max-width: 700px){
  .card-figure-grid{
    grid-template-columns: 1fr;
  }
}

.card-figure img{
  width: 100%;
  height: 100%;       /* adjust 160–220 */
  object-fit: contain;
  border-radius: 10px;
  display: block;
  background: white;
}

.card-caption{
  font-size: 0.85rem;
  margin-top: 0.4rem;
  opacity: 0.85;
}



</style>



<section class="band band-warm">
  <h2 style="margin-top:0;">Independent Projects</h2>


  <div class="ind-project-grid">


<div class="project-card">

  <h3 class="project-title">Modeling COPD Data with Linear Regression</h3>
  <p class="meta"><strong>Course:</strong> Linear Regression Models</p>

  <div class="tag-row">
    <span class="tag">Regression</span>
    <span class="tag">Diagnostics</span>
    <span class="tag">Model Building</span>
  </div>

  <p class="small-note">
    Built and analyzed regression models using COPD-related data to investigate relationships between clinical variables.
    Emphasis was placed on diagnostics, assumption checking, and interpretation rather than prediction alone.
  </p>

  
  <div class="card-figure-grid">

<div class="card-figure">
      <img src="/assets/images/BIC_sqrt_diag6_plotlm.png" alt="">
      <div class="card-caption">
        Cook's Distance graph used to identify influential observations.
      </div>
    </div>

<div class="card-figure">
      <img src="/assets/images/BIC_sqrt_fitted_vs_observed.png" alt="">
      <div class="card-caption">
        Fitted values versus observed data.
      </div>
    </div>

  </div>

</div>



<div class="project-card">
      <h3 class="project-title">Gibbs Phenomenon and Fourier Filtering</h3>
      <p class="meta"><strong>Course:</strong> Fourier Analysis</p>
      <div class="tag-row">
        <span class="tag">Fourier</span>
        <span class="tag">Visualization</span>
        <span class="tag">Filtering</span>
      </div>
      <p class="small-note">
        Studied the Gibbs phenomenon in Fourier series approximations of discontinuous functions.
        Applied filtering techniques to analyze overshoot behavior and convergence properties.
      </p>

<div class="card-figure-grid">

<div class="card-figure">
      <img src="/assets/images/square_wave_and_fourier_series (1).png" alt="Regression diagnostics plot">
      <div class="figure-caption">
        (insert caption)
      </div>
    </div>

<div class="card-figure">
      <img src="/assets/images/square_wave_exponential_p2_alpha16_N50 (1).png" alt="Regression diagnostics plot">
      <div class="figure-caption">
        (insert caption)
      </div>
    </div>

  </div>


    </div>

<div class="project-card">
      <h3 class="project-title">Fitness Data Optimization</h3>
      <p class="meta"><strong>Course:</strong> Advanced Numerical Optimization</p>
      <div class="tag-row">
        <span class="tag">Optimization</span>
        <span class="tag">Real Data</span>
        <span class="tag">Conjugate Gradient</span>
      </div>
      <p class="small-note">
        Used personal fitness data to estimate a conversion constant relating caloric intake to weight change.
        Formulated an objective function, applied numerical optimization methods, and interpreted results.
      </p>

<div class="card-figure-grid">

<div class="card-figure">
      <img src="/assets/images/Figures/contour_ncg (1).png" alt="">
      <div class="figure-caption">
        (insert caption)
      </div>
    </div>

<div class="card-figure">
      <img src="/assets/images/Figures/NonlinearCG_obs_vs_pred.png" alt="">
      <div class="figure-caption">
        (insert caption)
      </div>
    </div>
</div>
</div>
</div>
</section>





















<section class="band band-cool">
  <h2 style="margin-top:0;">Collaborative Projects</h2>

  <div class="group-project-grid">

<div class="project-card">
      <h3 class="project-title">Inverted Pendulum Stabilization</h3>
      <p class="meta"><strong>Course:</strong> Ordinary Differential Equations</p>
      <div class="tag-row">
        <span class="tag">Control</span>
        <span class="tag">Stability</span>
        <span class="tag">Feedback</span>
      </div>
      <p class="small-note">
        Studied the inverted pendulum as a model for unstable dynamical systems.
        Analyzed the differential equations and explored feedback-based control strategies to stabilize the system.
      </p>
      <div class="card-figure-grid">

<div class="card-figure">
      <img src="/assets/images/nofeedback (1).png" alt="">
      <div class="figure-caption">
        (caption)
      </div>
    </div>

 <div class="card-figure">
      <img src="/assets/images/withfeedback (1).png" alt="">
      <div class="figure-caption">
        (caption)
      </div>
    </div>

  </div>
    </div>







<div class="project-card">
      <h3 class="project-title">Singular Value Decomposition of Wind Data</h3>
      <p class="meta"><strong>Course:</strong> Linear Algebra</p>
      <div class="tag-row">
        <span class="tag">SVD</span>
        <span class="tag">Big Data</span>
        <span class="tag">Decision Making</span>
      </div>
      <p class="small-note">
        Applied singular value decomposition (SVD) to wind data to identify dominant modes and examine underlying patterns,
        focusing on interpretation in a real-world context.
      </p>
<div class="card-figure-grid">

 <div class="card-figure">
      <img src="/assets/images/scree_plot.jpg" alt="">
      <div class="figure-caption">
        (caption)
      </div>
    </div>

 <div class="card-figure">
      <img src="/assets/images/EOF1.jpg" alt="">
      <div class="figure-caption">
        (caption)
      </div>
    </div>


 <div class="card-figure">
      <img src="/assets/images/PC1.jpg" alt="">
      <div class="figure-caption">
        (caption)
      </div>
    </div>

  </div>

    </div>

<div class="project-card">
      <h3 class="project-title">Monarch Butterfly Population Dynamics</h3>
      <p class="meta"><strong>Course:</strong> Mathematical Modeling</p>
      <div class="tag-row">
        <span class="tag">Population Dynamics</span>
        <span class="tag">Stability Analysis</span>
      </div>
      <p class="small-note">
        Developed a mathematical model for monarch butterfly population dynamics by translating biological assumptions into
        a system of equations, analyzing behavior, and interpreting results.
      </p>
      <div class="card-figure-grid">

<div class="card-figure">
      <img src="/assets/images/temperature curve (1).png" alt="">
      <div class="figure-caption">
        (caption)
      </div>
    </div>

<div class="card-figure">
      <img src="/assets/images/parameter T0 (1).png" alt="">
      <div class="figure-caption">
        (caption)
      </div>
    </div>

<div class="card-figure">
      <img src="/assets/images/Mortality Rate of Larvae.png" alt="">
      <div class="figure-caption">
        (caption)
      </div>
    </div>

  </div>
    </div>

<div class="project-card">
      <h3 class="project-title">Object Classification with COIL-20 Data</h3>
      <p class="meta"><strong>Course:</strong> Data Science & Machine Learning</p>
      <div class="tag-row">
        <span class="tag">Classification</span>
        <span class="tag">Neural Networks</span>
      </div>
      <p class="small-note">
        Used the COIL-20 dataset to classify objects using classical ML methods and convolutional neural networks (CNNs).
        Compared performance and examined how model complexity affected accuracy.
      </p>
      <div class="card-figure-grid">

<div class="card-figure">
      <img src="/assets/images/cm_svm_rbf (1).png" alt="">
      <div class="figure-caption">
        (insert caption)
      </div>
    </div>

<div class="card-figure">
      <img src="/assets/images/Loss_VS_Epoch.png" alt="">
      <div class="figure-caption">
        (insert caption)
      </div>
    </div>

  </div>
    </div>


  </div>
</section>





