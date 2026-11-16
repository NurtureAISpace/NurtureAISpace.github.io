# NurtureAI Space

<div align="center">
  <img src="nurtureaispace-badge.jpg" alt="NurtureAISpace Mission Emblem" width="200" style="border-radius: 50%;" />
  <br />
  <h2>NurtureAI Space: Health Monitoring for Astronauts</h2>
  <p>NASA Space Apps Challenge 2026: <em>Create Health Monitoring Software for Astronauts on Space Missions</em>.<br />Daily check-in app, crew dashboard, and vitamin degradation forecast.</p>
  <p><strong>Developed by Team NurtureAISpace</strong></p>
  <p>
    <a href="https://nurtureaispace.github.io">Live Demo</a> | 
    <a href="https://nurtureaispace.github.io/app/">Astronaut Application</a> | 
    <a href="https://nurtureaispace.github.io/slides.html">Slide Deck</a> | 
    <a href="certificates/NASA_Space_Apps_Challenge_2026_Certificate.pdf">NASA Certificate</a>
  </p>
</div>

---

## Team

- **Suleyman Hajizadeh** - Lead Systems Architect and Research (`suleyman.hacizade1@gmail.com`)
- **Banu Gurbanzada** - Frontend Architecture and UI/UX Design (`banugurbanzade@gmail.com`)
- **Yunis Allahverdi** - AI/ML and Degradation Modeling (`allahverdiyunis@gmail.com`)
- **Faruk Karimli** - Computer Engineering and Life Support Simulation (`fkarimli23291@ada.edu.az`)

---

## Live Platform and Resources

- **Crew Dashboard:** https://nurtureaispace.github.io
- **Astronaut App (Offline-First Daily Check-In):** https://nurtureaispace.github.io/app/
- **Slide Deck:** https://nurtureaispace.github.io/slides.html
- **Official NASA Certificate (Galactic Problem Solver):** [Certificate PDF](certificates/NASA_Space_Apps_Challenge_2026_Certificate.pdf) | [Credential Dossier](https://suleimancertificates.github.io/certificates/nasa-space-apps-challenge-2026/)
- **Submission Guide:** [NASA Space Apps Challenge Guide (PDF)](docs/NASA_Space_Apps_Challenge_Submission_Guide.pdf)
- **Organization:** https://github.com/NurtureAISpace
- **Primary Source Code:** https://github.com/NurtureAISpace/mars-food-intelligence

---

## Technical Scope and Methodology

- **Personal Baseline Monitoring:** Uses NASA OSDR Inspiration4 datasets (OSD-569 and OSD-575) to compare physiological indicators against personal pre-flight baselines.
- **Kinetics Engine:** Models thermal degradation of vitamins C and B1 under varying storage temperatures via first-order Arrhenius kinetics.
- **Ration Optimization:** Computes balanced daily meal plans using SciPy linear programming (HiGHS solver) to meet exploration nutrition targets while minimizing resupply mass.
- **Autonomous Architecture:** The client-side astronaut application runs offline using local IndexedDB storage and biometric pseudonymization.

---

## Data Sources and Notes

This repository contains the static build of the web application deployed to GitHub Pages (built with `scripts/build_site.ps1` from the main repository).
- Core source code: [`NurtureAISpace/mars-food-intelligence`](https://github.com/NurtureAISpace/mars-food-intelligence).
- Parameter documentation: `docs/DATA_SOURCES.md` in the source repository.
- Research prototype: Designed for technical demonstration and exploration planning, not certified as a clinical medical device.
