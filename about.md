<style>
  /* --- Global site-wide nav (CV · About · Links & resources) --- */
  .site-nav {
    position: sticky;
    top: 0;
    background: white;
    padding: 0.5rem 0;
    border-bottom: 1px solid #ddd;
    z-index: 2000;
  }

  .site-nav a {
    margin-right: 0.4rem;
  }

  /* --- Page-specific sticky nav (sections within the page) --- */
  .page-nav {
    position: sticky;
    top: 2.4rem; /* roughly the height of the site-nav; tweak if needed */
    background: white;
    padding: 0.4rem 0;
    border-bottom: 1px solid #eee;
    z-index: 1500;
  }

  .page-nav a {
    margin-right: 0.4rem;
  }

  /* Smooth scrolling */
  html {
    scroll-behavior: smooth;
  }

  /* Offset anchored headings so they appear below both nav bars */
  h2[id],
  h3[id] {
    scroll-margin-top: 126px; /* adjust if combined nav height changes */
  }
</style>

<nav class="site-nav">
  My pages:
  <a href="/">About</a> ·
  <a href="/index">CV</a> ·
  <a href="/links">Resources</a>
</nav>

<nav class="page-nav">
  About menu:
  <a href="#about">About me</a> ·
  <a href="#what">What I do</a> ·
  <a href="#research-interests">Research Interests</a> ·
  <a href="#tools-i-use">Tools & methods I use</a> ·
  <a href="#find-more">Where to find more</a> ·
  <a href="#curios-about">What I'm currently curios about</a> ·
</nav>

# About me {#about}

**Docent (associate professor), licensed clinical psychologist, PhD**  
Stockholm, Sweden  

I work at **Karolinska University Hospital** and am affiliated with **Karolinska Institutet**. My background spans leadership in healthcare, applying and implementing clinical psychology within healthcare, research within the field of behavioral medicine and chronic pain. These days I split my time between **clinical digitalisation**, **research**, and explorations of how I can contribute to **AI** safety and ethics.

---

## What I do {#what}

  - **Clinical digitalisation/service development**  
  - Supporting the development of **digital and hybrid clinical workflows** at Karolinska University Hospital.  
  - Interested in if/how digital tools and clinical workflows can create value in day-to-day clinical work and improve patient experiences and clinical outcomes.

  - **Research**  
  - Acceptance and Commitment Therapy (ACT) for longstanding pain.  
  - Psychometric evaluation of self-report measures in chronic pain and healthcare contexts.  
  - Studies on **ME/CFS** and **post-COVID-19 condition**, including symptom profiles, sickness behaviour, and rehabilitation.  

  - **AI & healthcare**  
  - Moving toward research on **applied clinical AI-based solutions** and **non-technical AI safety**.  
  - Curious about how AI can be integrated into real-world clinical workflows without losing sight of ethics, safety, and patients’ lived experience.

---

## Research interests {#research-interests}

- Chronic pain, ACT, processes of change  
- Digital and hybrid care interventions  
- Psychometrics and outcome measurement in healthcare  
- Post COVID-19 condition and ME/CFS  
- AI in healthcare, clinical decision support, and documentation tools  
- Implementation of narrow AI applications in healthcare, and broader non-technical AI safety issues 

---

## Tools & methods I use {#tools-i-use}

- **Statistics & AI-assisted R programming**: R (longitudinal models, mixture/latent class models, psychometrics). 
- **Study designs**: RCTs, longitudinal observational studies, psychometric validation, feasibility and implementation studies. 
- **Writing & documentation**: Structured, reproducible workflows; strong preference for transparent methods and open, well-documented code/analysis when possible.

---

## Where to find more {#find-more}

  - **CV & publication list**:  
  My full CV, publication list, and more details about ongoing work are available here: https://inamek.github.io/.github.io/

- **Publications**:  
  Find a list of original scientific articles, general articles, and book chapters as part of the CV-page: https://inamek.github.io/.github.io/#publications.

---

## What I’m currently curious about {#curios-about}

- How clinical narrow AI tools actually behave “in the wild” – in real clinics, with real constraints.  
- Practical ways to evaluate **AI safety** and robustness from a non-technical/clinical perspective.  
- How to design and evaluate digital interventions and workflows that (potentially) deliver value and integrate smoothly with the day-to-day reality of clinicians and patients.

---

If you’re interested in any of the above – whether from a clinical, research, or AI/safety angle – feel free to reach out.
