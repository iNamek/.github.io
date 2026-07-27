<style>
  /* --- Global site-wide nav (CV · About · Resources · Reading) --- */
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
  <a href="/about">About</a> ·
  <a href="/resources">Resources</a> ·
  <a href="/reading">Reading</a> ·
  <a href="/index">CV</a>
</nav>

<nav class="page-nav">
  Resources menu:
  <a href="#websites">Websites</a> ·
  <a href="#forums">Forums & Communities</a> ·
  <a href="#podcasts">Podcasts</a> ·
  <a href="#writings">Writings</a> ·
  <a href="#learning">Courses and learning resources</a> ·
</nav>

# Resources

A collection of links to resources I find useful or interesting.

---

## Websites {#websites}

**AI companies**<br>
***The major players***<br>
<a href="https://www.anthropic.com/">Anthropic (Board of directors, Dario Amodei, Daniela Amodei, Yasmin Razavi, Jay Kreps, and Reed Hastings)</a><br>
<a href="https://deepmind.google">Google Deep Mind (CEO, Demis Hassabis)</a><br>
<a href="https://ai.meta.com/">Meta AI (CEO, Mark Zuckerberg)</a><br>
<a href="https://openai.com/sv-SE/">OpenAI (CEO, Sam Altman)</a><br>
<a href="https://x.ai/">xAI (CEO Elon Musk)</a>

***Companies focusing specifically on AI safety***<br>
<a href="https://www.conjecture.dev/">Conjecture (Connor Leahy)</a><br>
<a href="https://ssi.inc/">Safe Superintelligence (Ilya Sutskever)</a><br>

**People**<br>
<a href="https://mila.quebec/en/directory/yoshua-bengio">Yoshua Bengio</a><br>
<a href="https://nickbostrom.com/">Nick Bostrom</a><br>
<a href="https://consc.net/">David Chalmers</a><br>
<a href="https://paulfchristiano.com/">Paul Christiano</a><br>

## Forums, Communities & Organisations {#forums}
<a href="https://www.alignmentforum.org/">Aligment Forum</a><br>
<a href="https://www.astralcodexten.com/">Astral Codex ten (Scott Alexander)</a><br>
<a href="https://www.lesswrong.com/">Less Wrong</a><br>
<a href="https://www.overcomingbias.com/">Overcoming Bias (Robin Hanson)</a><br>
<a href="https://lethalintelligence.ai/">A site covering the potential lethal dangers of upcoming Autonomous and General
Artificial Intelligence systems (AGI)</a><br>
<a href="https://safe.ai/">Center for AI Safety (CAIS)</a><br>
<a href="https://pauseai.se/xrisk">Ideell organisation som syftar till att mildra riskerna med AI)</a><br>
<a href="https://incidentdatabase.ai/cite/1152/">The AI Incident Database is dedicated to indexing the collective history of harms or near harms realized in the real world by the deployment of artificial intelligence systems.</a><br>

## Podcasts {#podcasts}
<a href="https://open.spotify.com/show/2Op1WO3gwVwCrYHg4eoGyP?si=137b39f2cd694d0f">Future of Life Institute Podcast</a>

## Miscellaneous Writings on AI {#writings}
<a href="https://ai-2027.com/">AI 2027; Daniel Kokatajlo, Scott Alexander, Thomas Larsen, Eli Lifland & Romeo Dean</a><br>
<a href="https://darioamodei.com/essay/machines-of-loving-grace">Machines of Loving Grace; Dario Amodei</a><br>
<a href="https://www.darioamodei.com/essay/the-adolescence-of-technology">The Adolescence of Technology; Dario Amodei</a><br>
<a href="https://harpers.org/archive/2026/03/childs-play-sam-kriss-ai-startup-roy-lee/">Child’s Play - Tech’s new generation and the end of thinking; Sam Kriss</a><br>
<a href="https://gwern.net/doc/ai/nn/1993-olazaran.pdf">A Sociological History of the Neural Network Controversy; Mikel Olazaran</a><br>

## Courses and learning resources {#learning}

**Courses and learning resources**<br>
<a href="https://www.elementsofai.se/">Elements of AI: course, in which part 1 covers the basics of AI, and part 2 gets into Python programming and touches on the applied aspects of developing AI-systems.</a><br>
