<style>
@import url('https://fonts.googleapis.com/css2?family=Atkinson+Hyperlegible:wght@400;700&family=Crimson+Pro:wght@400;500;600;700&display=swap');

/* Typography */
body, .markdown-body {
  font-family: 'Atkinson Hyperlegible', -apple-system, sans-serif !important;
  color: #2C1810 !important;
  line-height: 1.75 !important;
  background: #FDF8F4 !important;
}

h1, h2, h3, h4 {
  font-family: 'Crimson Pro', Georgia, serif !important;
  color: #1a3a34 !important;
  letter-spacing: -0.01em;
}

h1 { font-size: 2.4em !important; font-weight: 700 !important; }
h2 { font-size: 1.6em !important; font-weight: 600 !important; border-bottom: 2px solid #d4c5b0 !important; padding-bottom: 8px !important; margin-top: 2em !important; }
h3 { font-size: 1.2em !important; font-weight: 600 !important; color: #2D7D6E !important; border-bottom: none !important; }

/* Links */
a { color: #2D7D6E !important; text-decoration: none !important; border-bottom: 1px solid rgba(45, 125, 110, 0.3); transition: border-color 0.2s ease; }
a:hover { border-bottom-color: #2D7D6E !important; }
h1 a, h2 a, h3 a, p[align="center"] a { border-bottom: none !important; }

/* Lists */
ul { padding-left: 1.2em !important; }
li { margin-bottom: 0.4em !important; }
li::marker { color: #2D7D6E; }

/* Hero area */
.hero-banner {
  background: linear-gradient(135deg, #1a3a34 0%, #2D7D6E 50%, #3a8a7a 100%);
  color: #FDF8F4;
  padding: 40px 30px 30px;
  border-radius: 12px;
  text-align: center;
  margin: 20px 0 30px;
}
.hero-banner .hero-logo { margin-bottom: 12px; }
.hero-banner h1 { color: #FDF8F4 !important; font-size: 2.6em !important; margin-bottom: 8px !important; border-bottom: none !important; }
.hero-banner .hero-subtitle { font-size: 1.15em; opacity: 0.92; margin-bottom: 16px; font-family: 'Atkinson Hyperlegible', sans-serif; }
.hero-banner .hero-date {
  display: inline-block;
  background: rgba(255,255,255,0.15);
  padding: 8px 24px;
  border-radius: 24px;
  font-weight: 700;
  font-size: 1.05em;
  letter-spacing: 0.02em;
  font-family: 'Atkinson Hyperlegible', sans-serif;
}

/* Supporter badge */
.supporter-badge {
  text-align: center;
  margin: -10px 0 24px;
  padding: 12px 0;
}
.supporter-badge img { vertical-align: middle; }
.supporter-badge sub { color: #64748B; }

/* Section containers */
.section-highlight {
  background: #f3efea;
  border-radius: 10px;
  padding: 24px 28px;
  margin: 24px 0;
}
.section-highlight h2 { margin-top: 0.5em !important; }

/* Float-wrap images */
.float-right {
  float: right;
  width: 45%;
  margin: 8px 0 20px 28px;
  border-radius: 10px;
  box-shadow: 0 4px 20px rgba(0,0,0,0.08);
}
.float-left {
  float: left;
  width: 40%;
  margin: 8px 28px 20px 0;
  border-radius: 10px;
  box-shadow: 0 4px 20px rgba(0,0,0,0.08);
}
.clearfix::after { content: ""; display: table; clear: both; }

/* CTA-style contact section */
.cta-section {
  background: linear-gradient(135deg, #1a3a34, #2D7D6E);
  color: #FDF8F4;
  padding: 28px 32px;
  border-radius: 10px;
  text-align: center;
  margin: 32px 0;
}
.cta-section h2 { color: #FDF8F4 !important; border-bottom: none !important; margin-top: 0.3em !important; }
.cta-section a { color: #b8e6d8 !important; border-bottom-color: rgba(184, 230, 216, 0.4) !important; }
.cta-section a:hover { border-bottom-color: #b8e6d8 !important; }

/* Bottom illustration */
.closing-art { text-align: center; margin: 40px 0 20px; }
.closing-art img { border-radius: 10px; box-shadow: 0 4px 24px rgba(0,0,0,0.06); }

/* Schedule list styling */
.schedule-grid { columns: 2; column-gap: 36px; }
@media (max-width: 600px) { .schedule-grid { columns: 1; } }

/* Responsive */
@media (max-width: 768px) {
  .hero-banner { padding: 28px 20px 24px; }
  .hero-banner h1 { font-size: 1.8em !important; }
  .hero-banner .hero-logo img { width: 120px !important; }
  .float-right, .float-left { float: none; width: 100%; margin: 16px 0; }
  .section-highlight { padding: 18px 20px; }
}

/* Override theme containers if present */
.container, .container-lg { max-width: 860px !important; }
</style>

<!-- Hero with logo inside -->
<div class="hero-banner">
  <div class="hero-logo"><img width="160" src="images/MedHackathon_logo.png" alt="MedHackathon Asia logo"></div>
  <h1>MedHackathon Asia 2026</h1>
  <div class="hero-subtitle">Advancing genomic and health data collaboration across Asia</div>
  <div class="hero-date">July 27 &ndash; 31, 2026 &middot; Singapore</div>
</div>

<!-- Supporter — logo at 2x size -->
<div class="supporter-badge">
  <a href="https://www.npm.sg/">
    <img width="280" src="images/PRECISE_logo.png" alt="PRECISE — Precision Health Research, Singapore">
  </a>
  <br>
  <sub>Supported by <a href="https://www.npm.sg/">PRECISE — Precision Health Research, Singapore</a>.</sub>
</div>

## Overview

MedHackathon Asia is a regional meeting for researchers, clinicians, bioinformaticians, data stewards, and precision medicine leaders working to strengthen genomic and health data collaboration across Asia.

The 2026 edition builds on the discussions and project outcomes documented after [MedHackathon Asia 2025](https://medhackathon.github.io/2025/). The shared objective is to unlock the scientific and clinical value of Asian genomic diversity through practical collaboration on biobanks, data standards, computational workflows, and responsible governance.

<p align="center">
<img src="images/collaboration.jpg" style="width: 100%; max-width: 900px; border-radius: 10px; box-shadow: 0 4px 20px rgba(0,0,0,0.08);" alt="Paper-cut illustration of researchers collaborating around a table">
</p>

## Why this matters

Asia holds the world's largest and most diverse population base, but genomic resources across the region remain fragmented. National initiatives have grown rapidly, yet cross-border collaboration is still limited by differences in metadata standards, access models, privacy regulation, consent practices, and technical infrastructure.

MedHackathon Asia provides a working forum to address these gaps. The aim is not only to discuss policy, but to advance concrete, reusable frameworks for data discovery, secure analysis, and population-aware genomic interpretation.

## MedHackathon Asia 2025

The first edition of MedHackathon Asia was held in February 2025 at Burapha University, Chonburi, Thailand, bringing together researchers from seven jurisdictions — Thailand, Japan, Singapore, Korea, Hong Kong, Indonesia, and India. Participants worked across project tracks including the Asian Pangenome Initiative, genome-phenome archive development, variant analysis harmonization, pharmacogenomics, federated research environments, and data governance. A report summarizing the outcomes is in preparation. See the [MedHackathon Asia 2025 website](https://medhackathon.github.io/2025/) for details.

<img src="images/hacking.jpg" class="float-right" alt="Paper-cut illustration of researchers working together on laptops">

## 2026 focus areas

The current planning is centered on several themes emerging from the shared report:

- Harmonized biobank collaboration across Asian countries and initiatives
- Standardized metadata, analysis pipelines, and data submission practices
- Responsible data governance, including DAC workflows, privacy protection, and ethical data sharing
- Federated and secure research environments that respect national and institutional requirements
- Reference resources and analytical tools that better represent Asian populations
- Capacity building for precision medicine, including training and shared implementation practices

## Project tracks

The report highlights a set of ongoing and emerging workstreams that inform the 2026 program:

- Asian Pangenome Initiative
- Asian Genome-Phenome Archive data catalogue
- Variant analysis pipeline harmonization
- CNV analysis for clinical interpretation
- HPV DNA detection in PBMC whole-genome sequencing data
- Pharmacogenomics and polygenic risk score implementation for Asian populations
- Federation of Trusted Research Environments
- Ethical, legal, and social issues in genomic data sharing
- Federated aggregated variant browsing across Asian cohorts
- Imputation pipelines and servers for Thai, Japanese, and broader Asian reference panels

<div class="clearfix"></div>

<div class="section-highlight" markdown="1">

## Expected outcomes

MedHackathon Asia 2026 is expected to support:

- Stronger researcher-to-researcher networks across Asian genome and biobank initiatives
- Better alignment on practical standards for genomic and phenotypic data sharing
- Shared understanding of country-specific governance constraints and collaboration models
- Prototype tools, reference resources, and interoperable workflows for regional use
- Clearer roadmaps for federated analysis, trusted research environments, and archive development
- Continued momentum toward equitable precision medicine innovation grounded in Asian populations

</div>

## Schedule

**[The full schedule](https://github.com/medhackathon/2026/wiki/Schedule) will be published here.**

July 27&ndash;31, 2026

- **Monday, July 27** — Opening session, community updates and framing talks
- **Tuesday, July 28** — Tutorials, project breakout sessions
- **Wednesday, July 29** — Hackathon working sessions
- **Thursday, July 30** — Hackathon working sessions, cross-team reporting
- **Friday, July 31** — Wrap-up session, next-step planning

<img src="images/tea-break.jpg" class="float-left" alt="Paper-cut illustration of a tea break with lanterns and kueh">

## Venue

**D'MARQUEE at Downtown East**
1 Pasir Ris Close, Singapore 519599

The meeting takes place at D'MARQUEE in Downtown East, Pasir Ris, Singapore. The venue is locally hosted by PRECISE (Precision Health Research, Singapore). Attendee check-in is at the venue reception on Monday 27 July from 12:00.

### Getting there

- **MRT + bus (about 40 minutes from Changi Airport):** take the East–West Line to Pasir Ris (EW1), then bus 354 (or 3, 5, 6, 12, 17, 21, 89, or 358 East Loop) to the Downtown East stops.
- **Free Downtown East shuttle** runs between Pasir Ris MRT and the Downtown East Begonia Pick-up Point daily from 11:00 to 22:00, at about 15-minute intervals.
- **Taxi or Grab** from Changi Airport takes about 15 to 20 minutes.

## Accommodation

D'Resort, co-located with D'MARQUEE at Downtown East, is the on-site option. Confirmed participants receive a list of alternative hotels nearby, with indicative travel times, in the registration confirmation email. Participants book their own rooms.

<div class="clearfix"></div>

## Who should join

This event is intended for participants working in human genetics, medical informatics, biobanking, clinical genomics, bioinformatics, data governance, and related areas. We welcome researchers and practitioners interested in building shared infrastructure, standards, and collaborative projects for precision medicine in Asia.

## Registration

MedHackathon Asia 2026 is a small working meeting, and venue capacity is limited. Participation is therefore by invitation and review: the organizing committee shares the registration form through country contacts and community channels, and every registration is reviewed before a seat is confirmed.

If you are actively engaged in Asian biobank, genomic, or precision-medicine collaboration and would like to take part, please reach out through the [contacts below](#contact). The registration form will be shared with prospective participants as it opens.

<!-- Contact CTA -->
<div class="cta-section" markdown="1">

## Contact

Please join our Google group at [MedHackathon Asia](https://groups.google.com/u/4/g/medhackathon-asia) or email the organizers at [admin-medhackathon-asia@googlegroups.com](mailto:admin-medhackathon-asia@googlegroups.com).

</div>

<!-- Closing artwork -->
<div class="closing-art">
<img src="images/asian-network.jpg" width="480" alt="Paper-cut artwork of interconnected Asian flowers, birds, and otters symbolizing regional collaboration">
</div>

<script>
document.addEventListener("DOMContentLoaded", function() {
    var elementToRemove = document.querySelector('h1 a[href="https://medhackathon.github.io/2026/"]');
    if (elementToRemove) {
        var parent = elementToRemove.closest('h1');
        if (parent) {
            parent.remove();
        }
    }
});
</script>
