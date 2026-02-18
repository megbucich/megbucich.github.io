---
title: Research
icon: fas fa-globe-americas
order: 6
---

{% assign page.title = nil %}

<style>
/* ===== Shared style (matches your other tabs) ===== */
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
  margin: 0 0 0.25rem 0;
}
.section-header p{
  color: #374151;
  font-size: 0.95rem;
  margin: 0;
}

/* Cards */
.card{
  background: rgba(255,255,255,0.78);
  border: 1px solid rgba(0,0,0,0.08);
  border-radius: 14px;
  padding: 1rem;
  box-shadow: 0 10px 25px rgba(0,0,0,0.05);
}

/* Two-column layout for text blocks */
.two-col{
  display: grid;
  grid-template-columns: 1.25fr 0.9fr;
  gap: 1.25rem;
  align-items: start;
}
@media (max-width: 900px){
  .two-col{ grid-template-columns: 1fr; }
}

/* Figure styling */
.research-figure{
  background: rgba(255,255,255,0.78);
  border: 1px solid rgba(0,0,0,0.08);
  border-radius: 14px;
  padding: 0.75rem;
  box-shadow: 0 10px 25px rgba(0,0,0,0.05);
  margin: 0;
}

.research-figure img{
  width: 100%;
  height: auto;
  border-radius: 10px;
  display: block;
  object-fit: contain;
}

.caption{
  margin: 0.75rem 0 0 0;
  font-size: 0.95rem;
  opacity: 0.9;
  line-height: 1.35;
}

/* NEW: stack figures vertically to avoid whitespace from mixed aspect ratios */
.fig-stack{
  display: flex;
  flex-direction: column;
  gap: 1rem;
  margin-top: 0.75rem;
}

/* Tools list */
.tool-list{
  list-style: none;
  padding-left: 0;
  margin: 0;
}
.tool-list li{
  margin-bottom: 0.5rem;
}
.tool-label{
  font-weight: 700;
  opacity: 0.9;
}
</style>



<section class="band band-warm">
  <div class="two-col">
    <div>
      <p>
        I am currently a member of the <a href="https://scil.sdsu.edu/">Climate Informatics Laboratory</a> at
        San Diego State University, working under <a href="https://shen.sdsu.edu/">Distinguished Professor Sam Shen</a> and
        <a href="https://www.linkedin.com/in/danielle-lafarga-47b38116b/">Dr. Dani Lafarga</a> to gain experience
        with large datasets. My work focuses on data visualization and interpretation, particularly in the context of
        ocean temperature data. Data gathering and preprocessing are handled externally within the lab. My work begins at the analysis and visualization stage using provided datasets.
      </p>

    </div>

    <div class="card">
      <h3 style="margin-top:0;">Tools & Data</h3>
      <ul class="tool-list">
        <li><span class="tool-label">Programming:</span> Python</li>
        <li><span class="tool-label">Environment:</span> Jupyter Notebooks</li>
        <li><span class="tool-label">Data format:</span> NetCDF</li>
        <li><span class="tool-label">Data source:</span> <a href="https://www.cpc.ncep.noaa.gov/products/GODAS/">NOAA GODAS</a></li>
      </ul>
    </div>
  </div>
</section>

<section class="band band-sunset">
  <h2 style="margin-top:0;">ENSO Analysis Using GODAS Data</h2>

  <p>
    My current work involves analyzing ocean temperature data from the
    <a href="https://www.cpc.ncep.noaa.gov/products/GODAS/">NOAA Global Ocean Data Assimilation System (GODAS)</a>
    to study variability associated with <a href="https://www.weather.gov/mhx/ensowhat">El Niño–Southern Oscillation (ENSO)</a> events.
  </p>

  <p>
    ENSO is a recurring climate pattern involving temperature fluctuations in the equatorial Pacific Ocean that affects
    weather patterns globally. Scientists monitor
    <a href="https://climatedataguide.ucar.edu/climate-data/nino-sst-indices-nino-12-3-34-4-oni-and-tni">specific regions of the tropical Pacific</a>
    (Niño 1+2, 3, 3.4, and 4) to track and classify El Niño and La Niña conditions.
  </p>

  <!-- STACKED FIGURES (prevents whitespace from mixed aspect ratios) -->
  <div class="fig-stack">
    <div class="research-figure">
      <img src="/assets/images/enso_regions_map.png" alt="ENSO monitoring regions overlaid on global ocean temperature map">
      <p class="caption">
        <strong>Figure 1:</strong> ENSO monitoring regions (Niño 1+2, 3, 3.4, and 4) overlaid on ocean temperature at 5m depth.
        These regions in the equatorial Pacific are used to track El Niño and La Niña events.
      </p>
    </div>

    <div class="research-figure">
      <img src="/assets/images/nino_regions.png" alt="Detailed temperature distributions across four ENSO monitoring regions">
      <p class="caption">
        <strong>Figure 2:</strong> Temperature distributions within each ENSO monitoring region at 5m depth (1980).
        Each region captures different aspects of tropical Pacific variability.
      </p>
    </div>
  </div>
</section>

<section class="band band-cool">
  <h2 style="margin-top:0;">Approach & Focus</h2>

  <p>
    A central component of my work involves computing the volume of ocean water within specified temperature bins across depth,
    latitude, and longitude. This enables tracking how the volume of warm and cool water changes over time, which may provide
    insight into ENSO-related dynamics.
  </p>

  <!-- STACKED FIGURES (prevents whitespace from mixed aspect ratios) -->
  <div class="fig-stack">
    <div class="research-figure">
      <img src="/assets/images/nino_34_monthly.png" alt="Monthly time series of Niño 3.4 index">
      <p class="caption">
        <strong>Figure 3:</strong> Monthly volume variations based on temperature in the Niño 1+2 region.
      </p>
    </div>

    <div class="research-figure">
      <img src="/assets/images/nino_12_warm_vs_cold.png" alt="Volumes for warm and cold temperatures in nino 12 region">
      <p class="caption">
        <strong>Figure 4:</strong> Warm vs. cold volume behavior in a monitored ENSO region.
      </p>
    </div>
  </div>

  <div class="card" style="margin-top:1rem;">
    <h3 style="margin-top:0;">Current Status</h3>
    <p style="margin-bottom:0;">
      This work is ongoing and has not yet resulted in a formal report or publication. I participate in regular lab meetings
      and smaller working group discussions, where I receive feedback and direction.
    </p>
  </div>
</section>
