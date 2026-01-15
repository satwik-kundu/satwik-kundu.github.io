---
layout: page
permalink: /services/
title: Services
show_title: false
description: # Contributions in reviewing and sub-reviewing.
nav: true
nav_order: 4
---

# Academic Services

---

<div class="timeline-item">
  <h3>Reviewer</h3>
  <ul class="service-list">
    <li class="service-category">Journals</li>
    
    <li><span class="venue">Springer Nature Quantum Machine Intelligence</span><span class="years">2025</span></li>
    <li><span class="venue">Elsevier Neurocomputing</span><span class="years">2025</span></li>
    <li><span class="venue">IEEE Computer Architecture Letters (CAL)</span><span class="years">2025</span></li>

    <li class="service-category">Conferences</li>
    <li><span class="venue">International Symposium on Computer Architecture (ISCA)</span><span class="years">2024-26</span></li>
    <li><span class="venue">International Symposium on High-Performance Computer Architecture (HPCA)</span><span class="years">2025</span></li>
    <li><span class="venue">International Conference on Quantum Computing and Engineering (QCE)</span><span class="years">2023-25</span></li>
    <li><span class="venue">International Symposium on Microarchitecture (MICRO)</span><span class="years">2022-25</span></li>
    <li><span class="venue">Design Automation and Test in Europe (DATE)</span><span class="years">2024-25</span></li>
    <li><span class="venue">International Conference on Computer‑Aided Design (ICCAD)</span><span class="years">2024</span></li>
    <li><span class="venue">International Symposium on Hardware Oriented Security and Trust (HOST)</span><span class="years">2023-24</span></li>
    <li><span class="venue">Asia and South Pacific Design Automation Conference (ASP‑DAC)</span><span class="years">2023</span></li>
    <li><span class="venue">International Conference on Computer Design (ICCD)</span><span class="years">2023</span></li>
    </ul>
</div>

<style>

  /* Specific styling for the category headers */
  .service-list .service-category {
    display: block; /* Overrides the flexbox of standard li items */
    font-size: 0.85em;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    font-weight: bold;
    color: #666; /* Or use var(--global-theme-color) with opacity */
    margin-top: 20px; /* Adds the separation you wanted */
    margin-bottom: 8px;
    border-bottom: 1px solid #e0e0e0; /* Adds a clean dividing line */
    padding-bottom: 2px;
  }

  /* Remove top margin for the very first category to save space */
  .service-list .service-category:first-child {
    margin-top: 0;
  }
  .timeline {
    border-left: 2px solid var(--global-theme-color);
    padding-left: 20px;
  }
  .timeline-item { margin-bottom: 20px; }
  .timeline-item h3 {
    color: var(--global-theme-color);
    font-weight: bold;
    margin-bottom: 10px;
  }

  /* ---------- list + alignment tweaks ---------- */
  .service-list {           /* replaces .timeline-item ul */
    list-style: none;
    margin: 0;
    padding: 0;
    font-size: 1.1em;
  }
  .service-list li {
    display: flex;          /* 2‑column layout */
    justify-content: space-between;
    gap: 1rem;
    padding: 5px 0;
  }
  .venue { flex: 1 1 auto; }         /* wraps naturally */
  .years {
    flex: 0 0 90px;         /* fixed width keeps a neat column */
    text-align: right;
    white-space: nowrap;
    color: var(--global-theme-color);
    font-weight: 500;
  }
</style>


